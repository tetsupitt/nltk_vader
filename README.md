# Setting up Anaconda's virtual environment

### Create the virtual environment
I assume requirements in nltk_env.yaml.
These requirements are loaded if you have conda.

conda env create -f nltk_env.yaml

check that you have an environment named nltk_env
the current environment has an * next to it. 

conda info --envs

### Activate the environment

conda activate nltk_env

Lastly, run the project

jupyter notebook

Then,click sentiment_analysis_coursereview.ipynb to open the file


To exit from virtual environment, back to base type

conda deactivate


# Updating virual environment

If you make changes to the nltk_env.yaml, then you need to update the virtual environment.
First you should deactivate the virtual environement

conda deactivate

You must be back to base environment. You can check the current enviroenment by

conda info --envs

Update the virtual environment by

conda env update --file nltk_env.yaml

You should activate the envionment to use the updated virtual environment.

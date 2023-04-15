### Setting up Anaconda's virtual environment

#create the env
conda env create -f nltk_env.yaml

#check that you have an environment named nltk_env
conda info --envs

#Activate the environment
conda activate nltk_env

#Lastly, run the project
jupyter notebook

#Then,click sentiment_analysis_coursereview.ipynb to open the file

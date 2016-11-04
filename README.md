# TACC

Use ontological representation for Natural Hazards Experimental Data for training Machine Learning models for various tasks like expeiment category prediction, answering experiment related questions etc.

## Installation

### Environment Setup
```shell
# Create a folder for virtual environments
$ cd ~/Workspace
$ mkdir virtualEnvs
$ cd virtualEnvs

# Create virtual environment and install dependencies.
$ conda create -n tacc python=2.7 anaconda
$ source activate tacc
$ conda install -n tacc gensim
$ conda install -n tacc BeautifulSoup4
$ conda install -n tacc nltk
$ conda install -n tacc scikit-learn

# Start ipython notebook in tacc environment 
$ cd path_to_git_repo
$ ipython notebook

# Deactivate the env after work is over
source deactivate

# To remove the virtual env (after project is complete)
$ conda remove -n word2vec -all
```

## API

TODO

# TACC

Use ontological representation for Natural Hazards Experimental Data for training Machine Learning models for various tasks like expeiment category prediction, answering experiment related questions etc.

## Installation

### Environment Setup
```shell
# Install virtualenv if its not already there. Generally comes presintalled with python
$ pip install virtualenv

# Create a folder for virtual environments
$ cd ~/Workspace
$ mkdir virtualEnvs
$ cd virtualEnvs

# Create virtual environment and activate it.
$ virtualenv AutoQA
$ source bin/activate

# Install required packages after activating the virtual environment.
$ pip install numpy
$ pip install scipy
$ pip install pandas
$ pip install seaborn
$ pip install -U scikit-learn

# MAC OSX CPU only binary for local installation
# Use appropriate binary from tensor flow site for other OS
$ export TF_BINARY_URL=https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-0.11.0-py2-none-any.whl
$ pip install --upgrade $TF_BINARY_URL

# Start ipython notebook in AutoQA environment 
$ cd ~/Workspace/AutoQA/
$ ipython notebook
```

## API

TODO

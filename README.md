# Udacity-AI-programming-in-Python
GENERAL INFO
This is the final image classifier project for the AI in Python nanodegree
The code is written in Python 3.7, and to get Python and Jupyter notebook, you can install Anaconda (free package manager).
The program uses Numpy, Pytorch, Matplotlib, PIL, json, and Pandas packages. This repo contains the first part of the project, which is training the classifier
and writing predict functiosn in a Jupyter notebook to make sure it works. 

IMAGE DATASETS
The flower images dataset used in this project is too big to include in this repo, but this program can be used with an image datasets. The directory must consist of three sets- training data, validation data, and test data. Within each of these folders, there should be a number of folders labelled as per their contents (for example, a folder within the training folder that contains pictures of dandelions could be named '5' where '5' corresponds to 'dandelions'). 

JSON FILE
The json file is required to convert the numerical labels of the folder to categorical labels (so for example, '5': 'dandelions', etc). This is because the classifier will output top indices which will need to be converted into the numerical class labels, which will need to be converted into categorical class labels.

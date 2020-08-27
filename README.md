# Udacity-AI-programming-in-Python
This is the final image classifier project for the AI in Python nanodegree
The code is written in Python 3.7, and to get Python and Jupyter notebook, you can install Anaconda (free package manager).
The program uses Numpy, Pytorch, Matplotlib, PIL, json, and Pandas packages. This repo contains the first part of the project, which is developing code for an image classifier built with Pytorch. We will be using a pretrained model and altering it's classifier. Another repo contains part 2 of the project, which converts everything to a command line application.

## INSTALLATION
-	First, to install Anaconda, go to the following website, choose your operating system type, and follow instructions:
https://docs.anaconda.com/anaconda/install/
-	Then, to clone the repository, go to anaconda prompt and type in following: 
Git clone https://github.com/Revak007/Udacity-AI-programming-in-Python.git 
-	To install Jupyter Notebook:
Conda install jupyter notebook
-	To run Jupyter Notebook, go the Anaconda prompt and type “jupyter notebook”. A browser will pop up in jupyter notebook in the current directory. 
-	To install numpy, pandas, matplotlib:
Conda install numpy, pandas, matplotlib
-	To install pytorch: 
Conda install pytorch

## IMAGE DATASETS
The flower images dataset used in this project is too big to include in this repo, but this program can be used with any image dataset. The data directory must consist of three sets- training data, validation data, and test data. Within each of these folders, there should be a number of folders labelled as per their contents (for example, a folder within the training folder that contains pictures of dandelions could be named '5' where '5' corresponds to 'dandelions'). 

## JSON FILE
The json file is required to convert the numerical labels of the folder to categorical labels (so for example, '5': 'dandelions', etc). This is because the classifier will output top indices which will need to be converted into the numerical class labels, which will need to be converted into categorical class labels.

## COMMENTS
-	While the code can generally be run in order, there are some parts that are not essential to the process and are added for later improvements:
    o	 You only need to download one pretrained model. I have included code for how to download two models in case you want to change the type of model you use
    o	 After the primary training section, I have including another code block that continues to train a model that has been saved to a checkpoint already. This is not needed if you use the classifier features that I have defined, since it reaches over 80% validation accuracy with my classifier. However, if you decide to change the classifier and need to run more epochs after saving to a checkpoint, you can run the extra training code block.


# UrgencyModelTraining

this project contains 5 folders:

* CNNGlove

* Data

* LSTMGlove

* LSTMPur1

* LSTMWord2vec

# Highlights:

The purpose of this project is to classify the emergency context into urgent and noturgent

The model was built with Long short-term memory(LSTM),Convolutional Neural Network (CNN) and Word Embeddings on Tensorflow.

# Reference:

* https://www.kaggle.com/kredy10/simple-lstm-for-text-classification

* https://www.kaggle.com/jacklinggu/keras-mlp-cnn-test-for-text-classification

* https://github.com/Harsh24893/EmotionRecognition

  ## Install dependencies
To get a development environment running you should :
Install virtualenv  :
```
pip install virtualenv
```
Create a new virtual environment and easily install all libraries by running the following command :
```
conda create  --name venv_name  --file requirements.txt
```
In the file requirements.txt you find all necessary dependencies for this project.
To activate the new environment:
```
source activate  venv_name
 
```

### In order to run this download Glove Vectors, since the file sizes are very large.

*[Glove] (https://nlp.stanford.edu/projects/glove/)

download : glove.840B.300d.zip

Create a folder in your project named Glove and add the file glove.840B.300d.txt 

Data source : amazon.com , yelp.com and imbd.com


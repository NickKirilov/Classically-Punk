# Welcome to Classically Punk
***

## Task
The goal is to understand and extract as much as possible data from audio files.
To train a model that can classify an audio file as a given genre
The success criteria is to achieve F1 score of more than 71% which is the F1 score of the baseline LogisticRegression model.

## Description
As a classification problem, I utilized LogisticRegression from scikit-learn library as a baseline model that achieved F1 score of 71%. I created a neural network using PyTorch. In the beginning I splitted the data to train/test/val - 60/20/20. However, it turned out that the train data samples are too little so I needed to increase the train data. Then, I had too little test and validation data. Finally, I switched to train/test data only with 70 to 30 split, and I utilized k-fold cross-validation because of the small number of samples available. 

## Installation
`pip install -r requirements.txt`

## Usage
You can use the model by running the notebook.

### The Core Team
Built by Nikolay Kirilov, student at Amsterdam Tech

<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px' /></span>

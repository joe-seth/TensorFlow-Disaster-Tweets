# TensorFlow-Disaster-Tweets
NLP mini project for identifying tweets classied as disaster and not a disaster
Disaster Tweet Analysis Project with Natural Language Processing
Deep Learning Project
python-shield


## Background
Twitter has been a key communication channel in times of emergency. The smartphones allows to announce an emergency being observed in real-time. Therefore, it serves a very useful tool for the agencies interested in programatically monitoring Twitter. Some efforts include the applications developed by disaster relief organizations and news agencies.

 ## Project 🎯
It’s not always clear whether a person’s words are actually announcing a disaster or not. The goal is to build a deep learning model that predicts which Tweets talks about real disasters and which ones do not.

This dataset was created by the company figure-eight and originally shared on their ‘Data For Everyone’s website. They hand-classified a dataset of 10,000 tweets. The dataset may contain text that may be considered as profane, vulgar, or offensive.


## Model Performances
Deep learning model performances are summarized below:

Baseline GAP1d has validation above 0.75 up to 5 epochs and then it starts to overfit on the train data.
Simple RNN model continously learns but results in important overfitting.
GRU model learns well and scores between 0.70 and 0.75 on the test data. It overfits quickly.
LSTM model learns much less than others. The rate of overfit is not much. The scores on test set are between 0.70 and 0.75.
There is a fifty-fifty chance of guessing whether a tweet talks about disaster or not. All the models seem to increase the predictions relative to this dumb model. Overfitting is common. GAP1d model is chosen as the final model.

## Technologies
Project is created with:

Python 3.8
Jupyter Notebook 6.4.12
Python libraries (see /requirements.txt)
VSCode
or this github project can be launched on colab-google without any local installations. It is free and requires Google account sign-in.

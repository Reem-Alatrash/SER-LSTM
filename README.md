# SER-RNN


## About
A speech emotion recognition (SER) system for a deep learning master-course. It uses a Long short-term memory network (LSTM), which is a recurrent neural network, to classify the emotion embedded within speech signals (both scripted and improvised) into 1 of 4 emotions: happy, sad, angry, neutral. 

The LSTM was built using Keras with a Tensorflow backend. The scripts are written in python 2.7 and it is *highly* recommended to upgrade them to python 3.x as support for python 2.7 stopped on January 1, 2020.

##### Input
The system takes as input pre-processed features extracted from the speech subset of the Interactive Emotional Dyadic Motion Capture (IEMOCAP) database.

##### Output
The system saves the predictions in a tab-seperated file which contains the IDs audio signals and their corresponding predicted class.

Example:
MSP-IMPROV-S08A-F05-S-FM02	happy

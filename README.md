# speech-emotion-recognition
current data sets:
RAVDESS : https://zenodo.org/record/1188976#.YX5urZ5BzIU

SAVEE : http://kahlan.eps.surrey.ac.uk/savee/Download.html


train data is (80%) and test data is (20%). 
The features that are extracted from audio files are normalized using mean standard value.
Various algorithms like CNN, LSTM, Bi-LSTM are tested on dataset
 Accuracy is calculated based on test dataset. 

1.Convolution Neural Network - CNN 
 In this algorithm we have used 7 hidden layers 2 drop out layers 1 batch normalization and max pooling layers are used for the construction. 
This proved to give a better performance than the current system 

2. Long-Short Term Memory - LSTM 
 In this algorithm 8 hidden layers 2 drop out layers, 2 batch normalization and 2 max pooling layers are used for the construction. 
This proved to give a better performance than the current system and has predicted the appropriate emotion. 

3. Bidirectional long-short term memory (bi-lstm) 
 In this algorithm We have used 7 hidden layers 2 drop out layers, batch normalization and 1 max pooling layers are used for the building the model. 
This proved to give less accuracy than other two algorithms. 



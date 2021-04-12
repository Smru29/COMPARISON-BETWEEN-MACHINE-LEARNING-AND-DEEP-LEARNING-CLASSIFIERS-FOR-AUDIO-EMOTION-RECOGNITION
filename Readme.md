COMPARISON BETWEEN MACHINE LEARNING AND DEEP LEARNING CLASSIFIERS FOR
AUDIO EMOTION RECOGNITION

This repository contains the work on comparison between machine learning
and deep learning classifier for audio emotion recognition using emodb
dataset from 

https://github.com/numediart/EmoV-DB (Unsorted Version)
https://coe.northeastern.edu/Research/AClab/Speech%20Data/


Installing Dependencies

The requisite to install the packages are 

1. tensorflow 
2. sklearn 
3. speechpy
4. keras 
5. librosa 
6. soundfile 
7. numpy
8. pyaudio
9. ffmpeg

Directory Structure

PythonCode - Contains the raw data of audio voices in .wav format of
four people (two male and two female voices) and is speaker independent
record.

Testing Data - containing the audio files used to predict the model in
deployment phase.

Feature Extraction - MFCC, Spectrogram, Mel-spectrogram

Details of the package

Deep Learning Classifier.ipynb - Deep learning algorithms are used to
predict emotions. It contains various algorithms used and accuracy of
the model is checked, and loss and validation errors are considered.

Algorithm used -

1.  Multilayer Perceptron Layer
2.  Convolution Neural Network

Machine Learning Classifier.ipynb - Machine learning algorithms are used
to predict emotions.It contains all the phase of model and the
deployment phase of the model as per the result of statistical testing.

1.  Support vector Machine
2.  Random FOrest Algorithm
3.  K-Nearest Neighbor Algorithm

Deployment -

From the Testing Data file, the test cases are taken to predict the
emotion of the audio voices, using the best accurate model in both the
classifiers.

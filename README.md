# EEG-SSVEP-Recognition

## Executive Summary
To create communication devices for patients with Amyotrophic Lateral Sclerosis (ALS), these devices must allow for users to communicate through only their ocular muscles and EEG data. To accurately interpret these EEG readings, this report looks at feasibility of different Machine learning models and data processing techniques to assist with the accurate tracking of a user’s intended target on a screen. This report employed the use of three different feature extraction techniques, Principal Component Analysis (PCA), Common Spatial Patterns (CSP) and Fast Fourier Transforms (FFT). These techniques were tested across three different Machine learning models, Long Short-Term Memory (LSTM), Support Vector Machine (SVM) and Random Forest Classifier to determine the most suitable configuration for real world use. Results from this experiment showed:  
• The combination of a 5th order Butterworth Bandpass Filter, PCA, CSP allowed a Random Forest Classifier to predict the correct tracking of a user’s target box on a screen with an accuracy of up to 100%, with a 20% test data split.  
• The effectiveness of implementing Machine Learning to assist in accurate eye gaze tracking from EEG data is promising and with further fine-tuning and testing be implemented into real world use  

## Contents of Repository  
* MLAss5MNE.ipynb - contains the code used for the machine learning project, with the aim to to develop machine learning modules for a human-machine interface (HMI) solution that will allow patients with Amyotrophic Lateral Sclerosis (ALS), who are rendered immobile except for their ocular muscles, to communicate through typing.  
* Figures directory - contains figures created in the jupyter notebook code for reference in project report    
* Machine Learning Assignment 5 z5308039.pdf - contains a detailed report on the machine learning implementation and analysis and discussion of results    
* results.txt - contains a text output of results derived from the jupyter notebook code  

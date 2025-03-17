# Music_Classification_ML
Classify music dataset using Machine Learning algorithms using Tensorflow and Skicit-learn

this classification is done by several features of music- tempo, loudness, beats, pitch, root mean square error, spectral_centroid, zero_crossing rate etc.
Extra features extracted from audio files, using librosa library of Python 
Classifying music into 10 generes - Classical , blues, rock, country, metal , pop, jazz etc. Each music genre has it's own feature combination and we  want to classify the dataset into 10 groups. At first we have used the Support Vector machine(SVM) algorithm both linear and rbf model

Collected music dataset from  https://www.kaggle.com/datasets/insiyeah/musicfeatures/data


below is accuracy of this model -confusion matrix
SVM model accuracy - approx 60% 

![image](https://github.com/user-attachments/assets/562755c1-d755-471f-aef3-b078226e4608)

next algorithm to apply - KNN, K-Means Clustering, Neural networks... etc
SVM performance can be increased using unsupervised learning PCA algorithm 


Next applied algorithm is KNN(K Nearest neighbours)
Here accuracy increases to 65%
below the new confusion maxtrix

![image](https://github.com/user-attachments/assets/493c674b-68f5-4179-8e6f-7305271d5b7b)




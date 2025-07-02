Speech Emotion Recognition (SER) using the CREMA-D dataset (https://www.kaggle.com/datasets/ejlok1/cremad).

The dataset was downsampled to 16 kHz for quicker processing and speech samples were kept into certain subfolders according to their emotional category.
Right now, the dataset is kept private as its a part of my M. Sc. (Engg) Thesis. After completion of the program, the dataset can be made available upon request.

We extracted three features from the speech samples, namely Mel-Frequency Cepstral Coefficients (MFCCs), Zero Crossing Rate (ZCR), and Short-term RMS Energy.
The MFCCs are considered to be the most important feature for speech data type.

Following, 10 machine learning models were run using a 5-fold cross-validation scheme to classify the emotional categories of the speech samples by leveraging the extracted features.
Logistic Regression, Naive Bayes, Random Forest, Support Vector Machine, XGBoost, Linear Discriminant Analysis, Ridge Classifier, SGD Classifier, Multi-layer Perceptron (ANN or Neural Network) and Calibrated SVM were run.


We obtained the following results:


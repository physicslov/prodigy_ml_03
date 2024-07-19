Cat vs Dog Classifier
This project is a machine learning model that classifies images of cats and dogs using a Support Vector Machine (SVM). The model has been trained on the Kaggle Dogs vs. Cats dataset, achieving an accuracy of 68.48%.

Table of Contents
* Project Overview
* Dataset
* Model Architecture
* Training
* Results
* Usage
* Dependencies

* Project Overview
This repository contains the code and resources for a cat vs dog image classifier. The classifier uses a Support Vector Machine (SVM) to distinguish between images of cats and dogs. The project demonstrates basic image preprocessing, feature extraction, and model training using SVM.
* Dataset
https://www.kaggle.com/c/dogs-vs-cats/data
The model was trained on the Kaggle Dogs vs. Cats dataset, which contains 25,000 labeled images of cats and dogs.


* Model Architecture
The classifier uses a Support Vector Machine (SVM) with the following steps:

Image Preprocessing: Images are resized to a uniform size and converted to grayscale.
Feature Extraction: Histogram of Oriented Gradients (HOG) features are extracted from the images.
Model Training: An SVM model is trained on the extracted features.
Training
The model was trained using the following steps:

* Data Preprocessing:

Resize images to 64x64 pixels.
Convert images to grayscale.
Extract HOG features.
* Model Training:

Split the dataset into training and testing sets (80% training, 20% testing).
Train an SVM model with the training set.
Evaluate the model using the testing set.
* Results
The classifier achieved an accuracy of 68.48% on the test set.

* Usage
To use the classifier, follow these steps:


# Image_Classifier

A comprehensive project implementing multiple image classification approaches, blending traditional machine learning techniques with deep learning strategies.

## **Project Overview**
Traditional Classifiers: Implements KNN, K-means (from scratch), and SVM (using scikit-learn) for classifying RGB images.

Feature Extraction: Utilizes HOG features extracted with OpenCV for early-stage classifiers.

Deep Learning: Integrates CNN-based classification for enhanced performance (project modules evolve from traditional to deep learning).

Modularity: Distinct separation between feature extraction and classification stages for flexible experimentation.

## **Structure**
feature_extraction.py	Functions for extracting HOG (and possibly other) features.
knn.py, kmeans.py	Custom implementation of KNN and K-means algorithms.
svm_classifier.py	SVM classifier with scikit-learn integration.
cnn_classifier.ipynb	Notebook with CNN-based classifier experiments and results.
utils.py	Utilities for data loading, preprocessing, visualization, etc.
dataset/	Contains image data (class-labeled).
README.md	High-level description, usage, and instructions.

## **How To Use**
Clone the repo and install dependencies
Python >=3.7, numpy, opencv-python, matplotlib, scikit-learn, etc.

Feature Extraction
Run relevant scripts to extract HOG features from your dataset.

Train Classifiers

For traditional: Use KNN/K-means scripts.

For SVM: Leverage the provided notebook or Python script.

For deep learning: Explore the CNN notebook.

Test and Evaluate
Evaluate performance metrics and compare approaches.

## **Features**
Compares classical and modern approaches to image classification.

Ready for custom dataset adaptation.

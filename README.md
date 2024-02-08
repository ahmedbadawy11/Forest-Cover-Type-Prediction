# README

## 🌲 Project Title: Forest Cover Type Prediction 


## Overview:
The Forest Cover Type Prediction project aims to predict the type of forest cover in the Roosevelt National Forest of northern Colorado based on various features of the landscape. This project utilizes machine learning algorithms to analyze a dataset containing observations of 30m x 30m patches within the wilderness areas. By predicting the forest cover type, this project contributes to environmental monitoring and management efforts.


## 👥 Team Members: 
- Ahmed Badawy
- Anas Elbattra
- Esraa Fayad

## 📊 Dataset: 
[Forest Cover Type Prediction Dataset](https://www.kaggle.com/competitions/forest-cover-type-prediction/data)

The study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. Each observation is a 30m x 30m patch. The task is to predict an integer classification for the forest cover type. The seven types are:
1. 🌲 Spruce/Fir
2. 🌲 Lodgepole Pine
3. 🌲 Ponderosa Pine
4. 🌳 Cottonwood/Willow
5. 🌳 Aspen
6. 🌲 Douglas-fir
7. 🌳 Krummholz

## Methodology:

We applied the following Machine Learning methods on the provided dataset:
1.  KNN
2.  Logistic Regression
3.  SVM
4.  Decision Tree Classifier
5.  Naive Bayes Classifier

This initial stage aimed to establish baseline performance. The top-performing models were KNN and Decision Tree.

![Performance Results](D:/Github/Forest-Cover-Type-Prediction/New folder/Image/output.png)

In the second stage, we applied feature selection methods and dimensionality reduction techniques with the top two models.

![Performance Results](D:/Github/Forest-Cover-Type-Prediction/New folder/Image/output2.png)

In the third stage, we introduced additional machine learning models such as Random Forest and two ensemble techniques to further enhance performance.

![Performance Results](D:/Github/Forest-Cover-Type-Prediction/New folder/Image/Untitldded.jpg)

The Stacking Classifier emerged as the top performer, combining the strengths of KNN and Decision Tree classifiers along with ensemble techniques.

Finally, we applied Public Key Infrastructure (PKI) for enhanced security and reliability.

![PKI](D:/Github/Forest-Cover-Type-Prediction/New folder/Image/Untitled.jpg)


## Project File
Group_5_project.ipynb: The Jupyter notebook containing the entire project.


This README provides an overview of our approach, methodologies, and outcomes in the Forest Cover Type Prediction project. For further details, refer to our code repository and associated documentation.


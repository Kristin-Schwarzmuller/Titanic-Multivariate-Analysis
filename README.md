# Titanic Multivariate Analysis

This repository contains the code and analysis for a multivariate analysis of the Titanic dataset. 
The analysis was conducted as part of the course "Multivariate Analysemethoden (SoSe 2022)" and carried out by Florian Landmann, Florian Obermeier, Kristin Schwarzmüller.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Preprocessing](#data-preprocessing)
3. [Analysis](#analysis)
    - [Principal Component Analysis (PCA)](#principal-component-analysis-pca)
    - [Diskriminanzanalyse](#diskriminanzanalyse)
    - [Neuronale Netze](#neuronale-netze)
    - [Decision Tree and Random Forest](#decision-tree-and-random-forest)
    - [KMeans Clustering](#kmeans-clustering)
    - [Confusion Matrix](#confusion-matrix)
4. [Running the Notebooks](#running-the-notebooks)
5. [Data Source](#data-source)

## Introduction

This project focuses on performing a multivariate analysis of the Titanic dataset to gain insights into various factors that may have influenced the survival of passengers. The analysis includes exploratory data visualization, dimensionality reduction techniques, classification models, and clustering.

## Data Preprocessing

Data preprocessing is performed in the notebook [01_Titanic_preprocess.ipynb](01_Titanic_preprocess.ipynb). In this notebook, the raw data from the [Titanic dataset](https://www.kaggle.com/competitions/titanic/data) is cleaned, transformed, and prepared for analysis.

## Analysis

The analysis itself is carried out in the notebook [02_Titanic.ipynb](02_Titanic.ipynb). Various multivariate analysis methods are applied to the preprocessed data, including:

### Principal Component Analysis (PCA)

PCA is utilized to reduce the dimensionality of the dataset while retaining as much relevant information as possible.

### Discriminant analysis

Discriminant analysis is employed to differentiate between passenger classes and investigate factors contributing to class separation.

### Neural networks

Neural networks are implemented to predict survival based on a set of input features.

### Decision Tree and Random Forest

A detailed analysis of decision trees and random forests is available in [Tree_analysis.ipynb](Tree_analysis.ipynb), focusing on their performance and feature importance.

### KMeans Clustering

Unsupervised KMeans clustering is applied to identify potential groups within the passenger data.

### Confusion Matrix

The confusion matrix is employed to evaluate the performance of classification models and understand the accuracy of predictions.

## Running the Notebooks

To run the notebooks, it is recommended to use Google Drive Cloud where the necessary CSV files are stored under the path `/content/drive/MyDrive/Colab Notebooks/MVA/`.

## Data Source

The dataset used in this analysis is the famous [Titanic dataset](https://www.kaggle.com/competitions/titanic/data) from Kaggle. It contains information about passengers on the Titanic, including features like age, gender, class, and survival status.

Feel free to explore the analysis and utilize the provided code for your own insights and learning!

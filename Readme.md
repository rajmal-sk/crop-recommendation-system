# Crop Recommendation System Machine Learning Model

## Introduction

Agriculture remains the foundation of human sustenance, yet it faces numerous challenges, particularly in selecting appropriate crops for diverse soil and weather conditions. Farmers often lack awareness regarding optimal crop choices based on specific environmental parameters. This knowledge gap results in resource wastage and suboptimal yields, posing a significant setback in agricultural productivity.

To address this challenge, this project leverages the power of machine learning techniques to provide farmers with informed crop selection recommendations. By implementing established machine learning models, this system predicts the most suitable crops based on specified constraints, such as soil type and weather conditions. Our objective is to mitigate resource wastage and enhance crop yield by delivering precise crop recommendations tailored to particular environmental parameters.

This project focuses on the practical application of existing machine learning models within the agricultural context. By doing so, we aim to bridge the gap between technological advancements and their direct application in optimizing agricultural practices.

## Features

- Predicts the most suitable crops based on soil and weather conditions
- Utilizes established machine learning models for accurate recommendations
- Aims to enhance crop yield and reduce resource wastage

## Dataset
The dataset used in this project was obtained from [Kaggle] (https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset/data), originally published by the Indian Council of Agricultural Research (ICAR), and comprises agricultural data crucial for crop yield prediction. It consists of 2200 samples, each containing 7 features vital for agricultural analysis. These features include:

- Nitrogen (N)
- Phosphorous (P)
- Potassium (K)
- Temperature
- Soil pH
- Humidity
- Rainfall

These features are fundamental indicators in determining soil fertility, environmental conditions, and overall suitability for cultivating various crops.

## Machine Learning Algorithms
To identify the most suitable crop based on specific soil and weather constraints among the 22 available crop types, we approached this as a classic classification problem. We employed the following well-known classification algorithms:

- Decision Tree Classifier
- K Nearest Neighbors Classifier
- Naive Bayes Classifier
- Support Vector Classifier

Among these, the Naive Bayes Classifier emerged as the most effective model. Its superior performance compared to other models led to its selection as the final choice for this project. The implementation of this model enables accurate predictions of suitable crops for planting, thereby maximizing crop yield and minimizing associated risks. This predictive capability offers substantial value in optimizing agricultural practices for specific soil and weather constraints.


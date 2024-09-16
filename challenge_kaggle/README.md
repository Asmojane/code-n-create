# Introduction

Welcome to my Kaggle challenges repository! All the projects here are developed using **Python** and various data science and machine learning libraries such as **Pandas**, **NumPy**, **Scikit-learn**, **TensorFlow**, and **Keras**. Each notebook focuses on applying machine learning techniques to different datasets and challenges, with detailed steps for data preprocessing, feature engineering, model building, and evaluation.

You can view my Kaggle profile and explore more of my work here: [Kaggle - JaneMathieuASMO](https://www.kaggle.com/janemathieuasmo).



# Kaggle Challenges Summary

## Titanic - Machine Learning from Disaster
The Titanic competition is a classic challenge in machine learning. The goal is to predict whether passengers survived the Titanic shipwreck based on variables such as age, gender, ticket class, and more.

In my three notebooks for this challenge:

- I began by exploring the dataset, handling missing data (e.g., filling in missing ages with the median), and creating new features such as family size and extracting titles from names.
- I preprocessed categorical data, including encoding gender and embarked location, and dropped irrelevant or highly incomplete columns like the cabin number.
- I trained multiple models (e.g., Logistic Regression, Decision Trees) and tuned hyperparameters. The final model achieved a score of **0.76555** on the public leaderboard.

---

## Digit Recognizer - Computer Vision
The Digit Recognizer competition focuses on computer vision, with the goal of correctly identifying handwritten digits from the MNIST dataset. This challenge introduces techniques such as image processing and neural networks.

In this notebook:

1. I performed data visualization to understand the MNIST dataset, displaying samples of handwritten digits and reshaping pixel data to prepare for modeling.
2. I used **K-Nearest Neighbors (KNN)** to classify the digits after normalizing the pixel values.
3. I used a **Convolutional Neural Network (CNN)** to classify the digits. The model consists of multiple convolutional and pooling layers to capture the spatial features of the images.

### The CNN architecture includes:
- Two convolutional layers with filters of sizes 32 and 64.
- MaxPooling layers to reduce the spatial dimensions.
- Fully connected layers to classify the output into one of 10 digit classes.
- A Dropout layer to prevent overfitting.

The model was trained using the **Adam optimizer** with **categorical cross-entropy** as the loss function. I also implemented a learning rate reduction strategy, which reduces the learning rate if the validation accuracy plateaus during training. The model achieved a high accuracy of **0.98867** on the validation set.


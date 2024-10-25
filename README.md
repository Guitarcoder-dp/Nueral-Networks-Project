Fruits and Vegetables Image Classification(EDA Project)
📑 Overview
This project uses Convolutional Neural Networks (CNN) to classify images of fruits and vegetables into different categories. The goal is to assign input images to one of several predefined classes with high accuracy.
📂 Data Preparation
Dataset: Fruits and Vegetables Image Recognition Dataset.
Data Splitting:
Training set: Used to teach the model.
Validation set: Helps fine-tune the model and avoid overfitting.
Test set: Used to assess the model’s performance on unseen data.
🧠 Network Architecture
We designed a CNN model for image classification following these steps:

Convolutional and pooling layers: Extract important features from the images.
Fully connected layers: Make predictions for each category.
Dropout layers: Prevent overfitting.
Softmax activation: Outputs probabilities for each class.




Binary Classification with Deep Learning Models(DL_project)

📋 Project Overview
In this project, we explore different deep learning models to perform a binary classification task, where the goal is to classify data into two categories:

Control
Patient
The dataset contains trial-related information, including eye movements, fixations, and stimulus properties. We use a range of models, each suited for different types of data patterns, to analyze the tabular dataset.

📂 Models Used
Convolutional Neural Network (CNN)
Uses 1D convolutional layers to capture spatial dependencies in sequential data.
Gated Recurrent Unit (GRU)
Models temporal dependencies in the sequential data.
Feed-Forward Neural Network (FNN)
Tests how a non-sequential model performs on the dataset.
Long Short-Term Memory (LSTM)
Captures long-term dependencies in sequential data.
Simple RNN
Focuses on short-term dependencies in sequences by reusing the same weights.
🔄 Data Preprocessing
Remove unnecessary columns.
Convert string labels (like "Control" and "Patient") to numeric values.
Split the data into training and testing sets for evaluation.
🛠️ Model Training
Framework used: Keras
Loss functions and optimizers: Chosen based on the model type.
Training and Testing:
Train each model on the training set.
Evaluate performance on the test set.






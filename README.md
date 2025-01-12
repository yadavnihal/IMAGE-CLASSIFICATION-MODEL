# IMAGE-CLASSIFICATION-MODEL

Steak, Pizza, or Sushi Classification Project

Project Overview

This project focuses on classifying food images into three categories: steak, pizza, or sushi. Using PyTorch and deep learning techniques, the model predicts the category of an input image with high accuracy.

Steps Involved

##Step 1: Collecting and Preparing Data

Collecting Data: A labeled dataset of food images was gathered.

Organizing Data: The dataset was structured into training, validation, and test sets.

Cleaning Data: Duplicate and irrelevant entries were removed to ensure data quality.

##Step 2: Training the Model

Model Architecture: A convolutional neural network (CNN) was designed for image classification.

Training: The model was trained using PyTorch, employing the CrossEntropyLoss function and Adam optimizer.

Validation: The model was evaluated on the validation dataset to tune hyperparameters and improve performance.

##Step 3: Testing the Model

Testing: The model was tested on unseen data to assess its generalization ability.

Metrics: Accuracy, precision, recall, and F1 score were computed to evaluate model performance.

##Step 4: Making Predictions

A user-friendly script was developed to allow inference on new images.

##Step 5: Data Visualization

Training and validation loss/accuracy were plotted to monitor performance.

Confusion matrices were created to visualize classification results.

##Conclusion

This project successfully implements an image classification model to distinguish between steak, pizza, and sushi. The model's accuracy and usability make it a valuable tool for food image recognition tasks.


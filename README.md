# American-express
This project implements an Artificial Neural Network (ANN) using TensorFlow/Keras to analyze and predict outcomes from the america.csv dataset.
# Data Preprocessing
Loading the Data:
Load the dataset and split it into features (X) and target (y).
Handling Missing Values:
Remove rows where the target column contains missing values.
Encoding Categorical Data:
Label Encoding: Converts categorical data in one column to numerical labels.
One-Hot Encoding: Transforms another categorical column into binary vectors.
Feature Scaling:
Standardize numerical features using StandardScaler to ensure equal importance during training.
Splitting the Dataset:
Split the data into training (80%) and testing (20%) sets using train_test_split.
# ANN Creation
Architecture:
Two hidden layers with 5 units each and ReLU activation.
Output layer with 1 unit and sigmoid activation for binary classification.
Compilation:
Optimizer: adam
Loss: binary_crossentropy
Metric: accuracy
# Training the ANN
Train the model on the training data for 120 epochs with a batch size of 32.
# Making Predictions
Predict outcomes for new inputs and the test set.
Convert probabilities to binary predictions (True or False) using a threshold of 0.5.
# Model Evaluation
Confusion Matrix: Visualize the model's performance in terms of true/false positives and negatives.
Accuracy Score: Calculate the percentage of correct predictions.

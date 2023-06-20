# Predicting-Sales-of-Alexa
This code performs binary classification using KNN and logistic regression. It starts by importing necessary libraries like numpy, matplotlib, and pandas. 
The dataset, 'Alexa_dataset.csv', is loaded using pandas, and the independent and dependent variables are extracted. 
The dataset is then split into training and testing sets. 
Feature scaling is applied to standardize the features using StandardScaler. 
KNN and Logistic regression is used as the classification algorithm, and the classifier is trained on the scaled training data. 
The trained classifier is then used to predict the target variable for the testing data. 
Several evaluation metrics such as accuracy, precision, and recall are calculated using functions from sklearn.metrics. 
Additionally, a visualization function called "Visualizer" is defined to plot the decision boundary of the classifier along with the actual data points for both the training and testing sets. 
This code provides a complete workflow for binary classification, including data preprocessing, model training, evaluation, and visualization.

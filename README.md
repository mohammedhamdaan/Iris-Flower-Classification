# Iris-Flower-Classification
In this project, you will build a simple Machine Learning model to classify iris flowers into one of three species: • Setosa • Versicolor • Virginica Classification is based on sepal and petal measurements. This classic dataset is ideal for learning basic supervised learning techniques.
# Iris Flower Classification - Week 1 Project

This project is part of the NSP Nexus AI/ML Internship.

## Objective
To classify iris flowers into Setosa, Versicolor, or Virginica using a machine learning model (KNN or Decision Tree).

## Technologies Used
- Python
- Google Colab
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

## Steps
1. Load and explore the dataset
2. Visualize relationships
3. Split the data
4. Train the model
5. Evaluate performance
How It Works
This project follows a basic Machine Learning pipeline to classify iris flowers using petal and sepal measurements.

Step-by-Step Process:
Import Libraries
Loads all required Python libraries like pandas, matplotlib, seaborn, and sklearn.

Load the Dataset
Uses sklearn.datasets.load_iris() to import the Iris dataset and converts it into a pandas DataFrame for easier analysis.

Explore the Dataset
Displays the first few rows, data structure, and summary statistics.
Visualization tools like pairplot and heatmap are used to understand feature relationships.

Prepare the Data
Separates the features (X) from the target labels (y) and splits them into training and testing sets using an 80-20 ratio.

Train the Model
Trains a K-Nearest Neighbors (KNN) classifier on the training data using model.fit().

Make Predictions
Uses the trained model to predict the species of iris flowers in the test dataset.

Evaluate the Model
Evaluates accuracy and prints a confusion matrix and classification report to measure the model's performance.

Visualize Results
Displays a heatmap of the confusion matrix to better understand how well the model performed across all classes.

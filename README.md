# NeuroNexus
This is my winter internship project repository in which i did 2 task of my internship.

It is a dataset regarding the Iris flower classification and employing various machine learning models for classification purposes. The provided code involves several steps:

Data Loading and Exploration: Loading the Iris dataset, displaying dataset information, summary statistics, and checking the distribution of target labels.

Preprocessing: Splitting the data into training and test sets, scaling the features using StandardScaler.

Model Training and Evaluation: Training models like K-Nearest Neighbors (KNN), Random Forest, Support Vector Machines (SVM), Decision Trees, and a Voting Classifier, then evaluating their performances using accuracy, confusion matrix, and classification reports.

Hyperparameter Tuning: Using GridSearchCV to find the best hyperparameters for KNN and Random Forest models.

Dimensionality Reduction: Applying PCA for dimensionality reduction and visualizing the reduced-dimensional data.

Model Comparison: Comparing multiple models using cross-validation and printing their mean accuracy scores.

SHAP (SHapley Additive exPlanations) Visualization: Visualizing feature importances for the Random Forest model using SHAP values.

Custom Scatter Plot Visualization: Creating a custom scatter plot using Seaborn to visualize the relationships between features while differentiating species.

It is an end-to-end pipeline for performing classification tasks on the Iris dataset using various machine learning models. Let's break down the code and provide an overview:

1. Data Loading and Exploration
Loading Data: Reading the Iris dataset from a CSV file.
Exploratory Data Analysis (EDA):
info(): Displaying information about the dataset.
describe(): Showing summary statistics.
Checking the distribution of target labels using value_counts().
2. Data Preprocessing
Splitting Data: Dividing the dataset into training and testing sets.
Feature Scaling: Using StandardScaler to scale the numerical features.
3. Model Building and Evaluation
K-Nearest Neighbors (KNN):

Training a KNN classifier.
Making predictions and evaluating performance using accuracy, confusion matrix, and classification report.
Performing cross-validation for KNN model evaluation.
Random Forest, SVM, Decision Tree:

Building classifiers for Random Forest, SVM, and Decision Tree models.
Making predictions and evaluating performance for each model.
Voting Classifier:

Creating an ensemble model (Voting Classifier) using KNN, Random Forest, and SVM.
Evaluating its performance.
4. Dimensionality Reduction
PCA (Principal Component Analysis):
Reducing dimensions to 2 using PCA and visualizing the reduced-dimensional data.
5. Model Comparison
Cross-Validation: Comparing models (KNN, Random Forest, SVM, Decision Tree) using cross-validation to estimate their performance.
6. Hyperparameter Tuning
Grid Search: Performing hyperparameter tuning for KNN and Random Forest using GridSearchCV.
7. Feature Importance Visualization
SHAP Values: Using SHAP (SHapley Additive exPlanations) to visualize feature importances for the Random Forest model.
8. Custom Visualization
Pairplot Visualization: Using Seaborn's PairGrid to create custom scatter plots for visualizing relationships between features while differentiating species.
9. Libraries and Modules Used
NumPy, pandas for data manipulation
sklearn for model building, preprocessing, evaluation, and hyperparameter tuning
matplotlib and seaborn for data visualization
shap for feature importance visualization

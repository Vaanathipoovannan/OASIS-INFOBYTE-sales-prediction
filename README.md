# OASIS-INFOBYTE-sales-prediction

Random Forest Regression for Advertising Dataset
This Python script uses Random Forest Regression to predict sales based on advertising data.

Overview
The dataset used in this script is from the 'Advertising.csv' file. The script performs the following steps:

Load the dataset using pandas.
Data cleaning and preprocessing:
Dropping unnecessary columns.
Splitting the dataset into predictors (x) and target (y) variables.
Splitting the data into training and testing sets.
Scaling the features using StandardScaler.
Training a Random Forest Regressor model on the training data.
Evaluating the model on the test data and calculating the R-squared score.
Usage
To run this script:

Ensure you have Python installed on your system.

Install the required libraries using pip:

Copy code
pip install numpy pandas scikit-learn
Download the 'Advertising.csv' file and place it in the appropriate directory.

Run the script:

Copy code
python random_forest_regression.py
Dependencies
numpy
pandas
scikit-learn

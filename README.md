# Placement-prediction-using-Logistic-Regression
Placements are crucial for students and educational institutions as they help build a strong foundation for professional careers and enhance the institution's reputation in the education market.
This project aims to predict the placement status of students based on various attributes using the Logistic Regression algorithm.

# Objective
The objective of this project is to develop a predictive model that can determine whether a student will be placed or not based on their qualifications, historical data, and experience. The model uses logistic regression, a supervised classification algorithm, to predict the binary outcome (placement status).

# Dataset
The dataset used in this project contains information about students, including:

* Secondary school percentage
* Higher secondary school percentage
* Degree percentage
* Degree type
* Work experience
The dataset is in CSV format and includes over 200 records with multiple attributes.

Steps Involved
Importing Necessary Libraries:

Import libraries such as Pandas, NumPy, Matplotlib, and Scikit-learn for data manipulation, visualization, and modeling.
Reading the Dataset:

Load the dataset and check its contents to understand the structure and attributes.
Data Preprocessing:

Drop unnecessary columns and convert categorical columns to numerical values using encoding techniques.
Splitting the Dataset:

Split the dataset into features (X) and labels (Y), and further divide it into training and testing sets.
Training the Model:

Train the logistic regression model using the training data.
Making Predictions:

Use the trained model to make predictions on new data and the test set.
Evaluating the Model:

Evaluate the model's performance using accuracy score and confusion matrix to understand its effectiveness.

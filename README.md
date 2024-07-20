## Simple Linear Regression
This project demonstrates the implementation of a simple linear regression model to predict salaries based on years of experience. The code uses Python and popular data science libraries such as NumPy, Pandas, Matplotlib, and Scikit-learn.

## Features
Loads and preprocesses the dataset.
Splits the dataset into training and test sets.
Trains a simple linear regression model on the training set.
Makes predictions on the test set.
Visualizes the results of the training and test sets.

## Prerequisites
Before you begin, ensure you have met the following requirements:

Python 3.x
NumPy library
Pandas library
Matplotlib library
Scikit-learn library
You can install the required libraries using pip:

sh
Copy code
pip install numpy pandas matplotlib scikit-learn
Usage
Clone the repository to your local machine.
sh
Copy code
git clone https://github.com/your-username/simple-linear-regression.git
Navigate to the project directory.
sh
Copy code
cd simple-linear-regression
Ensure you have the Salary_Data.csv file with the dataset.
Run the simple_linear_regression.py script.
sh
Copy code
python simple_linear_regression.py


## How It Works
The dataset is loaded from a CSV file (Salary_Data.csv) which contains data on salaries and years of experience.
The dataset is split into training and test sets using Scikit-learn's train_test_split function.
A simple linear regression model is trained on the training set.
Predictions are made on the test set.
The results are visualized using Matplotlib, showing the relationship between years of experience and salary for both the training and test sets.
Files
simple_linear_regression.py: The main script to run the simple linear regression model.
Salary_Data.csv: CSV file containing the dataset.

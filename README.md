# All-possible-linear-regression-on-top-of-insurance-dataset
objectives: To understand the structure of our data, visaulizing, building simle linear model, multilinear model using sklearn and selecting best model to fit on top of this dataset to make accurate predicts

# Insurance Data Linear Regression

This repository contains a Python implementation of linear regression on an insurance dataset. The goal of this project is to understand the dataset's structure, implement simple linear regression, and multiple linear regression to predict values related to medical charges.

## Objective

The main objectives of this project are:

1. To understand the structure of the dataset.
2. To implement simple linear regression and predict values.
3. To implement multiple linear regression and predict values.

## Domain

The dataset used in this project falls within the medical domain and contains information related to medical insurance charges.

## Tasks to be Performed

### 1. Read the Dataset and Explore its Structure

- Read the insurance dataset from a `.csv` file.
- Use the Seaborn library to create a pair plot for all of the dataset's columns, helping us gain insights into the relationships between variables.

### 2. Simple Linear Regression

- Divide the dataset into training and test sets with an 80:20 ratio.
- Build a simple linear regression model where the dependent variable is 'charges,' and the independent variable is 'age.'
- Predict the values on the test set and calculate the root mean square error (RMSE).

### 3. Multiple Linear Regression

- Build a multiple linear regression model where the dependent variable is 'charges,' and the independent variables are 'children' and 'bmi.'
- Predict the values on the test set and calculate the root mean square error (RMSE).

## Getting Started

Follow the steps below to get started with this project:

1. Clone this repository to your local machine using the following command:

   ```shell
   git clone https://github.com/your-username/insurance-linear-regression.git
   ```

2. Navigate to the project directory:

   ```shell
   cd insurance-linear-regression
   ```

3. Install the required Python packages (you can use a virtual environment):

   ```shell
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook or Python script to perform the tasks outlined above.

## Dataset

The insurance dataset used in this project is available in the `insurance.csv` file.

## Results

After completing the tasks, you will find the results of the linear regression analysis in the project's notebook or script, along with visualizations and error metrics.

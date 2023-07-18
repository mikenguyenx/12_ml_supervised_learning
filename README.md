# Supervised Machine Learning for Credit Risk

Credit risk poses a classification problem that’s inherently imbalanced. This is because healthy loans easily outnumber risky loans. In this Challenge, you’ll use various techniques to train and evaluate models with imbalanced classes. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

What You're Creating
Using your knowledge of the imbalanced-learn library, you’ll use a logistic regression model to compare two versions of the dataset. First, you’ll use the original dataset. Second, you’ll resample the data by using the RandomOverSampler module from the imbalanced-learn library.

For both cases, you’ll get the count of the target classes, train a logistic regression classifier, calculate the balanced accuracy score, generate a confusion matrix, and generate a classification report.

## Technologies

Programming Languages: Python 3.7.13

Interactive Development Environment: JupyterLab 


Libraries: 
- Pandas - a Python library that is used for data manipulation, analysis, and visualization. 
- Numpy - A popular open-source numerical computing library for Python which provides a powerful array object and a collection of mathematical functions.
- Sklearn - also known as Scikit-learn, which is a popular machine learning library in Python that provides a wide range of tools and algorithms for machine learning tasks such as classification, regression, clustering, and dimensionality reduction.

Operating System(s):  Any operating system that supports Python, including Windows & macOS.

## Installation Guide

To run this analysis, make sure you install the necessary dependencies:

1. Install Python: https://www.python.org/downloads/
2. Install and run Jupyter Lab:  https://jupyter.org/install
3. Clone the repository: git clone "https://github.com/mikenguyenx/12_ml_supervised_learning.git" using git or download the ZIP file and extract it to a local directory.

## Usage

To run the script:

1. Open a terminal or command prompt and navigate to the directory with the analysis.
2. Open `credit_risk_resampling.ipynb` in Jupyter Lab.
3. Run the code cells by clicking on the run button or by pressing the `Shift + Enter` key combination to load and preprocess the data, and generate and optimize machine learning model.

## Instructions

This challenge consists of the following subsections:

- Split the Data into Training and Testing Sets

- Create a Logistic Regression Model with the Original Data

- Predict a Logistic Regression Model with Resampled Training Data

- Write a Credit Risk Analysis Report

## Supervised Learning Logistic Regression Classifier Model

### Results from Original Data
![original](original.png)

### Results from Resampled Data
![resampled](resampled.png)

## Contributors

Mike Nguyen

## License

MIT
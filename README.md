# Customer-Churn-Analysis
This repository contains code and resources for analyzing customer churn in the telecommunications industry. The goal of this project is to develop a predictive model that can identify customers who are likely to churn, allowing the company to take proactive measures to retain those customers.

## Table of Contents

- [Business Overview](#business-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Business Overview

Syria Tel Company is a telecommunications company providing various services such as mobile, internet, and landline connections to customers in Syria. Customer churn, which is defined as customers quitting a service or transferring to a rival, is a worry for the business. Because it affects sales and client loyalty, churn is a major problem for the business. Your objective is to create a prediction model that can spot clients who are most likely to leave, allowing the business to take preventative action to keep them.

## Installation

To use the code in this repository, you need to have the following dependencies installed:

- Python 3.7 or higher
- Jupyter Notebook
- Required Python libraries (numpy, pandas, scikit-learn, matplotlib, etc.)

You can install the required Python libraries by running the following command:
pip install -r requirements.txt


## Usage

To run the code and reproduce the analysis, follow these steps:

1. Clone this repository:

2. Navigate to the project directory:

3. Launch Jupyter Notebook:

4. Open the `Final_Customer_Churn.ipynb` notebook in your browser.

5. Follow the instructions in the notebook to execute the code cells and perform the analysis.

## Data
The dataset to be used is Syria Customer Churn from: https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset
This is a classification problem because, churn, the target variable is boolean whic we will convert to binary values(0 and 1). 
The dataset is Customer_churn.csv above. It contains information about customers, their usage patterns, and whether they have churned or not. The dataset is provided in CSV format.

## Modeling

The modeling process involves building a predictive model to classify customers as churned or non-churned based on various features. We explore different machine learning algorithms, such as logistic regression, decision trees, and random forests, to find the best-performing model.

## Evaluation

The evaluation of the models is based on several metrics, including accuracy, F1 score, recall, and precision. The performance of the models is compared, and the most suitable model is selected. 

## Contributing

Contributions to this project are welcome. If you have suggestions, bug fixes, or enhancements, please submit a pull request or open an issue.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.





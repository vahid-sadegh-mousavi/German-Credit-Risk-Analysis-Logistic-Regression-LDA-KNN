# German-Credit-Risk-Analysis-Logistic-Regression-LDA-KNN

![Project Image](project_image.png)

## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Data Source](#data-source)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Models](#machine-learning-models)
- [Evaluation Metrics](#evaluation-metrics)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Welcome to the German Credit Risk Analysis project! This repository contains a comprehensive analysis of credit risk using various machine learning techniques. We explore the German credit dataset, preprocess the data, build machine learning models, and evaluate their performance.

## Project Overview
This project includes:
- Data preprocessing to handle missing values and outliers.
- Implementation of machine learning models, such as Logistic Regression, Linear Discriminant Analysis (LDA), and K-Nearest Neighbors (KNN).
- Model evaluation using accuracy, precision, recall, ROC-AUC, and confusion matrices.
- Hyperparameter tuning for optimal model performance.

## Installation
1. Clone this repository to your local machine using `git clone`.
2. Install the required libraries listed in `requirements.txt` using `pip install -r requirements.txt`.

## Usage
1. Open and run the Jupyter Notebook `German_Credit_Risk_Analysis.ipynb` to reproduce the analysis.
2. Customize the models, hyperparameters, or data preprocessing steps as needed for your specific use case.

## Data Source
The dataset used in this project is the "german_credit.csv" dataset, which provides information on credit applicants' characteristics and risk profiles.

## Data Preprocessing
- Handling missing values in 'Saving_account' and 'Checking_account' columns.
- Replacing job code 0 with the mode of the 'job' column.
- Outlier treatment for 'age,' 'Credit_amount,' and 'duration' columns.

## Machine Learning Models
- Logistic Regression
- Linear Discriminant Analysis (LDA)
- K-Nearest Neighbors (KNN)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- ROC-AUC
- Confusion matrices

## Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to enhance this project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

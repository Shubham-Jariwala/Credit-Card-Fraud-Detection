# Credit Card Fraud Detection using Gaussian Mixture Models

This project demonstrates the use of Gaussian Mixture Models (GMM) for detecting fraudulent credit card transactions. 

## Project Overview

The project utilizes a credit card transaction dataset and employs a GMM-based approach to identify anomalies indicative of fraudulent activities. This approach involves:

1. **Data Loading and Exploration:** The project begins by loading the credit card transaction dataset and performing exploratory data analysis to understand its structure and characteristics.
2. **Feature Selection:** Key features relevant to fraud detection, such as 'V14' and 'V17', are selected for modeling.
3. **Data Splitting:** The dataset is split into training and testing sets to evaluate the model's performance.
4. **GMM Training:** A Gaussian Mixture Model is trained on the normal (non-fraudulent) transactions to learn the distribution of genuine transactions.
5. **Threshold Determination:** An optimal threshold is determined based on the log-likelihood scores of the transactions, aiming to balance precision and recall for fraud detection.
6. **Fraud Detection:** New transactions are classified as fraudulent or non-fraudulent based on their log-likelihood scores relative to the chosen threshold.
7. **Model Evaluation:** The performance of the model is evaluated using metrics such as precision, recall, and F1-score.

## Requirements

To run this project, you will need the following libraries:

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

You can install these libraries using `pip`:

<br> pip install numpy pandas matplotlib seaborn scikit-learn <br>

## Usage

1. Clone this repository.
2. Open the Jupyter Notebook `credit_card_fraud_detection.ipynb`.
3. Run the cells in the notebook sequentially.

## Results

The project demonstrates the effectiveness of GMMs in detecting fraudulent credit card transactions. The evaluation metrics show promising results in terms of precision, recall, and F1-score.

## Future Work

Potential improvements and extensions for this project include:

- Exploring different feature sets and engineering new features.
- Optimizing the GMM parameters and threshold selection.
- Comparing GMM performance with other anomaly detection techniques.
- Deploying the model for real-time fraud detection.

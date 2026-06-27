# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The aim is to build a classification model that can identify suspicious transactions and help reduce financial risk.

## Project Overview

Credit card fraud detection is a common real-world problem in data science because fraudulent transactions are usually rare compared to genuine transactions. This creates an imbalanced classification problem, where accuracy alone is not enough to judge model performance.

In this project, I explored transaction data, preprocessed the dataset, trained machine learning models, and evaluated their performance using suitable classification metrics.

## Objectives

* Understand the structure of credit card transaction data
* Identify patterns between genuine and fraudulent transactions
* Handle class imbalance in the dataset
* Train machine learning models for fraud detection
* Evaluate models using appropriate metrics such as precision, recall, F1-score, confusion matrix, and ROC-AUC

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Workflow

1. Data Loading
   Imported the dataset and reviewed its structure, features, and target variable.

2. Exploratory Data Analysis
   Analyzed transaction patterns, class distribution, and feature relationships.

3. Data Preprocessing
   Cleaned the data, handled missing values if present, and prepared features for model training.

4. Model Building
   Trained machine learning models to classify transactions as fraudulent or genuine.

5. Model Evaluation
   Evaluated model performance using classification metrics suitable for imbalanced datasets.

## Key Learning

Through this project, I learned how to approach an imbalanced classification problem and why metrics like recall, precision, F1-score, and confusion matrix are more meaningful than accuracy for fraud detection tasks.

## Repository Structure

```text
credit-card-fraud-detection/
│
├── CREDIT_CARD_FRAUD_DETECTION.ipynb   # Main Jupyter Notebook
├── README.md                           # Project documentation
```

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/qudsiasamarb/credit-card-fraud-detection.git
```

2. Open the project folder:

```bash
cd credit-card-fraud-detection
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook CREDIT_CARD_FRAUD_DETECTION.ipynb
```

4. Run the notebook cells step by step.

## Results

The model was evaluated using classification metrics that are suitable for fraud detection. Since fraudulent transactions are rare, the focus was placed on identifying fraud cases effectively rather than only maximizing accuracy.

## Future Improvements

* Try additional machine learning models
* Apply advanced imbalance-handling techniques
* Tune hyperparameters for better performance
* Deploy the model as a simple fraud detection web application
* Add visual dashboards for transaction monitoring

## Author

**Qudsia Samar**
MSc Data and Computational Science
University College Dublin
GitHub: [qudsiasamarb](https://github.com/qudsiasamarb)

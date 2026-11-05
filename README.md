
# Bank Marketing Campaign Prediction

## Project Overview
This project uses Machine Learning to predict whether a customer will subscribe to a bank term deposit after being contacted through a marketing campaign.

The objective is to help banks understand customer behavior and identify potential customers who are more likely to subscribe.

## Problem Statement
Bank marketing campaigns involve contacting a large number of customers. Predicting customer responses can help banks improve their marketing strategies and make better data-driven decisions.

This project aims to classify whether a customer will subscribe to a term deposit (Yes/No).

## Dataset
- Dataset: Bank Marketing Dataset
- File: `bank-additional-full.csv`
- Contains customer, financial and marketing campaign-related information.
- Target variable: `y` (Yes/No subscription).

## Technologies Used
- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

*Keep only the libraries actually used in your notebook.*

## Project Workflow
1. Data Loading
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Model Building
5. Model Evaluation
6. Customer Subscription Prediction

## Machine Learning Models
Two approaches were explored:

- Linear Regression: Initially tested, but produced less suitable results for the classification task.
- Random Forest Classifier: Used for predicting whether a customer would subscribe to a term deposit.

## Results
The Random Forest Classifier achieved approximately **88% accuracy** in the project.

## Repository Structure

```text
Bank-Marketing-Campaign-Prediction/
│
├── bank.ipynb
├── bank-additional-full.csv
└── README.md
```

## How to Run
1. Clone this repository.
2. Install the required Python libraries.
3. Open `bank.ipynb` using Jupyter Notebook.
4. Run the notebook cells to explore the analysis and predictions.

## Future Improvements
- Experiment with additional classification algorithms.
- Improve model performance through hyperparameter tuning.
- Evaluate precision, recall and F1-score.
- Develop a simple interface for making customer subscription predictions.

---

**Author:** Dwarika Agarwal

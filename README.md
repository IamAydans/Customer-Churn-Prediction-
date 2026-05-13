# Customer Churn Analysis and Prediction in the Telecommunications Sector Using Machine Learning

## Project Overview

This project investigates customer churn behaviour in the telecommunications sector using machine learning techniques. The analysis aims to identify the key factors associated with customer churn and evaluate multiple predictive models to support customer retention strategies.

The project combines exploratory data analysis (EDA), data preprocessing, feature engineering, machine learning model development, and business interpretation to generate actionable insights for churn reduction.

---

## Business Problem

Customer churn is a major challenge in the telecommunications industry because losing customers directly affects profitability and long-term business sustainability. Retaining existing customers is generally more cost-effective than acquiring new ones.

This project aims to:
- analyse churn behaviour,
- identify important churn drivers,
- predict customer churn using machine learning,
- and provide business recommendations for improving customer retention.

---

## Objectives

- Perform exploratory data analysis to understand customer churn patterns.
- Identify important variables related to customer churn.
- Preprocess and prepare the dataset for modelling.
- Build and compare multiple machine learning models.
- Evaluate model performance using classification metrics.
- Generate business insights and recommendations based on analytical findings.

---

## Dataset

The dataset used in this project is based on the IBM Telco Customer Churn dataset obtained from Kaggle.

Dataset source:
https://www.kaggle.com/datasets/johnflag/jb-link-telco-customer-churn

The dataset contains customer-level information including:
- demographic characteristics,
- service subscriptions,
- contract information,
- billing and payment details,
- customer satisfaction indicators,
- customer service requests,
- churn status.

### Dataset Location

```text
data/raw/telco_churn_data.csv
```

The dataset is included directly in the repository because the file size is below 600 KB and does not contain sensitive information.

---

## Machine Learning Models

The following models were implemented and evaluated:

- Logistic Regression
- Random Forest Classifier
- Tuned Random Forest Classifier
- Gradient Boosting Classifier

---

## Evaluation Metrics

Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## Key Findings

- Gradient Boosting achieved the strongest overall predictive performance.
- Contract type, tenure, monthly charges, and customer satisfaction were among the most influential churn-related variables.
- Customers with shorter contracts and lower satisfaction levels showed higher churn probability.

---

## Repository Structure

```text
customer-churn-prediction-bda/
│
├── README.md
├── LICENSE
├── requirements.txt
│
├── data/
│   └── raw/
│       └── telco_churn_data.csv
│
├── notebooks/
│   └── customer_churn_prediction.ipynb
│
├── outputs/
│   └── figures/
```

---

## How to Reproduce the Project

### 1. Clone the Repository

```bash
git clone <repository-link>
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the Notebook

Open:

```text
notebooks/customer_churn_prediction.ipynb
```

### 4. Run the Notebook

Run all notebook cells sequentially from top to bottom.

---

## Dependencies

Main Python libraries used:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

All dependencies are listed in:

```text
requirements.txt
```

---

## Business Insights

The analysis suggests that customer retention strategies should focus on:
- improving customer satisfaction,
- reducing dissatisfaction during early subscription stages,
- encouraging long-term contracts,
- improving support service quality,
- identifying high-risk customers proactively.

These insights can support customer retention decision-making and reduce churn-related revenue loss.

---

## Limitations

- The dataset represents a specific telecommunications scenario and may not generalise to all markets.
- Model performance may vary on real-world production data.
- External behavioural and competitive market factors were not included in the dataset.

---

## AI Usage Disclosure

AI tools were used to support coding assistance, debugging, repository structuring, and documentation improvement.

All analytical decisions, interpretation of findings, and final project validation were reviewed and verified independently.

AI-generated support was used in accordance with the Business Data Analytics Project handbook requirements.

---

## Author
Aydan Sadigova
MSc in IT for Business Data Analytics  
International Business School / The University of Buckingham

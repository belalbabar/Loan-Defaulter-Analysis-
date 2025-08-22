Loan Default Analysis using Python 🐍

## Project Overview

This project analyzes a customer dataset to understand factors affecting loan defaults. The main goal is to identify patterns in customer behavior and assess the risk of loan default using **binary classification** techniques.


## Dataset

The dataset contains customer information with the following key features:

| Feature         | Description                                |
| --------------- | ------------------------------------------ |
| Income          | Customer's annual income                   |
| Age             | Age of the customer                        |
| Experience      | Professional experience in years           |
| Marital Status  | Single or Married                          |
| House Ownership | Rented, Owned, or None                     |
| Car Ownership   | Owns a car or not                          |
| Job Details     | Years in current job, profession           |
| City            | City of residence                          |
| State           | State of residence                         |
| Risk Flag       | Binary target: 0 = No default, 1 = Default |

---

## Exploratory Data Analysis (EDA)

* Performed **data cleaning and preprocessing**, converting categorical features to numeric where needed.
* Visualized distributions of features like **Income, Age, Marital Status, House Ownership, Car Ownership**.
* Observed **imbalanced target distribution** (`Risk Flag`), with more non-default cases.

**Plots included:**

* Feature importance from tree-based models
* Marital Status distribution
* House Ownership distribution

---

## Modeling Approach

1. **Logistic Regression**

   * Used to handle **binary target** and imbalanced classes.
   * Provides baseline for predicting risk of default.

2. **Random Forest Classifier**

   * Evaluates **feature importance** to identify which attributes influence default risk the most.
   * Achieved **ROC-AUC score: 0.76**.

> Both models were trained using Python libraries like **Pandas, NumPy, Seaborn, Matplotlib, and scikit-learn**.

---

## Key Insights

* Income, marital status, and house ownership have visible patterns related to loan default.
* Random Forest model highlighted the most influential features affecting risk.
* Binary target imbalance should be carefully handled in predictive modeling.

---

## Skills Gained

* Data preprocessing and handling categorical features
* Mini exploratory data analysis for binary targets
* Visualization of feature distributions
* Binary classification using Logistic Regression and Random Forest
* Evaluation using confusion matrix, classification report, and ROC-AUC

---

## Usage

1. Clone the repository
2. Load the dataset into a Pandas DataFrame
3. Run preprocessing scripts to clean and encode features
4. Execute the EDA and modeling scripts
5. Visualize the results and feature importance plots




Do you want me to do that?

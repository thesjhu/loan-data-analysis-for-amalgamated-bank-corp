## 🏦 Credit Risk Analysis and Loan Default Prediction

This repository contains a comprehensive data analysis and machine learning project focused on credit risk assessment for Amalgamated Bank Corp (ABC). The goal is to transform raw loan data into actionable intelligence, providing management with a clear demographic profile of their clients and a predictive model to forecast loan default risk.

The entire analysis workflow is encapsulated in the primary Jupyter Notebook: **`task-final.ipynb`**.

-----

### ✨ Project Highlights & Deliverables

This analysis was executed to address key business questions from ABC management, dealing with a dataset of over **300,000 loans**.

| Phase | Description | Key Deliverables |
| :--- | :--- | :--- |
| **Data Preparation** | Thorough cleansing, imputation of null values, and application of robust outlier detection methods to ensure data quality. | Documented null handling and outlier removal strategies. |
| **Exploratory Data Analysis (EDA)** | Detailed macro-level analysis of the loan portfolio and client base. | High-level summary charts for senior management on total loan exposure, default rates (amount and percentage), and key customer demographics (e.g., employment type, age, income). |
| **Default Analysis** | Focused visualization to identify characteristic qualities of clients who are in default or late on repayments. | Three meaningful visualizations highlighting differences between defaulting and non-defaulting groups. |
| **Predictive Modeling** | Implementation of a **Logistic Regression** model to calculate the probability of a client defaulting on a loan. | Predictive model results, scoring metrics, and a Confusion Matrix. |

-----

### 💻 Getting Started

This project is built using standard Python data science libraries.

#### Prerequisites

To run the notebook, you must have the following libraries installed:

  * `numpy`
  * `pandas`
  * `matplotlib`
  * `seaborn`
  * `scikit-learn` (`sklearn`)

You can install them using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

#### Running the Analysis

1.  **Data File:** Ensure the primary dataset file, **`application_train.csv`**, is present in the same directory as the notebook. (The notebook is configured to read this file).
2.  **Execute:** Open the main file, `task-final.ipynb`, in a Jupyter environment and run all cells sequentially.

-----

### 📌 Main File

| File Name | Description |
| :--- | :--- |
| **`task-final.ipynb`** | The core analysis notebook containing all data cleaning, EDA, visualization, feature engineering, Logistic Regression model training, and evaluation. |

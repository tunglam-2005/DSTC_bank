# DSTC_bank

## Overview

This project includes data preprocessing, EDA, and modelling tasks on a dataset related to credit data. The data comprises 20,000 entries with 124 features, primarily focusing on credit-related metrics such as loan and credit card enquiries, outstanding balances, and other financial indicators. The project goes through essential steps like loading the dataset, performing exploratory data analysis (EDA), and building machine learning models.

## Structure

### 1. Data Loading and Inspection
- **Data Overview:** The dataset is loaded and basic summary statistics are calculated, including column types and missing values.
- **Head of Data:** Displays the first 10 rows of the dataset for a quick look at the structure.
- **Shape:** Confirms the size of the dataset (20,000 rows and 124 columns).

### 2. Data Preprocessing
- **Missing Data Handling:** Procedures for missing values.
- **Normalization:** Transform the data so there aren't outliers.
- **Reducing dimensions:** Reduce the number of columns so the predictive model can be more accurate and cost less computation power.

### 3. Exploratory Data Analysis (EDA)
- **Statistical Summaries:** Calculate summary statistics for important features.
- **Data Visualization:** Visual exploration of patterns in the data.

### 4. Modelling
- **Model Selection:** Details on the machine learning algorithms used.
- **Model Training:** Fitting the model to the processed dataset.
- **Model Evaluation:** Performance metrics like accuracy, precision, and recall.

## Dependencies

To run this notebook, you need the following libraries installed:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `tensorflow` (for deep learning model)

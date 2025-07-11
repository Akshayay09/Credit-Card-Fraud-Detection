# Credit-Card-Fraud-Detection

### Project Overview
  This project focuses on detecting fraudulent credit card transactions using data analysis and machine learning techniques in Python. Implemented in Jupyter Notebook, it leverages libraries like Pandas, NumPy, Matplotlib, and Seaborn to preprocess, analyze, and visualize a credit card transaction dataset. The goal is to identify patterns of fraudulent behavior while addressing challenges like class imbalance and outliers.

### Features
- Data Preprocessing: Cleaned the dataset by handling missing values, removing outliers (e.g., transactions with amounts above a threshold), and standardizing features.
- Exploratory Data Analysis (EDA): Performed filtering, grouping, sorting, and aggregation to uncover insights, such as the distribution of fraudulent vs. non-fraudulent transactions.
- Visualizations: Created bar plots, box plots, and violin plots to visualize transaction amounts by class, highlighting class imbalance and density variations.
- Machine Learning: Applied classification models to predict fraudulent transactions, with a focus on handling imbalanced data.

### Key Libraries: 
  Utilized Pandas for data manipulation, NumPy for numerical operations, Matplotlib and Seaborn for visualization, and Scikit-learn for modeling.

### Dataset
  The dataset contains anonymized credit card transactions with features like transaction amount and class (0 for non-fraudulent, 1 for fraudulent). Preprocessing steps included filtering fraudulent transactions (Class=1) and analyzing high-value transactions.

### Requirements
  - Python 3.x
  - Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
  - Jupyter Notebook

### Key Insights
- Fraudulent transactions (Class=1) are significantly fewer, indicating a class imbalance that requires careful handling.
- Violin plots revealed distinct amount distributions for fraudulent vs. non-fraudulent transactions.
- Preprocessing, such as outlier removal, improved model performance and visualization clarity.

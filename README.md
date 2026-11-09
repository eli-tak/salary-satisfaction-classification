# Salary Satisfaction Classification

A machine learning project that uses job-posting information to classify whether a salary estimate is **below** or **at/above** the median training salary. It compares four classifiers: Logistic Regression, K-Nearest Neighbors, Decision Tree, and Random Forest.

## Dataset

`df.csv` contains job postings with fields such as job title, salary estimate, rating, company, location, company size, industry, sector, and revenue.

## Project Workflow

1. Load and inspect the data
2. Clean salary estimates (parse ranges, handle missing `-1` values and hourly pay)
3. Exploratory data analysis
4. Feature engineering and a train/test split (30% test), with the median threshold learned from training data only to avoid data leakage
5. Train and evaluate the four models using confusion matrices, classification reports, and accuracy
6. Compare model accuracy

## Installation
```bash
pip install -r requirements.txt

# titanic_dataset_kaggle

Titanic Dataset - Data Cleaning & Preprocessing

This project demonstrates how to clean and prepare the Titanic dataset for machine learning models.

Steps Performed

Data Exploration: Viewed data types, missing values, and basic statistics.
Missing Value Handling:
Numeric: Filled missing values with the median.
Categorical: Filled with mode or dropped columns with excessive missing data.
Encoding:
Label Encoding for Sex.
One-hot encoding for Embarked.

Feature Scaling:
Outlier Detection & Removal:
Visualized with boxplots.
Removed using IQR method.

Export:
Saved the final cleaned dataset to cleaned_titanic.csv.
Files

preprocessing_titanic.ipynb: Code for preprocessing.
cleaned_titanic.csv: Final cleaned dataset.
titanic.csv: Original dataset.
screenshots: Contains visualizations.
Tools Used

Python
Pandas,
NumPy,
Seaborn,
Matplotlib,
Scikit-learn

What I Learned

Handling missing data (MCAR, MAR, MNAR)
Label vs one-hot encoding
Normalization vs Standardization
Outlier detection using boxplots and IQR
Importance of preprocessing in ML

# DATA-CLEANING
Titanic Dataset - Data Cleaning & Preprocessing

This project is part of an AI/ML internship task focused on data preprocessing. The goal is to clean,encode, normalize, and handle outliers in the Titanic dataset to make it ready for machine learning.

Steps Performed
1. Loaded the dataset using Pandas.
2. Handled missing values:

o Filled missing Age with mean.

o Filled missing Embarked with mode.

o Dropped Cabin due to many missing values.

3. Converted categorical variables:

o Applied one-hot encoding to Sex and Embarked.

4. Normalized numerical features:

o Used StandardScaler on Age and Fare.

5. Detected and removed outliers:

o Used boxplots to visualize outliers.

o Applied IQR method to remove them.

Technologies Used

• Python

• Pandas

• NumPy

• Seaborn

• Matplotlib

• Scikit-learn

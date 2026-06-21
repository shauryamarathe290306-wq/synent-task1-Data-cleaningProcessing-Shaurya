# synent-task1-Data-cleaning-Processing
# Titanic Dataset Data Cleaning

Problem Statement

Real-world datasets often contain missing values, inconsistent data types, duplicate records, and unnecessary columns. These issues can affect data analysis and machine learning performance.

The objective of this project is to clean the Titanic dataset by identifying and handling missing values, converting data types, renaming columns for better readability, removing unnecessary columns, and preparing the dataset for further analysis.

---

Dataset Details

Dataset Name: Titanic Dataset

Source: Kaggle Titanic - Machine Learning from Disaster

File Used: train.csv

Description:
The dataset contains information about passengers aboard the RMS Titanic, including demographic details and survival status.

### Key Features

- PassengerId – Unique passenger identifier
- Survived – Survival status (0 = No, 1 = Yes)
- Pclass – Passenger class
- Name – Passenger name
- Sex – Gender
- Age – Age of passenger
- SibSp – Number of siblings/spouses aboard
- Parch – Number of parents/children aboard
- Ticket – Ticket number
- Fare – Passenger fare
- Cabin – Cabin number
- Embarked – Port of embarkation

---

Approach

The following data cleaning steps were performed:

1. Imported the Pandas library.
2. Loaded the Titanic dataset.
3. Examined the dataset structure using `.info()`.
4. Identified missing values using `.isnull().sum()`.
5. Converted appropriate columns to correct data types.
6. Renamed selected columns for better readability.
7. Filled missing values in the Age column using the median value.
8. Filled missing values in the Embarked column using the mode value.
9. Removed the Cabin column due to a large number of missing values.
10. Removed duplicate records.
11. Verified that missing values were handled successfully.
12. Saved the cleaned dataset as `cleaned_titanic.csv`.

---

## Result

After performing data cleaning:

- Missing values were successfully handled.
- Data types were standardized.
- Column names became more readable.
- Unnecessary columns were removed.
- Duplicate records were eliminated.
- A clean dataset was generated and saved as `cleaned_titanic.csv`.

The cleaned dataset is now ready for exploratory data analysis (EDA), visualization, and machine learning tasks.

---

## Technologies Used

- Python
- Pandas
- Google Colab / Jupyter Notebook

---

## Output

*Generated File*

`cleaned_titanic.csv`

This file contains the cleaned version of the Titanic dataset and can be used for further data science and machine learning applications.

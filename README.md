# PRODIGY_DS_01-TASK_02
![image](https://github.com/AakashShaji/PRODIGY_DS_02-TASK_02/assets/121721309/aaa4b2e2-6b79-46c8-84b7-e9bde1e2898f)

## Introduction
This notebook is a part of a data analysis project aimed at examining survival rates based on different factors. It leverages Python's data analysis libraries, such as pandas and matplotlib, to manipulate data and visualize results. The primary dataset analyzed appears to be related to passenger survival, likely from a historic dataset such as the Titanic passenger data, although the exact dataset isn't explicitly mentioned in the provided content.

## Dataset
Download dataset from https://www.kaggle.com/c/titanic/data

dataset- [Titanic-Dataset.csv](Titanic-Dataset.csv).

The predefined columns are -

Passenger ID - To identify unique passengers

Survived - If they survived or not

P Class - The class passengers travelled in

pclass: A proxy for socio-economic status (SES) 1st = Upper 2nd = Middle 3rd = Lower

Name - Passenger Name

Sex - Gender of Passenger

Age - Age of passenger

Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

SibSp - Number of siblings or spouse

Parch - Parent or child

Ticket - Ticket number

Fare - Amount paid for the ticket

Cabin - Cabin of residence

Embarked - Point of embarkmen

## Task Description
The task involves performing data analysis to uncover insights into survival rates based on various demographic and personal characteristics of individuals. Specific objectives include:

* Loading and exploring the dataset to understand its structure and contents.
* Cleaning and preprocessing the data to handle missing values and create new relevant features.
* Visualizing the survival rates across different age categories to identify trends and patterns.
* Summarizing the findings and providing actionable insights or conclusions based on the analysis.

## Analysis Highlights
### 1)Data Loading and Cleaning:

The dataset is loaded using pandas, and initial exploration is done to understand the distribution and nature of data.
Missing values are handled appropriately to ensure accurate analysis.

### 2)Feature Engineering:

New features such as Age_categories are created by binning the Age column into distinct categories like 'Infant', 'Child', 'Teenager', 'Young Adult', 'Adult', and 'Senior'.
This categorization helps in analyzing survival rates across different age groups.

### 3)Data Visualization:

A bar chart is plotted to visualize the survival rates across the defined age categories.
Different colors are used for each bar to enhance readability and distinction between categories.
A legend is added to the chart to clearly indicate which color corresponds to which age category.

### 4)Pivot Table:

A pivot table is created to summarize the survival rates for each age category, providing a clear tabular representation of the data.

## Conclusion
The analysis provides valuable insights into survival rates across different age categories. By visualizing the data, it's possible to identify which age groups had higher or lower survival rates. This can be particularly useful for historical analysis or for designing better safety protocols in current contexts. The notebook successfully demonstrates the process of data cleaning, feature engineering, and visualization to derive meaningful conclusions from a dataset.

Thank you for reviewing my submission!

📬 Contact For any inquiries or feedback regarding this project, please contact:

* www.linkedin.com/in/aakashshaji (LinkedIn)
* Email: aakashshaji03@gmail.com

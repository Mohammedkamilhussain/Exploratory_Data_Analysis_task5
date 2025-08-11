# Exploratory_Data_Analysis_task5
Using Pandas, Matplotlib, and Seaborn, an exploratory data analysis (EDA) was conducted on the Titanic dataset. includes correlation heatmaps, univariate, bivariate, and multivariate analysis, data cleaning, and important survival pattern insights.

Exploratory Data Analysis – Titanic Dataset
 Description:
This project is included in Task 5 of the Data Analytics Internship. The project involves the process of Exploratory Data Analysis (EDA) for the Titanic dataset. It aims to find out patterns related to survival, and the correlation between features using Python, Pandas, Matplotlib, and Seaborn.


 Dataset:
The dataset provides information about passengers, such as:

->PassengerId
->Name
->Sex
->Age
->Pclass (Passenger class)
->Fare
->Embarked
->Survived (The target)


Tools & Libraries:
->Python 3.x
->Pandas
->Matplotlib
->Seaborn
->Jupyter Notebook


 EDA will consist of:
->Data loading and inspection:
->Checked the structure of the dataset, data types, and missing values.


Data cleaning:
->Fill missing Age values with median.
->Fill missing Embarked values with mode (most common).


Univariate analysis:
->Histograms for numeric features.
->Countplots for categorical features like gender and survived.


Bivariate analysis:
->Survival rate by gender and passenger class.
->Boxplots to compare fare distributions.


Multivariate analysis:
->Pair-plots for the key numeric features.
->Correlation heat map for the numeric columns.


Significant Findings:
->Female passengers had a better survival rate relative to males.
->Passengers in higher classes (first class) paid for more and had higher odds of survival.
->Younger passengers had a slightly better chance of survival.


Files in the Repository:
-task5_eda.ipynb → Jupyter Notebook with full analysis and visualizations.
-task5_eda.pdf → PDF export of notebook.

# EDULUMOS-INTERSHIP-TASKS
1. Titanic Dataset – Exploratory Data Analysis (EDA)

This project explores the Titanic dataset to uncover meaningful insights using data cleaning, exploratory visualizations, and foundational statistical analysis.
The goal is to understand key factors influencing passenger survival and to practice essential data analysis skills.

📌 Project Objectives

Clean and preprocess the Titanic dataset

Handle missing values (Age, Cabin, Embarked, etc.)

Explore feature relationships

Visualize data distributions

Identify survival patterns across different groups

Perform foundational statistical analysis

Generate meaningful insights from the data

🧰 Skills & Tools Used
🔹 Programming

Python

Jupyter Notebook

🔹 Libraries

Pandas – data cleaning & manipulation

NumPy – numerical computing

Matplotlib & Seaborn – visualizations

Scipy – basic statistical analysis

📂 Dataset

The Titanic dataset used in this project contains the following key columns:

Column	Description
Survived	0 = No, 1 = Yes
Pclass	Passenger class (1,2,3)
Sex	Gender
Age	Age in years
SibSp	Siblings/spouses aboard
Parch	Parents/children aboard
Fare	Ticket price
Embarked	Port of embarkation
🧹 Data Cleaning Steps

Handling missing values (Age, Embarked)

Dropping unusable fields (Cabin, Ticket)

Creating new features:

family_size = SibSp + Parch + 1

is_alone = 1 if family_size == 1 else 0

Encoding categorical variables

Fixing data types

📊 Visualizations Included
✔ Histograms

Age distribution

Fare distribution

Family size

✔ Bar Charts

Survival by Gender

Survival by Passenger Class

Embarked vs Survival

✔ Heatmaps

Correlation between numerical features

✔ Pie Charts

Gender distribution

Survival rate

✔ Boxplots

Age vs Survival

Fare vs Survived/Not Survived

📈 Statistical Analysis Performed

Mean, median, mode of key variables

Survival rate by groups

Correlation analysis

T-tests and chi-square checks (optional)

Probability distributions

🧠 Key Insights

Women had a significantly higher survival rate

1st class passengers survived more than 3rd class

Younger passengers (children) had better chances

High fare = higher survival probability

Being alone reduced survival chances

Strong correlation between Sex, Pclass & Survival

🏁 Conclusion

This analysis reveals that survival on the Titanic was strongly influenced by social and demographic factors such as gender, class, fare, and family size.
Women and children were prioritized, and wealthy passengers had better access to safety.

This project demonstrates essential data analysis skills including cleaning, visualization, and statistical reasoning.

Employee Attrition Analysis – Green Destinations
Project Overview

Green Destinations is a popular travel agency. Recently, the HR Director noticed that more employees are leaving the company than before. To understand the situation better, we collected employee data and analyzed it for trends and patterns.

This project is about answering two main questions:

How many employees are leaving (attrition rate)?

Are factors like age, years at the company, and income connected to attrition?

The goal is to give the HR team useful insights so they can improve employee retention.

Dataset

The dataset includes information about employees such as:

Attrition → Whether the employee left or stayed (Yes or No).

Age → Age of the employee.

YearsAtCompany → How many years the employee has worked at Green Destinations.

MonthlyIncome → Monthly salary of the employee.

Note: Column names in your dataset may vary. Please double-check and update them in the code if needed.

Setup Instructions

Clone or download this project to your computer.

Install the required Python libraries:

pip install pandas matplotlib seaborn


Place your dataset in the project folder. Example file name:

greendestination.csv


Run the script to see the analysis:

python analysis.py

Visualizations

The script generates the following visualizations:

Attrition Rate → Pie chart showing the percentage of employees who left versus those who stayed.

Attrition vs Age → Boxplot showing if younger or older employees are more likely to leave.

Attrition vs Years at Company → Histogram showing if employees with fewer years at the company leave more often.

Attrition vs Monthly Income → Boxplot showing if salary has an effect on attrition.

Correlation Heatmap → Heatmap showing relationships between numerical features.

Example Code Snippet
sns.boxplot(x='Attrition', y='Age', data=df, palette='Set2')
plt.title("Attrition by Age")
plt.show()

Insights to Look For

The overall attrition percentage.

Whether younger employees are leaving more often.

If salary is linked with attrition.

How years of service affect employee turnover.

Deliverables

A Python script that performs the analysis and creates visualizations.

Graphs that provide a clear picture of attrition trends.

This README file to guide you through the project.

Would you like me to also turn this into a PDF project report with proper sections (Objective, Methodology, Analysis, Results, and Conclusion)? That way you can directly submit it as part of your work.

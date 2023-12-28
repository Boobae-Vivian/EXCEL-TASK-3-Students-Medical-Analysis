# STUDENTS MEDICAL ANALYSIS

## INTRODUCTION

This Excel task involves analyzing the health data of students, utilizing a substantial dataset comprising 192,356 rows and 13 columns of information. The objective is to uncover valuable insights by creating Pivot Tables that emphasize key indicators such as age, BMI, temperature, heart rate, blood pressure, cholesterol, height, weight, blood groups, smoking habits, and diabetes status. Through these tables, we aim to calculate average values, identify gender-based health patterns, and explore the distribution of various health-related attributes. Join us in exploring and interpreting the data to gain a deeper understanding of the diverse health characteristics within the student population.

## PROBLEM STATEMENT

The task involves leveraging the 'Students Medical Dataset' to derive valuable insights through the creation of Pivot Tables. Specifically, we aim to address the following analytical objectives:

1. Average Age, BMI, Temperature, Heart Rate, Blood Pressure, and Cholesterol, segregated by gender (Male and Female).
2. Average height and weight for both Male and Female students, rounded to two decimal places.
3. The number of students across different blood groups
4. The number of students who smoke and those who do not
5. The number of students with diabetes and those without
6. Create visual representations, such as charts or graphs, for each objective to effectively communicate the insights derived from the Pivot Tables.

These visualization will enhance the interpretability of the data and facilitate a deeper understanding of health patterns among the students.

## SKILLS AND CONCEPTS DEMOSTRATED
- Pivot table proficiency
- Data aggregation
- Data Visualization
- Data interpretation

## ANALYSIS, RESULTS AND DISCUSSION

### 1. Average Age, BMI, Temperature, Heart Rate, Blood Pressure, and Cholesterol, segregated by gender (Male and Female)

To compute the average age, BMI, temperature, heart rate, blood groups, and cholesterol for both genders, the following steps are involved: Start by creating a pivot table. Select all the data, navigate to the "Insert" tab on the Excel ribbon, click on "Pivot Table," and choose the table range, often auto-selected. Next, select the pivot table destination, either a new worksheet or an existing one, and click "OK." Once the pivot table is created, a field list will appear alongside it, containing four different fields.

Now, drag the columns for age, BMI, temperature, heart rate, blood pressure, and cholesterol into the "Values" field for aggregation. Simultaneously, place the gender column into the "Row" field for categorization. By default, the pivot table aggregates values as a sum. However, since we seek average values, modify this by selecting each header, right-clicking, and opting to summarize values by average. This action will run the analysis, providing the average values for each specified column, categorized by gender.

PIVOT TABLE                       |VISUALIZATION
:--------------------------------:|:------------------------------:
![](Average_BATHBC.png)           |![](Visual_BATHBC.png)

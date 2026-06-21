Research: Student Academic Performance Dataset

Title & Collection Method

Title: Student Academic Performance Dataset

Collection Method:
A survey was conducted among 50 students from different educational levels. Each student provided information about their age, number of courses taken, study hours, attendance rate, and assignment scores. The data was collected manually through questionnaires and academic records.

Description of Features & Label
Features (X)
Age – Numeric (years)
Courses – Numeric (number of courses taken)
Hours – Numeric (study hours)
Attendance – Numeric (attendance percentage)
Assignment Score – Numeric (score out of 100)

Label (y)
Pass_Fail – Categorical (Pass / Fail)

This makes the problem a classification task, where the goal is to predict whether a student will pass or fail based on academic factors.

Dataset Structure

Rows (Samples): 50 students
Columns: 6 (5 features + 1 label)
Sample Table (10 Rows)

| Age | Courses | Hours | Attendance | Assignment Score | Pass_Fail |
| --- | ------- | ----- | ---------- | ---------------- | --------- |
| 18  | 2       | 40    | 65         | 55               | Fail      |
| 19  | 3       | 60    | 75         | 68               | Pass      |
| 20  | 4       | 80    | 85         | 72               | Pass      |
| 21  | 1       | 30    | 50         | 45               | Fail      |
| 22  | 5       | 100   | 90         | 88               | Pass      |
| 18  | 2       | 45    | 60         | 50               | Fail      |
| 19  | 3       | 70    | 80         | 75               | Pass      |
| 20  | 4       | 90    | 92         | 85               | Pass      |
| 21  | 1       | 25    | 55         | 40               | Fail      |
| 22  | 5       | 110   | 95         | 90               | Pass      |


Data Quality Issues
Small dataset size (50 records), which may limit model performance.
Some values may be self-reported and not fully accurate.
Limited number of features affecting student performance.
Dataset may not represent all student populations.
Use Case

This dataset can be used to train a classification model that predicts whether a student will pass or fail.

Possible Algorithms:

Logistic Regression
Decision Tree
Random Forest
K-Nearest Neighbors (KNN)
Naive Bayes

Potential Applications:

Identify students at risk of failing.
Improve academic support programs.
Help teachers monitor student progress.
Support educational decision-making through data analysis.

Problem Type: Classification
Target Variable: Pass_Fail
Dataset Size: 50 Students × 6 Variables
# MIS 311 - Student Exam Performance Analysis

## Project Overview

This project is my individual assignment for MIS 311 - Introduction to Business Analytics. I used Microsoft Excel to perform Exploratory Data Analysis on a student exam performance dataset.

The purpose of this project is to understand which factors may affect students' final exam results. The analysis focuses on study habits, attendance, internet access, parental education, and academic performance.

The main questions of this project are:

1. Do students with higher study hours achieve better final exam scores?
2. Do students who pass have higher attendance rates than students who fail?
3. Does internet access or parental education strongly affect final exam performance?

---

## Dataset Overview

The dataset contains information about students' demographic background, study habits, academic behaviour, subject scores, and final exam results.

The dataset includes:

- **10,000 rows**
- **23 columns**

Some key variables include:

- student_id
- gender
- age
- parental_education
- family_income
- internet_access
- study_environment
- study_hours_per_day
- attendance_rate
- sleep_hours
- social_media_hours
- assignment_completion_rate
- participation_score
- online_courses_completed
- tutoring
- math_score
- reading_score
- writing_score
- science_score
- final_exam_score
- previous_gpa
- pass_fail
- grade_category

The dataset includes both numerical variables and categorical variables. Numerical variables include study hours per day, attendance rate, sleep hours, subject scores, final exam score, and previous GPA. Categorical variables include gender, parental education, family income, internet access, tutoring, pass/fail status, and grade category.

---

## Data Cleaning

Before doing the analysis, I checked the dataset for missing values and duplicate rows.

### Missing Values

No missing values were found in the dataset. Therefore, no replacement or removal was required.

### Duplicate Rows

Duplicate rows were checked using Excel's Remove Duplicates function. No duplicate rows were found.

This means the dataset was already clean and ready for descriptive analysis, PivotTables, and charts.

---

## Descriptive Statistics

Descriptive statistics were used to summarize the main numerical variables, including study hours per day, attendance rate, sleep hours, social media hours, assignment completion rate, subject scores, final exam score, and previous GPA.

Some important results include:

| Variable | Average | Minimum | Maximum | Standard Deviation |
|---|---:|---:|---:|---:|
| study_hours_per_day | 3.0 | 0.5 | 7.2 | 1.2 |
| attendance_rate | 84.7 | 50.8 | 100.0 | 9.5 |
| sleep_hours | 7.0 | 4.0 | 10.0 | 1.0 |
| social_media_hours | 2.5 | 0.0 | 8.0 | 1.4 |
| assignment_completion_rate | 79.5 | 40.0 | 100.0 | 13.8 |
| final_exam_score | 49.7 | 4.4 | 97.8 | 12.1 |

The average final exam score was about **49.68**, while the average study time was about **3.02 hours per day**. The average attendance rate was **84.70%**, which shows that students generally had good attendance, but their final exam scores still varied widely.

---

## Key Insights

### Insight 1: Study Hours and Final Exam Score

Students with high study hours achieved an average final exam score of **55.29**, while students with low study hours achieved an average score of **44.10**.

This shows that students who spent more time studying each day tended to perform better in the final exam. Therefore, consistent study habits may have a positive relationship with academic success.

### Insight 2: Attendance and Pass/Fail Result

Students who passed had an average attendance rate of **85.97%**, while students who failed had an average attendance rate of **83.51%**.

This suggests that regular class attendance may support better academic performance. Students who attend classes more often may have more opportunities to understand lessons, ask questions, and prepare for exams.

### Insight 3: Internet Access and Final Exam Score

Students with internet access achieved an average final exam score of **49.77**, while students without internet access achieved an average score of **48.92**.

The difference is small, so internet access may slightly support learning, but it does not appear to be the strongest factor affecting exam performance in this dataset.

---

## Charts

The project includes the following Excel charts:

1. Average Final Exam Score by Internet Access
2. Average Attendance Rate by Pass/Fail Result
3. Average Final Exam Score by Study Hours Group
4. Average Final Exam Score by Parental Education

These charts help visualize the relationship between student behaviour and academic performance.

---

## Main Conclusion

Overall, the analysis shows that student exam performance is more clearly related to **study habits** and **attendance**. Students with higher study hours had much higher final exam scores, and students who passed also had higher attendance rates.

Internet access and parental education showed smaller differences, suggesting that personal academic behaviour may be a stronger factor in student performance than background factors alone.

---

## Tools Used

- Microsoft Excel
- Excel Filters
- Remove Duplicates
- Descriptive Statistics
- PivotTables
- Column Charts

---

## Repository Contents

| File / Folder | Description |
|---|---|
| README.md | Project summary |
| data/ | Student exam performance dataset |
| charts/ | Excel charts used in the analysis |
| report/ | Final assignment report |

---

## Reference

Eastern International University. (2026). *MIS 311 - Introduction to Business Analytics: Assignment #1 Personal Portfolio Site* [Assignment brief].

Le Thi Tuyet Nhung. (2026). *Student Exam Performance dataset for MIS 311 Assignment #1* [Unpublished Excel workbook].

# MIS 311 - Student Exam Performance Analysis

## 1. Project Overview

This project performs Exploratory Data Analysis (EDA) on the Student Exam Performance dataset. The goal is to understand the dataset, clean the data, explore important patterns, and generate insights about factors that affect students’ academic performance.

The analysis focuses on study habits, attendance, internet access, parental education, and final exam scores. These factors are used to understand which variables may be related to students’ academic success.

---

## 2. Dataset Description

The dataset contains information about students’ demographic background, study habits, academic behaviour, subject scores, and final exam results.

The dataset includes the following key variables:

- `student_id`: Unique identifier for each student
- `gender`: Student gender
- `age`: Age of the student
- `parental_education`: Highest education level of parents
- `family_income`: Household income category
- `internet_access`: Whether the student has internet access
- `study_environment`: Quality of study environment
- `study_hours_per_day`: Average daily study time
- `attendance_rate`: Percentage of class attendance
- `sleep_hours`: Average hours of sleep per night
- `social_media_hours`: Average daily time spent on social media
- `assignment_completion_rate`: Percentage of assignments completed
- `participation_score`: Level of student participation in class
- `online_courses_completed`: Number of online courses completed
- `tutoring`: Whether the student receives tutoring support
- `math_score`: Score achieved in mathematics
- `reading_score`: Score achieved in reading
- `writing_score`: Score achieved in writing
- `science_score`: Score achieved in science
- `final_exam_score`: Score achieved in the final exam
- `previous_gpa`: Student’s GPA from previous academic periods
- `pass_fail`: Indicates whether the student passed or failed
- `grade_category`: Classification of overall performance

Dataset size:

- Number of rows: 10,000
- Number of columns: 23

---

## 3. Data Cleaning

The dataset was cleaned before analysis to ensure that the results were accurate and reliable.

The following data cleaning steps were completed:

- Missing values were checked across all columns.
- No missing values were found in the dataset.
- Duplicate rows were checked using Excel’s Remove Duplicates function.
- No duplicate rows were found.
- A new column called `study_group` was created to classify students into two groups:
  - High study hours
  - Low study hours

The `study_group` column was created based on whether a student’s daily study hours were above or below the average study hours per day.

After cleaning, the dataset was ready for descriptive statistics, pivot tables, charts, and insight generation.

---

## 4. Descriptive Statistics

Descriptive statistics were used to summarize the main numerical variables in the dataset.

Key summary statistics:

- Average final exam score: 49.68
- Minimum final exam score: 4.40
- Maximum final exam score: 97.80
- Average study hours per day: 3.02 hours
- Average attendance rate: 84.70%
- Average sleep hours: 7.02 hours
- Average social media hours: 2.52 hours
- Average previous GPA: 1.98

These results show that students generally had a high attendance rate, but their final exam scores varied widely.

---

## 5. Key Insights

### Insight 1: Study Hours and Final Exam Score

Students with high study hours achieved an average final exam score of 55.29, while students with low study hours achieved an average score of 44.10.

This shows that students who spent more time studying each day tended to perform better in the final exam. Therefore, consistent study habits may have a positive relationship with academic success.

### Insight 2: Attendance and Pass/Fail Result

Students who passed had an average attendance rate of 85.97%, while students who failed had an average attendance rate of 83.51%.

This indicates that regular class attendance may be an important factor in academic success. Students who attend classes more often are more likely to understand lessons, participate in learning activities, and perform better in exams.

### Insight 3: Internet Access and Academic Performance

Students with internet access achieved an average final exam score of 49.77, while students without internet access achieved an average score of 48.92.

This suggests that internet access may slightly support students’ learning by allowing them to access online materials and complete academic tasks more easily. However, the difference is small, so internet access alone may not be the strongest factor affecting exam performance.

### Insight 4: Parental Education and Final Exam Score

The average final exam scores were very similar across different parental education levels. Students whose parents had a Bachelor degree achieved an average score of 49.90, while students from High School, Master, and PhD backgrounds had average scores around 49.42 to 49.79.

This suggests that parental education may not be a strong factor in this dataset. Study hours and attendance appear to have a clearer relationship with student performance.

---

## 6. Visualizations

The project includes the following charts:

- Average Final Exam Score by Internet Access
- Average Attendance Rate by Pass/Fail Result
- Average Final Exam Score by Study Hours Group
- Average Final Exam Score by Parental Education

These visualizations help compare student performance across different categories and make the insights easier to understand.

---

## 7. Conclusion

Overall, the analysis shows that student exam performance is strongly related to study habits and attendance. Students with high study hours achieved much higher final exam scores than students with low study hours. Students who passed also had a higher average attendance rate than students who failed.

Internet access and parental education showed smaller differences in average final exam scores. This suggests that personal study behaviour, especially daily study time and regular attendance, may be stronger factors affecting academic performance in this dataset.

---

## 8. References

GitHub Docs. (n.d.). Get started using GitHub. GitHub. 
https://docs.github.com/en/get-started/start-your-journey

MIS 311 dataset. (n.d.). Student Exam Performance dataset provided for MIS 311 Assignment #1.

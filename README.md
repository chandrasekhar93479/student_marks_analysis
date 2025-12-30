# student_marks_analysis
Student Performance Data Analysis (EDA)
📌 Project Overview

This project is part of the Data Science / Data Analysis with Python – Internship Task 1.
The objective is to explore, clean, merge, analyze, and visualize student performance data using Python.

Two datasets related to student academic performance were merged and analyzed to answer key analytical questions using Exploratory Data Analysis (EDA) techniques.

📁 Dataset Description

The project uses the following datasets:

student-mat.csv → Student performance in Mathematics

student-por.csv → Student performance in Portuguese

Both datasets were merged using common student attributes such as demographic, family, and educational background details.

🔗 Dataset Merge Details

Merge Type: Inner Join

Merge Columns:
school, sex, age, address, famsize, Pstatus, Medu, Fedu, Mjob, Fjob, reason, nursery, internet

Final Dataset Size:
382 rows × 53 columns

The merged dataset is saved as:

merged_student_data.xlsx

🛠 Tools & Technologies Used

Python 3

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook / Google Colab

📌 Tasks Performed
1️⃣ Data Loading

Loaded datasets using Pandas

Verified structure and column details

2️⃣ Data Cleaning

Checked for missing values

Removed duplicate records

Verified data types and consistency

3️⃣ Exploratory Data Analysis (EDA)

Answered the following questions:

What is the average final grade (G3)?

How many students scored above 15?

Is study time correlated with academic performance?

Which gender performs better on average?

4️⃣ Data Visualization

Histogram of final grades

Scatter plot: Study time vs Final grades

Bar chart: Gender-wise average performance

5️⃣ Reporting

Generated a PDF EDA report

Created a clean merged Excel dataset

Documented findings clearly

📂 Project Structure
├── merged_student_data.xlsx
├── Student_EDA_Report.pdf
├── eda_student_analysis.ipynb
├── README.md

📈 Key Insights

Portuguese subject has a slightly higher average score than Math.

More students scored above 15 in Portuguese.

Study time shows a positive correlation with performance.

Female students perform slightly better on average.

▶️ How to Run the Project

Open Jupyter Notebook or Google Colab

Upload merged_student_data.xlsx

Run the EDA Python code cells

View visualizations and insights

✅ Internship Task Compliance

✔ Data Loading
✔ Cleaning
✔ Analysis
✔ Visualization
✔ Documentation
✔ Submission-ready format

👨‍🎓 Author

Konatham Chandrasekhar Reddy

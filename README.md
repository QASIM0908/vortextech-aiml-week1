# vortextech-aiml-week1
# Week 1: Data Cleaning and Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project represents the completion of the **Week 1 Task for the Vortex Tech AI & ML Internship Track**. The main goal of this task is to take a raw, real-world dataset, clean its structural imperfections, and perform basic Exploratory Data Analysis (EDA) to find initial insights before applying Machine Learning models.

## 📊 Dataset Focus
* **Dataset Used:** Student Mental Health Dataset (Kaggle)
* **Dataset Dimensions:** 101 rows | 11 columns
* **Target Focus:** Tracking student attributes (Age, Course, CGPA) alongside mental health indices (Depression, Anxiety, Panic Attacks).

## 🛠️ Data Pipeline Implementation
I built a clean, reproducible Python data pipeline using Pandas, Matplotlib, and Seaborn:

1. **Data Audit:** Inspected data types, structural formatting, and initial dimensions.
2. **Missing Value Imputation:** Handled missing inputs in the `Age` variable dynamically using median values to avoid outlier distortion.
3. **Categorical Standardization:** Cleaned up inconsistent text entries (e.g., merging duplicate categories like `"year 1"` and `"Year 1"` caused by case sensitivity issues).
4. **Feature Engineering:** Extracted raw text CGPA ranges (e.g., `"3.00 - 3.49"`) and transformed them into continuous numerical scores (`CGPA_Score`) for mathematical computation.
5. **Visual Analysis:** Created an analytical dashboard featuring a univariate look at depression distributions, alongside a bivariate analysis checking how those distributions correlate across university academic years.

## 🚀 How to Run locally
1. Clone this repository:
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/vortextech-aiml-week1.git](https://github.com/QASIM0908/vortextech-aiml-week1.git)

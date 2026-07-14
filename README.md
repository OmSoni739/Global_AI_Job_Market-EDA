# Global AI Job Market & Salary Trends — Exploratory Data Analysis

## 📌 Overview

This project is a end-to-end Exploratory Data Analysis (EDA) of a balanced Global AI Job Market dataset containing 15,000 AI job postings. The goal is to uncover meaningful insights about salaries, experience levels, industries, company sizes, employment types, and other factors shaping the global AI job market — and to practice turning raw data into clear, business-relevant insights.

## 🎯 Objectives

1. Understand the structure and quality of the dataset.
2. Perform data cleaning and preprocessing.
3. Engineer new features from existing columns.
4. Analyze salary trends and job market patterns.
5. Visualize relationships between key variables.
6. Extract meaningful, business-relevant insights.

## 🛠️ Tools & Libraries

- **Python** — Pandas
- **Visualization** — Matplotlib, Seaborn
- **Environment** — Jupyter Notebook

## 📂 Dataset Information

**Dataset**: Global AI Job Market & Salary Trends

**Records**: 15,000

**Features**: 19 columns

### Key attributes include:

- Job Title
- Salary (USD)
- Experience Level
- Employment Type
- Company Size
- Company Location
- Industry
- Years of Experience
- Remote Ratio
- Benefits Score
- Posting Date
- Application Deadline

## 🔍 Approach

1. **Data Understanding** — inspected shape, structure, and data types
2. **Data Cleaning** — checked for nulls, removed duplicate records
3. **Feature Engineering** — parsed date columns and derived posting month/year and deadline month for time-based analysis
4. **Exploratory Analysis** — answered 10 business questions using summary statistics and visualizations
5. **Insights** — documented observations after every analysis step

## 💼 Business Questions Answered

1. Which month has the highest number of AI job postings?
2. Which month has the highest number of application deadlines?
3. How are AI job salaries distributed?
4. How does experience level affect AI job salaries?
5. Which top 10 AI job titles are most in demand?
6. Does company size influence AI salaries?
7. Which industries offer the highest average AI salaries?
8. Does years of experience influence AI salaries?
9. What are the most common employment types in the AI job market?
10. Which numerical variables are most strongly correlated?

## 📊 Visualizations Used

1. Count Plot
2. Histogram
3. Box Plot
4. Scatter Plot
5. Horizontal Bar Chart
6. Correlation Heatmap

## 📊 Key Insights

- **Hiring seasonality:** March recorded the highest number of job postings (1,953), while June had the lowest (912) — hiring activity peaks in Q1.
- **Salary range:** Average AI salary is ~$122,000/year, ranging from $16,621 to $410,273. Half of all jobs pay below $107,000.
- **Experience matters most:** Years of experience shows the strongest correlation with salary (0.74) — the single biggest driver of pay in this dataset.
- **Experience level:** Salaries rise consistently from Entry to Executive level, with Senior/Executive roles showing the widest pay variation.
- **Company size:** Large companies pay the highest median salaries and contain the most high-paying outliers (some exceeding $400,000).
- **Industry:** Technology leads in average pay, closely followed by Transportation and Automotive; Education pays the least among the top 10 industries. Overall, industry has a relatively modest effect on salary compared to experience.
- **Employment type:** Contract roles are the most common (3,841 postings), with Full-Time, Part-Time, and Freelance fairly evenly distributed.
- **Most in-demand roles:** Machine Learning Engineer is the most frequently posted job title (824 postings).

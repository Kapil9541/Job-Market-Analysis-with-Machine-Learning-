# 🌍 Remote Job Market Analysis & Machine Learning Project

## 📌 Project Overview

The rapid growth of remote work has transformed the global employment landscape. Organizations increasingly hire talent worldwide, generating large amounts of job-related data. This project analyzes remote job listings to identify hiring trends, in-demand skills, salary patterns, and workforce insights. Additionally, a machine learning model was developed to predict job role categories using NLP techniques.

---

## 🎯 Problem Statement

Remote job platforms contain large volumes of unstructured information such as job titles, skills, locations, and salary details. Extracting meaningful insights manually is difficult.

The objectives of this project are:

* Analyze global remote hiring trends
* Identify high-demand skills and job categories
* Study salary and location patterns
* Build a predictive machine learning model for job role classification

---

## 📂 Dataset Information

The dataset was collected through web scraping from remote job listing platforms.

### Dataset Features

* Category
* Job Title
* Company
* Skills
* Salary
* Country
* Remote Status
* Date Posted
* Job Links
* Role Category

---

## 🛠 Technologies & Libraries Used

### Programming & Data Processing

* Python
* Pandas
* NumPy
* Regular Expressions (re)
* Jupyter Notebook

### Web Scraping

* Requests
* BeautifulSoup
* Selenium

### Data Visualization

* Matplotlib
* Seaborn
* Power BI

### Machine Learning & NLP

* Scikit-learn
* TF-IDF Vectorizer
* Logistic Regression
* Multinomial Naive Bayes
* LabelEncoder

---

## 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Removed duplicates
* Handled missing values
* Converted relative dates into datetime format
* Standardized location and country names
* Cleaned salary information
* Normalized skills data
* Created role categories through feature engineering
* Exploded skills into separate rows for skill-level analysis

---

## 📊 Exploratory Data Analysis (EDA)

EDA was performed to discover trends and insights:

* Top hiring categories
* Most demanded skills
* Remote vs physical job trends
* Country-wise hiring distribution
* Salary insights
* Company hiring patterns

---

## 🔍 Key Findings & Insights

* Software Engineering roles dominate remote hiring
* Golang emerged as one of the most demanded skills
* United States led global remote recruitment
* AI, Cloud, and DevOps skills showed strong demand
* Most companies did not publicly disclose salary information
* Remote jobs represented a large portion of job listings

---

## 📈 Dashboard Development

An interactive Power BI dashboard was created including:

### KPI Cards

* Total Jobs
* Total Companies
* Total Countries
* Remote Job Percentage
* Average Salary

### Visualizations

* Top skills analysis
* Country-wise hiring patterns
* Job category distribution
* Salary insights
* Hiring trends over time
* Interactive filters and slicers

---

## 🤖 Machine Learning Model

### Problem Type

Multi-Class Classification

### Target Variable

Role_Category

### Features Used

* Job Title
* Skills
* Country
* Remote Status

---

## ⚙️ Machine Learning Workflow

1. Feature Selection
2. Feature Engineering
3. Text Combination
4. TF-IDF Vectorization
5. Label Encoding
6. Train-Test Split
7. Model Training
8. Model Evaluation

---

## 🧠 Algorithms Used

### Logistic Regression

Used as a baseline classification model for text classification.

### Multinomial Naive Bayes

Used as an additional NLP classification model.

---

## 📉 Model Evaluation Metrics

The model was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Classification Report
* Confusion Matrix

### Confusion Matrix Findings

* Strong diagonal concentration indicated accurate predictions
* Minor overlap existed between similar job categories
* Engineering and data-related roles showed high prediction accuracy

---

## 💼 Business Impact

This project helps:

* Companies understand hiring trends
* Recruiters analyze workforce demand
* Job seekers identify high-demand skills
* Organizations make data-driven hiring decisions

---

## 🚀 Future Scope

Potential future improvements:

* Implement BERT and advanced NLP models
* Develop salary prediction models
* Build job recommendation systems
* Deploy ML model as a web application
* Real-time remote job monitoring

---

## 👨‍💻 Author

Kapil Khatana

Motivated Data Scientist | Python | SQL | Power BI | Machine Learning

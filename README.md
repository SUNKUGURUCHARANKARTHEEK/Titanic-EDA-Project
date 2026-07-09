# Titanic EDA Project

## Overview
This project analyzes the Titanic dataset to understand passenger survival through data cleaning and visualization.

## Objectives
- Understand the dataset structure
- Clean and prepare the data
- Handle missing values
- Check for duplicate records
- Identify outliers
- Perform EDA and summarize insights

## Dataset
The dataset contains passenger information such as age, gender, class, fare, cabin, and embarkation port.

## Steps Performed
- Missing values were handled using suitable methods
- Duplicate records were checked
- Outliers were detected using visual analysis
- Multiple charts were created to explore survival patterns

## Key Insights
- Female passengers had a higher survival rate than male passengers
- First-class passengers had better survival chances
- Most passengers were between 20 and 40 years old
# Titanic EDA Project

## 📌 Project Overview

This project focuses on cleaning and exploring the Titanic dataset to uncover insights about passenger survival. The analysis includes handling missing values, checking for duplicates, detecting outliers, and creating visualizations to understand patterns in the data.

---

## 🎯 Objectives

- Understand the structure of the Titanic dataset
- Clean and prepare the data for analysis
- Handle missing values effectively
- Check for duplicate records
- Detect outliers using visualization techniques
- Perform Exploratory Data Analysis (EDA)
- Derive meaningful insights from the data

---

## 📂 Dataset Information

The Titanic dataset contains information about passengers, including:

- Passenger ID
- Survival status
- Passenger class
- Name
- Gender
- Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Ticket information
- Fare
- Cabin
- Port of embarkation

Dataset source: Kaggle Titanic Dataset

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- VS Code

---

## 🧹 Data Cleaning Process

### Missing Value Treatment

| Column | Missing Values | Method Used |
| ------ | -------------- | ----------- |
| Age | 177 | Median imputation |
| Cabin | 687 | Replaced with "Unknown" |
| Embarked | 2 | Mode imputation |

### Duplicate Records

- Checked for duplicate entries
- No duplicate records were found

### Outlier Detection

- Box plots were used to identify outliers
- The Fare column showed several extreme values

---

## 📊 Exploratory Data Analysis

The following visualizations were created:

1. Survival count
2. Gender vs. survival
3. Passenger class vs. survival
4. Age distribution
5. Correlation heatmap
6. Fare box plot

---

## 📈 Key Insights

- Female passengers had a significantly higher survival rate than males
- First-class passengers had better chances of survival
- Most passengers were between 20 and 40 years old
- Fare values contained several outliers
- Passenger class and fare showed strong relationships with survival outcomes

---

## 📁 Project Structure

```text
Titanic-EDA-Project
│
├── README.md
├── analysis.py
├── train.csv
└── images/
    ├── survival_count.png
    ├── gender_vs_survival.png
    ├── class_vs_survival.png
    ├── age_distribution.png
    └── heatmap.png
```

---

## 🚀 How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/SUNKUGURUCHARANKARTHEEK/Titanic-EDA-Project.git
```

2. Navigate to the project folder

```bash
cd Titanic-EDA-Project
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

4. Run the analysis script

```bash
python analysis.py
```

---

## 👨‍💻 Author

SUNKUGURUCHARANKARTHEEK

GitHub: https://github.com/SUNKUGURUCHARANKARTHEEK

---

## ⭐ Project Status

✅ Completed

This project was created as part of an exploratory data analysis task focused on understanding the Titanic dataset through data cleaning and visualization.

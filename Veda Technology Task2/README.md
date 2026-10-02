# Veda Technology – Task 2

## Exploratory Data Analysis on Titanic Dataset

### 📌 Project Overview

This project was completed as part of my **Data Analytics Internship at Veda Technology**.

The objective of this task is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python. The analysis focuses on data cleaning, statistical analysis, visualization, correlation analysis, and identifying patterns related to passenger survival.

### 🎯 Objectives

* Explore and understand the Titanic dataset
* Identify and handle missing values
* Remove duplicate and unnecessary records
* Convert categorical data into numerical format
* Perform statistical analysis
* Analyze passenger survival patterns
* Create meaningful data visualizations
* Study correlations between numerical features
* Extract useful insights from the dataset

### 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

### 📂 Project Structure

```text
Veda_Technology_Task_2
│
├── dataset
│   └── titanic.csv
│
├── cleaned_data
│   ├── titanic_cleaned.csv
│   └── titanic_final.csv
│
├── task2.ipynb
└── README.md
```

### 🔍 Data Cleaning

The following preprocessing steps were performed:

* Checked the dataset structure
* Identified missing values
* Filled missing `Age` values using the median
* Filled missing `Embarked` values using the mode
* Removed the `Cabin` column due to a large number of missing values
* Checked and removed duplicate records
* Removed unnecessary columns such as `PassengerId`, `Name`, and `Ticket`
* Converted categorical variables into numerical values

### 📊 Exploratory Data Analysis

The following analyses were performed:

* Overall survival analysis
* Survival analysis by gender
* Survival analysis by passenger class
* Age distribution analysis
* Survival analysis by age group
* Family size analysis
* Correlation analysis

### 📈 Data Visualizations

The project includes visualizations such as:

* Survival percentage by passenger class
* Survival percentage by gender
* Age distribution of passengers
* Survival percentage by age group
* Survival percentage by family size
* Correlation heatmap

### 💡 Key Insights

* The overall survival rate was **38.38%**.
* Female passengers had a survival rate of approximately **74.20%**.
* Male passengers had a survival rate of approximately **18.89%**.
* First-class passengers had a survival rate of approximately **62.96%**.
* Second-class passengers had a survival rate of approximately **47.28%**.
* Third-class passengers had a survival rate of approximately **24.24%**.
* Survival rates varied across different age groups and family sizes.

### 📁 Output Files

The cleaned and processed datasets are stored in the `cleaned_data` folder:

* `titanic_cleaned.csv`
* `titanic_final.csv`

The complete analysis, code, outputs, and visualizations are available in:

* `task2.ipynb`

### ✅ Conclusion

This project provided practical experience in **data cleaning, exploratory data analysis, statistical analysis, data visualization, and extracting meaningful insights using Python**.

It helped strengthen my understanding of how data can be prepared, analyzed, and visualized to identify useful patterns and relationships.

---

### 👩‍💻 Internship

**Data Analytics Internship – Veda Technology**

**Task:** Exploratory Data Analysis using Python

**Dataset:** Titanic Dataset

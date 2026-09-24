# Data Analysis & Programming Project

> A data analysis and machine learning project developed for the **Programming for Data Analysis** course in the Data Science specialization at my university.

## 📌 Project Overview

This project explores **employee attrition** using data analysis, statistical techniques, and machine learning.

The dataset contains information about employees and various factors that may be associated with their decision to leave an organization. The project aims to transform raw employee data into meaningful insights that can help understand workforce patterns and employee turnover.

The analysis covers the complete data analysis workflow, from **data preprocessing and exploratory data analysis (EDA)** to **statistical analysis and machine learning modeling**.

## 🎯 Objectives

The main objectives of this project are to:

* Understand the structure and characteristics of the employee dataset.
* Perform data cleaning and preprocessing.
* Explore patterns and relationships among employee attributes.
* Identify key factors and trends associated with employee attrition.
* Apply statistical analysis to uncover relationships between employee metrics and attrition.
* Build machine learning models to predict employee attrition.
* Interpret the results and provide actionable recommendations for HR management.

## 📊 Project Workflow

The project follows a typical data science workflow:

```text
Raw Data
   │
   ▼
Data Cleaning & Preprocessing
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Statistical Analysis
   │
   ▼
Feature Preparation
   │
   ├───────────────┐
   ▼               ▼
Attrition      Linear
Prediction     Regression
   │               │
   └───────┬───────┘
           ▼
     Results & Insights
```

## 🔍 Analysis

### 1. Data Preparation

The project begins with preparing the employee dataset for analysis, including:

* Inspecting the dataset structure
* Handling data types and variables
* Cleaning and transforming data
* Preparing variables for statistical analysis and machine learning

### 2. Exploratory Data Analysis

Exploratory analysis is used to investigate employee characteristics and discover patterns within the dataset.

The analysis examines relationships between employee attributes and **attrition**, helping identify variables that may be associated with employee turnover.

### 3. Statistical Analysis

Statistical techniques are applied to examine relationships and differences within the data.

This provides a quantitative foundation for interpreting the patterns observed during exploratory analysis.

### 4. Machine Learning

Two machine-learning components are included in the project:

#### Employee Attrition Prediction

`[MachineLearning]_AttritionPrediction.ipynb`

A classification-oriented analysis focused on predicting whether an employee is likely to leave the organization.

The notebook demonstrates the process of preparing employee data for predictive modeling and evaluating the resulting model.

#### Linear Regression

`[MachineLearning]_LinearRegression.ipynb`

A linear regression analysis exploring relationships between selected variables and a continuous target variable.

The notebook demonstrates the application of regression modeling as part of the broader data analysis workflow.

## 📁 Repository Structure

```text
Data-Analysis-Programming-Project/
│
├── Data/
│   └── Dataset files
│
├── DAP_SourceCode.ipynb
│   └── Main data analysis and programming workflow
│
├── [MachineLearning]_AttritionPrediction.ipynb
│   └── Employee attrition prediction
│
├── [MachineLearning]_LinearRegression.ipynb
│   └── Linear regression analysis
│
├── Data Analysis Programming_Report.pdf
│   └── Project report
│
└── README.md
    └── Project documentation
```

## 🛠️ Tools & Technologies

* **Python**
* **Jupyter Notebook**
* **Pandas** — data manipulation and analysis
* **NumPy** — numerical computing
* **Matplotlib** — data visualization
* **Seaborn** — statistical visualization
* **Scikit-learn** — machine learning
* **Statistical analysis techniques**

## 📈 Key Areas of Analysis

The project focuses particularly on:

* Employee demographics
* Job and organizational characteristics
* Compensation-related factors
* Work experience
* Job satisfaction
* Work-life-related factors
* Employee attrition
* Relationships between employee characteristics and outcomes

## 📚 Dataset

The project uses an employee dataset sourced from **Kaggle**. The dataset contains employee-level information and an attrition indicator, making it suitable for exploratory analysis and predictive modeling.

> **Note:** The dataset is used for educational and analytical purposes as part of a university course project.

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.x and Jupyter Notebook installed.

You can install the main dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Run the Project

Clone the repository:

```bash
git clone https://github.com/nnttvy/Data-Analysis-Programming-Project.git
```

Navigate to the project directory:

```bash
cd Data-Analysis-Programming-Project
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Then open the notebooks in the following order:

1. `DAP_SourceCode.ipynb`
2. `[MachineLearning]_AttritionPrediction.ipynb`
3. `[MachineLearning]_LinearRegression.ipynb`

## 📊 Results & Report

A full write-up of the methodology, findings, and recommendations is available in Data Analysis Programming_Report.pdf.

## 🎓 Academic Context

This project was completed as part of the **Programming for Data Analysis** course within the **Data Science specialization at UEH University**.

It demonstrates the application of programming, data analysis, statistics, visualization, and introductory machine learning techniques to a practical business problem.

## 📌 Disclaimer

This project was developed for academic purposes. The findings and machine learning models should not be interpreted as production-ready HR decision-making systems without further validation using appropriate organizational data.

---

⭐ If you find this project useful or interesting, feel free to explore the notebooks and analysis.

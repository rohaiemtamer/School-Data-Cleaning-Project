#  School Data Cleaning & Preparation Project

##  Project Story

Raw data is rarely ready for analysis.

In real-world projects, datasets often contain missing values, inconsistent formatting, duplicated information, and quality issues that can negatively impact reporting and business decisions.

This project simulates a real data preparation workflow using a school management dataset. The objective was not only to clean the data, but also to transform it into a reliable, analysis-ready structure that can later be loaded into SQL Server and used in Business Intelligence solutions such as Power BI dashboards.

The project focuses on applying practical data cleaning techniques that are commonly used by Data Analysts during the data preparation phase.

---

#  Project Objectives

The main goals of this project were:

* Understand the structure of the dataset
* Assess data quality issues
* Handle missing and inconsistent values
* Standardize categorical fields
* Improve data consistency across tables
* Prepare data for SQL Server integration
* Create a reliable dataset for future reporting and analytics

---

#  Dataset Overview

The dataset represents a school management environment and contains multiple related entities.

### Included Tables

* Students
* Teachers
* Courses
* Classes
* Departments
* Student Assessments

The structure follows a dimensional modeling approach where fact and dimension tables can later be integrated into a reporting solution.

---

#  Data Understanding

Before performing any cleaning operations, the dataset was explored to understand:

* Number of sheets
* Table structure
* Column names
* Data types
* Missing values
* Potential inconsistencies

This step helped identify the main data quality issues that needed to be addressed.

---

#  Data Cleaning Process

Several cleaning operations were applied throughout the project.

## 1. Missing Value Treatment

Missing values were detected across different tables.

Appropriate strategies were applied depending on the column type:

* Replacing null values where applicable
* Creating alternative values for incomplete records
* Preserving data integrity while reducing information loss

---

## 2. Text Standardization

Text fields were standardized to improve consistency.

Operations included:

* Removing unnecessary spaces
* Normalizing categorical values
* Correcting inconsistent formatting

This ensures that categories are treated consistently during future analysis.

---

## 3. Data Consistency Improvements

Different validation checks were performed to ensure:

* Consistent naming conventions
* Reliable category values
* Better data quality across dimensions

---

## 4. Feature Engineering

Additional derived fields were created to improve usability and support downstream reporting requirements.

These transformations help make the dataset more analysis-friendly.

---

## 5. Data Validation

After cleaning operations were completed, validation checks were performed to verify:

* Missing values were properly handled
* Data transformations were applied successfully
* Tables remained structurally consistent

---

#  SQL Preparation

One of the key objectives of this project was preparing the dataset for database integration.

The project includes:

* SQL-compatible data type mapping
* Database-ready structure
* Preparation for loading into SQL Server

This step bridges the gap between raw Excel data and enterprise reporting environments.

---

# 🛠 Technologies Used

| Tool             | Purpose                        |
| ---------------- | ------------------------------ |
| Python           | Data Processing                |
| Pandas           | Data Cleaning & Transformation |
| NumPy            | Data Manipulation              |
| Jupyter Notebook | Development Environment        |
| SQL Server       | Future Data Storage & Analysis |

---

#  Project Structure

```text
School-Data-Cleaning-Project
│
├── data
│   └── school_dataset.xlsx
│
├── images
│   ├── notebook_preview (1).png
│   ├── notebook_preview (2).png
│   ├── notebook_preview (3).png
│   ├── notebook_preview (4).png
│   └── notebook_preview (5).png
│
├── notebooks
│   └── School_Data_Cleaning.ipynb
│
├── README.md
└── requirements.txt
```

#  Project Preview

![Notebook Preview](images/notebook_preview%20\(1\).png)

![Notebook Preview](images/notebook_preview%20\(2\).png)

![Notebook Preview](images/notebook_preview%20\(3\).png)

---

#  Outcome

The final output is a cleaned and structured dataset that can be directly used for:

* Business Intelligence reporting
* Power BI dashboards
* SQL analytics
* Educational performance analysis
* Data warehousing workflows

---

#  Future Improvements

Potential next steps include:

* Loading the cleaned dataset into SQL Server
* Building a star schema model
* Creating interactive Power BI dashboards
* Developing KPI tracking reports
* Automating the ETL workflow

---

#  Author

**Rohaiem Tamer**

Data Analyst | Business Intelligence Enthusiast

This project was developed as part of my data analytics portfolio to demonstrate practical data cleaning, transformation, and preparation skills using Python.

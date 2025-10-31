# Police Traffic Stops Analysis

A comprehensive analysis of traffic stops using a real-world police dataset.  
This project demonstrates **data cleaning, exploratory data analysis (EDA), visualization, and statistical insights** with Python and Pandas.

---

## Overview

Traffic stop data can reveal patterns in enforcement, gender and race disparities, and the outcomes of stops.  
This project performs data preprocessing, visualizes stop trends, and calculates key metrics such as **stop frequency by hour, driver demographics, stop outcomes, and arrest rates by race and gender**.

---

## Key Features

- **Data Cleaning** – Handling missing values, converting datatypes, and creating datetime columns.  
- **Exploratory Data Analysis (EDA)** – Visualizing stop counts by hour and analyzing stop patterns.  
- **Driver Demographics** – Calculating percentages of drivers by gender and race.  
- **Stop Outcomes** – Analyzing outcomes (Citation, Arrest, Warning, etc.) and their percentages.  
- **Arrest Analysis** – Calculating arrest counts and rates by driver race and gender.  
- **Visualization** – Bar charts for hourly stop distribution.

---

## Tech Stack

- **Python 3.10+**
- **Pandas** for data manipulation
- **Matplotlib** for visualizations

---

## Sample Results
### Stops by Hour 
Most common stop hour: 10
Number of stops at that hour: 7350

### Driver Gender Percentages
- Man: 68.56%
- Woman: 25.63%
- Unknown: 5.82%

### Stop Outcomes
| Stop outcomes | their percentages |
|---------------|-------------------|
| Citation | 83.94% |
| Unknown | 5.81% |
| Warning | 5.77% |
| Arrest Driver | 2.80% |
| N/D | 0.64% |
| No Action | 0.64% |
| Arrest Passenger | 0.39% |

### Arrest Counts by Race and Gender
Arrested counts by race and gender:
- Asian        F: 11, M: 30
- Black        F: 134, M: 571
- Hispanic     F: 80, M: 486
- White        F: 371, M: 1244
- Other        M: 2
- Unknown      Unknown: 5333

### Arrest Rate (%) by Race and Gender
| Unknown | Unknown: 5.81% |
|---------|----------------|
| White | M: 1.36% |
| Black | M: 0.62% |
| Hispanic | M: 0.53% |
| White | F: 0.40% |
| Black | F: 0.15% |
| Hispanic | F: 0.09% |
| Asian | M: 0.03% |
| Asian | F: 0.01% |
|Other | M: 0.002% |

### Insights & Learnings
- Traffic stops peak around 10 AM, indicating daytime policing patterns.
- Male drivers constitute the majority of stops, but arrest rates vary significantly by race and gender.
- Citation is the most common stop outcome (over 80%), whereas arrests are relatively rare.
- The dataset contains some missing or unknown values, highlighting the need for careful data cleaning and preprocessing.
- These insights could inform policies, transparency, and fairness in policing practices.

⭐ Star the repository if you find it useful!

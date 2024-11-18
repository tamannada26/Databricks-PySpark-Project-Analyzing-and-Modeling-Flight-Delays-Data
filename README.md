# PySpark-Project-Analyzing-and-Modeling-Flight-Delays-Data
This repository contains a PySpark-based project for analyzing and predicting flight delays using the Flight Delays and Cancellations dataset. The project was developed and executed on Databricks. It showcases an end-to-end workflow, including data loading, cleaning, exploratory analysis, and building predictive models.



## Project Overview  
The objective of this project is to demonstrate proficiency in PySpark for big data analysis and machine learning by analyzing flight delays and cancellations. It involves:  
- **Data Preparation**: Loading and cleaning the dataset.  
- **Feature Engineering**: Transforming raw data into actionable insights.  
- **Exploratory Data Analysis (EDA)**: Using SQL queries and visualizations to derive insights.  
- **Modeling**: Predicting flight delays using regression and classification models.  

---

## Dataset  
The dataset used in this project contains information about flight delays, cancellations, and their causes. It includes details such as airline codes, flight dates, departure and arrival delays, and reasons for delays.  

---

## Workflow  

### 1. Data Loading and Initial Exploration  
- **Dataset**: `flights.csv`  
- **Key steps**:  
  - Loading the dataset as a PySpark DataFrame.  
  - Displaying schema and sample rows.  
  - Determining the dataset's shape (rows and columns).  

---

### 2. Data Cleaning and Transformation  
- **Handling missing values**:  
  - Dropping columns/rows with excessive missing data.  
  - Imputing missing values for numerical columns.  
- **Feature engineering**:  
  - Extracting `DAY_OF_WEEK` and `MONTH` from flight dates.  
  - Creating a binary column indicating whether a flight was delayed (`ARRIVAL_DELAY > 0`).  
- **Data type conversions**:  
  - Ensuring columns have appropriate types for analysis.  

---

### 3. Exploratory Data Analysis (EDA)  

Using PySpark SQL for:  
- Calculating the average delay time for each airline.  
- Identifying the top 5 airports with the most delayed departures.  
- Determining the most common reason for flight cancellations.  

**Visualizations**:  
- Average delay by airline.  
- Delay patterns over days of the week and months.  

---

### 4. Predictive Modeling  
- **Predicting flight delays using PySpark MLlib**:  
  - Data splitting, training, and testing.  
  - Building regression and classification models.  
  - Evaluating model performance using metrics such as RMSE and accuracy.  

---

## Results  
Key insights from EDA:  
- Airlines with the highest average delays.  
- Airports prone to departure delays.  
- Seasonal patterns in delays.  

---

## Prerequisites  
- Python 3.x  
- Databricks Workspace  
- PySpark  


# Hospital Management Analysis Dashboard

## Project Overview

This project is a comprehensive **Hospital Management Analysis** created using **Microsoft Excel**. The project analyzes hospital operations, patient visits, revenue, doctors, diagnoses, appointments, payment methods, and patient satisfaction.

The dataset contains approximately **1,000,000 hospital records** covering the period from **2024 to 2026**.

The main objective of this project is to transform raw hospital data into meaningful insights through **data cleaning, analysis, PivotTables, PivotCharts, slicers, and an interactive dashboard**.

---

# Project Objectives

The main objectives of this project are:

- Analyze overall hospital revenue
- Calculate total patient visits
- Calculate the total number of distinct doctors
- Analyze patient satisfaction scores
- Measure average waiting time
- Measure average patient stay time
- Identify top revenue-generating hospitals
- Analyze revenue across different cities
- Identify the most common diagnoses
- Analyze appointments across departments
- Understand gender distribution
- Analyze payment modes
- Track monthly revenue trends
- Analyze patient visit status

---

# Dashboard KPIs

The dashboard includes the following Key Performance Indicators (KPIs):

- 💰 Total Revenue
- 😊 Average Satisfaction Score
- 👥 Total Patients
- 👨‍⚕️ Total Distinct Doctors
- ⏳ Average Waiting Time
- 🏥 Average Stay Time

---

# Dashboard Analysis

The interactive dashboard includes the following visualizations:

### 1. Monthly Revenue Trend
Shows how hospital revenue changes over time from **2024 to 2026**.

### 2. Payment Mode Analysis
Analyzes the different payment methods used by patients, such as:

- Bank Transfer
- Card
- Cash
- Insurance
- UPI

### 3. Top 5 Diagnoses
Displays the most common diagnoses recorded in the hospital dataset.

### 4. Top 5 Revenue Generating Hospitals
Identifies the hospitals generating the highest revenue.

### 5. Top Cities by Revenue
Shows revenue contribution from different cities.

### 6. Gender Distribution
Analyzes patient distribution based on gender categories.

### 7. Appointments by Department
Displays appointment activity across different hospital departments.

### 8. Visit Status
Analyzes different patient visit outcomes, such as:

- Admitted
- Completed
- Cancelled
- Discharged
- No Show

---

# Data Cleaning Process

Several data cleaning operations were performed before creating the dashboard.

### ✔ Handling Missing Values

Missing values were identified in important columns such as:

- Patient Age
- Doctor ID
- Insurance Type
- Waiting Time

Appropriate cleaning techniques were applied depending on the type of data.

### ✔ Handling Invalid Ages

Unrealistic patient ages were identified in the dataset.

Invalid age values were handled to improve the accuracy and reliability of the analysis.

### ✔ Handling Missing Doctor IDs

Missing doctor IDs were identified and handled during the data cleaning process.

### ✔ Handling Duplicate Data

Duplicate records and duplicate doctor IDs were analyzed to ensure accurate reporting.

### ✔ Distinct Doctor Calculation

The total number of doctors was calculated using **unique/distinct Doctor IDs** instead of counting every patient visit.

This ensures that doctors appearing multiple times in the dataset are not counted repeatedly.

---

# Tools and Technologies Used

- Microsoft Excel
- PivotTables
- PivotCharts
- Excel Formulas
- Data Cleaning Techniques
- Slicers
- Conditional Formatting

---

# Interactive Features

The dashboard includes interactive slicers for filtering the data.

### Available Filters:

- 📅 Year
- 📆 Month

These slicers allow users to analyze hospital performance for different time periods.

---

# Project Structure

```text
Hospital Management Analysis
│
├── Hospital_Management_Data
│   └── Raw and cleaned hospital dataset
│
├── PivotTables
│   ├── Revenue Analysis
│   ├── Payment Mode Analysis
│   ├── Appointment Analysis
│   └── Doctor Analysis
│
└── Hospital Analysis Dashboard
    ├── KPI Cards
    ├── Revenue Trend
    ├── Diagnosis Analysis
    ├── Hospital Revenue Analysis
    ├── City Revenue Analysis

## Key Insights
Some important insights that can be generated from this dashboard include:
Identification of the highest revenue-generating hospitals
Analysis of revenue trends over different months and years
Understanding of the most common patient diagnoses
Identification of departments with high appointment volumes
Analysis of patient payment preferences
Understanding patient gender distribution
Monitoring patient waiting and stay times
Tracking different visit outcomes
Monitoring hospital performance through interactive filters

## Dashboard Preview
The dashboard provides a complete overview of hospital performance from 2024 to 2026, combining operational, financial, and patient-related metrics in one interactive Excel dashboard.

🚀 Skills Demonstrated
Through this project, the following Data Analytics skills were demonstrated:
Data Cleaning
Data Validation
Handling Missing Values
Handling Duplicate Records
Data Analysis
KPI Development
PivotTable Analysis
PivotChart Creation
Dashboard Design
Data Visualization

Business Insight Generation
    ├── Gender Distribution
    ├── Department Analysis
    └── Visit Status Analysis

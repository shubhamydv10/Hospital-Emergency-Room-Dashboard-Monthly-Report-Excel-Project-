# Hospital-Emergency-Room-Dashboard-Monthly-Report-Excel-Project-

## 📘 Project Overview

This project presents an **interactive Excel dashboard** designed to analyze and monitor key performance indicators (KPIs) of a **Hospital Emergency Room (ER)** on a **monthly basis**.
The dashboard provides a clear and comprehensive view of hospital operations — including patient flow, waiting times, satisfaction levels, and admission trends — helping management make data-driven decisions for better patient care and resource allocation.

---

## 🎯 Objective

The main objective of this <a href="https://github.com/shubhamydv10/Hospital-Emergency-Room-Dashboard-Monthly-Report-Excel-Project-/blob/main/Final%20Dashboard.png">Dashboard</a> is to:

* Track and visualize **monthly emergency room performance**.
* Identify **patient trends** such as age, gender, and referral departments.
* Monitor **wait times** and **service efficiency**.
* Improve **decision-making** in hospital operations by providing clear, visual insights.

---

## 📊 Key Insights Displayed

The dashboard consists of multiple performance metrics and visualizations:

### 1. **KPIs Section**

* **No. of Patients:** 513 total patients recorded in the selected month.
* **Average Wait Time:** 36.32 minutes, reflecting service efficiency.
* **Patient Satisfaction Score:** 4.96 out of 5, indicating high satisfaction levels.

### 2. **Admission Status**

* **Admitted:** 269 patients (52%)
* **Not Admitted:** 244 patients (48%)
  Shows hospital admission efficiency and patient retention.

### 3. **Patient Attended within Time**

* **62%** patients attended *on time*.
* **38%** experienced *delays*.
  Visualized through a pie chart to assess service punctuality.

### 4. **Gender-wise Analysis**

* **Female:** 53%
* **Male:** 47%
  Highlights gender distribution among ER visitors.

### 5. **Patient Distribution by Age Group**

Displays number of patients across different age categories:
`0–9`, `10–19`, `20–29`, `30–39`, `40–49`, `50–59`, `60–69`, `70–79`.
Most visits occur in younger and middle-aged groups.

### 6. **Department Referral Analysis**

Shows which departments ER patients are referred to:

* General Practice (103)
* Orthopedics (65)
* Cardiology (14)
* Physiotherapy (14)
* Neurology (9)
* Renal (5)
* Gastroenterology (4)
* None (299 — not referred further)

This helps in understanding patient flow and departmental workload.

---

## 🧩 Features & Functionality

* **Month Selector (Jan–Dec):** Dynamic button-based navigation to view monthly data.
* **Year Filter (2023–2024):** Switch between different years of records.
* **Interactive Visuals:** Pie charts, bar charts, and KPI cards update dynamically.
* **Sparklines:** Mini line charts beneath KPIs show performance trends.
* **User-Friendly Layout:** Clean, minimal design with color-coded sections for clarity.

---

## 🧮 Tools & Techniques Used

* **Tool:** Microsoft Excel
* **Techniques:**

  * PivotTables & PivotCharts
  * Slicers and Form Controls
  * Data Validation and Conditional Formatting
  * Dynamic Ranges and Formulas (`COUNTIFS`, `AVERAGEIFS`, etc.)
  * Chart Customization & Dashboard Formatting

---

## 📁 Dataset Description

The <a href="https://github.com/shubhamydv10/Hospital-Emergency-Room-Dashboard-Monthly-Report-Excel-Project-/blob/main/Hospital%20Emergency%20Room%20Data.csv">Dataset</a> contains anonymized records of emergency room visits, including:

| Column                | Description                                        |
| --------------------- | -------------------------------------------------- |
| `Patient_ID`          | Unique identifier for each visit                   |
| `Visit_Date`          | Date of ER visit                                   |
| `Year` / `Month`      | Used for filtering                                 |
| `Gender`              | Male/Female                                        |
| `Age`                 | Patient age                                        |
| `Wait_Time`           | Time difference between arrival and being attended |
| `Admission_Status`    | Admitted / Not Admitted                            |
| `Department_Referral` | Department where patient was referred              |
| `Satisfaction_Score`  | Feedback score (1–5)                               |
| `OnTime_Flag`         | OnTime / Delay                                     |

---

## 🧠 Key Takeaways

* The hospital maintained a **strong satisfaction score (4.96)**.
* **52% of patients admitted** — indicating a balanced case load.
* **Average waiting time** around 36 minutes suggests potential improvement areas.
* **62% on-time performance** can be enhanced through workflow optimization.
* Gender and age data show balanced and diverse patient demographics.

---










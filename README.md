#  Fintech Loan Portfolio Analysis – Power BI Project

## Table of Contents
- [Project Objective](#project-objective)
- [Dataset Overview](#dataset-overview)
- [Business Questions Answered](#business-questions-answered)
- [Power BI Report Features](#power-bi-report-features)
- [Tools & Technologies](#tools--technologies)
- [AI Assistance Used](#ai-assistance-used)
- [Project Workflow](#project-workflow)
- [Dashboard Previews](#-dashboard-previews)
- [Project Insight](#project-insight)
- [Final Conclusion](#final-conclusion)

---

##  Project Objective

This project simulates a loan portfolio analysis for a fictional fintech company. It uses customer, loan, and repayment data to answer key business questions. The entire analysis is built in **Power BI** and focuses on disbursement trends, customer risk segmentation, and repayment behavior.

---

##  Dataset Overview

* **Customers**: Region, income group, demographics
* **Loans**: Loan ID, amount, type, start date, loan status
* **Payments**: Daily repayment records and payment status

---

##  Business Questions Answered

1. **How much loan has been disbursed over time?**
2. **What is the current default rate?**
3. **Which customer segments (by region or income group) are riskier?**
4. **How is repayment behavior changing over time?**

---

##  Power BI Report Features

###  KPIs

* Total Loan Disbursed
* Total Amount Repaid
* Current Default Rate

###  Trend Analysis

* Monthly, Quarterly, and Yearly trends for loan disbursement and repayments
* Growth metrics: YoY (Year-over-Year), MoM (Month-over-Month), QoQ (Quarter-over-Quarter)

###  Risk Segmentation

* Breakdown by Region, Income Group, and Occupation
* Identification of higher-risk customer segments

###  Comparative Analysis

* Cumulative Repayments vs. Total Disbursed Loans

###  Interactive Filters

* Region
* Income Group
* Loan Status
* Date Range

---

##  Tools & Technologies

* **Power BI Desktop** – for data modeling and dashboard creation
* **Excel** – used for mock data creation and basic cleaning
* **DAX (Data Analysis Expressions)** – for custom measures and calculations

  * Examples: `CALCULATE`, `DIVIDE`, etc.

---

##  AI Assistance Used

I used **ChatGPT** to:

* Write and refine DAX measures (e.g., for default rate, MoM, QoQ, and YoY growth)
* Suggest the best visual types for presenting insights
* Structure the dashboard pages
* To generate business questions

---


##  Project Workflow

Below are the main steps followed to build this Power BI project:

1. **Data Cleaning**

   * Checked for missing values, errors, and duplicate entries.
   * Cleaned data using Excel and Power BI Query Editor.

2. **Data Preparation**

   * Assigned correct data types to each column (e.g., dates, numbers, text).
   * Created a **Date Table** for time-based analysis (used in YoY, MoM, QoQ metrics).
   * Renamed columns for clarity and consistency.

3. **Data Modeling**

   * Built relationships between tables using primary and foreign keys.
   * Ensured referential integrity between `Customers`, `Loans`, and `Payments`.

4. **Dashboard Planning**

   * Created multiple report pages based on business questions:

     * Disbursement Trends
     * Risk Segmentation
     * Repayment Analysis

5. **Report Building**

   * Designed interactive visuals and KPIs.
   * Applied slicers and filters (Region, Loan Status, Date Range).
   * Used **DAX** for custom calculations like default rate, growth metrics, and cumulative totals.

6. **Testing & Review**

   * Validated all visuals against source data.
   * Ensured performance and clarity for end users.

---

## 📸 Dashboard Previews

### 1️ Loan Portfolio Summary
![Loan Summary](https://raw.githubusercontent.com/NinadShenoy/Fintech_Loan_Portfolio-Data_Visualization/main/Screenshot-Loan%20Portfolio%20Summary.png)

### 2️ Disbursement Growth & Insight
![Disbursement Growth](https://raw.githubusercontent.com/NinadShenoy/Fintech_Loan_Portfolio-Data_Visualization/main/Screenshot-%20Disbursement%20Growth%20%26%20Insights.png)

### 3️ Credit Risk & Default Trends
![Credit Risk](https://raw.githubusercontent.com/NinadShenoy/Fintech_Loan_Portfolio-Data_Visualization/main/Screenshot-%20Credit%20Risk%20%26%20Default%20Trends.png)

### 4️ Loan Repayment Performance
![Loan Repayment](https://raw.githubusercontent.com/NinadShenoy/Fintech_Loan_Portfolio-Data_Visualization/main/Screenshot-Loan%20Repayment%20Performance.png)

---

### **Project Insight**

This project analyzes a 4-year fintech loan dataset to uncover patterns in disbursement growth, repayment trends, and default behavior. Key findings, 
* "High-income and East region borrowers drive most disbursements."
* "Salaried clients and the North region face the highest default risk."
* "Repayment peaked in 2023 but declined in 2024, indicating recovery stress."

---

###  **Final Conclusion**

The report shows that salaried customers and those from the North tend to default more often. While high-income individuals take larger loans, lower-income groups show more reliable repayment. To improve outcomes, lenders should review borrower data before issuing loans, be cautious with high-risk segments, and set up regular follow-ups like reminders or early support to reduce missed payments.

---

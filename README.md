# 🏥 Hospital Analysis Dashboard: Operational & Financial Deep Dive (Power BI Project)

## 🌟 Executive Summary

This project showcases a comprehensive, end-to-end business intelligence solution for modern hospital management, developed entirely in Power BI. It transforms raw, static Excel data into a dynamic, interactive suite of dashboards covering key operational domains: **Patient Flow**, **Doctor Performance**, **Operational Charges**, and **Financial Health**.

The primary objective is to move beyond simple reporting by providing granular, cross-functional visibility that facilitates data-driven decision-making. The dashboard suite features five distinct pages, enabling hospital leadership to monitor daily operations and strategic long-term performance simultaneously.

## 💾 Data Source & Preparation

The analysis is powered by a structured dataset sourced from **Microsoft Excel**.

* **Source Files:** The data was ingested and modeled directly from Excel workbooks, representing various facets of hospital operations (e.g., Patient Records, Medicine Inventory, Doctor Salaries, and Billing Logs).
* **Data Preparation (Power Query):** The data underwent rigorous cleaning, transformation, and shaping within Power BI's Power Query Editor to ensure integrity, consistency, and optimal performance for visualization.
* **Data Modeling:** A robust star schema or similar relational model was established to link fact tables (e.g., Charges, Sales) with dimension tables (e.g., Patients, Doctors, Dates), enabling complex cross-filtering and accurate aggregation across all dashboard pages.

---

## 📸 Dashboard Screenshots

| Page | Description | Image Placeholder |
| :--- | :--- | :--- |
| **Front Page** | Project cover and navigation overview. |  |
| **Overview Dashboard** | High-level summary of operational KPIs. | 

[Image of the Overview Dashboard from Page 2]
![image alt](Overview.png)
| **Patients Dashboard** | Detailed patient records and consumption patterns. |  |
| **Doctors Dashboard** | Doctor-specific performance and commission tracking. |  |
| **Finance Dashboard** | Comprehensive financial metrics and resource allocation. |  |

---

## 📈 Key Performance Indicators (KPIs)

The dashboard provides instant visibility into critical organizational metrics:

| Metric | Value | Dashboard Page | Insight | Source |
| :--- | :--- | :--- | :--- | :--- |
| **Total Patients** | 30 | [cite_start]Overview [cite: 29] [cite_start]/ Finance [cite: 284] | Total patients monitored in the current period. [cite_start]| [cite: 29, 284] |
| **Total Paid Amount** | 727K | [cite_start]Overview [cite: 30] [cite_start]/ Finance [cite: 286] | Total revenue generated from patient payments. [cite_start]| [cite: 30, 286] |
| **Average Age** | 45.57 | [cite_start]Overview [cite: 32] [cite_start]/ Finance [cite: 287] | Crucial for demographic analysis and resource planning. [cite_start]| [cite: 32, 287] |
| **Discharge Rate** | 73% | [cite_start]Overview [cite: 49] | Efficiency of patient turnover and recovery. [cite_start]| [cite: 49] |
| **Dr. Commission** | 71.38K | [cite_start]Overview [cite: 34] [cite_start]/ Finance [cite: 301] | Total commission paid to all doctors. [cite_start]| [cite: 34, 301] |
| **Doctor Salary Total** | 4M | [cite_start]Finance [cite: 289] | Total expenditure on doctor compensation. [cite_start]| [cite: 289] |
| **Staff Count** | 3,928 | [cite_start]Finance [cite: 311] | Total non-medical staff count. [cite_start]| [cite: 311] |
| **Staff Salary Total** | 714K | [cite_start]Finance [cite: 312] | Total expenditure on staff compensation. [cite_start]| [cite: 312] |

---

## 🔎 Detailed Visualizations Analysis

### 1. Overview Page Analysis (Page 2)
* [cite_start]**Patient Discharge By Date:** A line chart illustrating the number of patient discharges over time (May-23 to Oct-23) [cite: 38, 55-60]. This helps identify peak discharge periods and resource allocation needs.
* [cite_start]**Charges Breakdown:** A column chart displaying the distribution of revenue across core services: Surgery (0.43M), Room (0.17M), Test, Other, Fees, Discount, and Medicine [cite: 65, 76-87, 322]. **Surgery is identified as the primary revenue generator.**
* [cite_start]**Medicine Tracking Matrix:** A detailed matrix showing medicine purchases broken down by Month (May-Oct) and Day of the Week (Fri-Wed) [cite: 42, 53, 61-74].

### 2. Patients Page Analysis (Page 3)
* [cite_start]**Patient Charges:** A horizontal bar chart showing the individual financial burden by charge type for a selected patient (e.g., Amit Kumar: Surgery 25K, Room 10K, Test 5K) [cite: 133, 139-140, 143, 150, 157, 174].
* [cite_start]**Medicine Sale (QTY):** Ranks the quantity of specific medicines purchased by the patient, with **Omeprazole** and **Paracetamol** as the top items [cite: 134, 141-142].
* [cite_start]**Patient Feedback:** Captures qualitative data regarding patient experience (e.g., "Treatment was good but had to wait too long" [cite: 132]).

### 3. Doctor Page Analysis (Page 4)
* [cite_start]**Commission Rate:** Clearly displays the individual doctor's commission rate (e.g., Dr. Aditya Gupta: 10.0% [cite: 194]).
* [cite_start]**Patient Spend & Bills:** A table detailing the patients served, the status of their surgery, and the total Bills and Fees generated (e.g., Rahul Sharma: Bills 10010, Fees 800) [cite: 215, 219-234]. This allows for direct calculation of the doctor's contribution to revenue.

### 4. Finance Page Analysis (Page 6)
* [cite_start]**Medicines Stock Status:** Compares the 'Stock' versus 'Sales' ratio for critical medicines (e.g., Paracetamol, Ibuprofen, Omeprazole) [cite: 296-310]. This is vital for inventory management and preventing stock-outs.
* [cite_start]**Supplier Analysis:** Displays the distribution of unit prices across different healthcare suppliers (HealthCare Sup..., MediCore Enter..., MediPharm Dis...)[cite: 319, 327, 329, 341].

---

## ✅ Future Enhancements

* **DAX Optimization:** Further refining complex DAX measures for quicker rendering and performance.
* **Security Integration:** Implementing Row-Level Security (RLS) to restrict data views based on the user's role (e.g., a doctor only sees their patient data).
* **Web Integration:** Publishing the dashboard to the Power BI Service for broader organizational access and mobile viewing.

---

I've provided a very detailed and professional template. Now, you can easily copy this code into your `README.md` file on GitHub!

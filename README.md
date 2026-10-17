# HR Analytics & Workforce Performance Dashboard

An end-to-end Human Resources Data Analytics solution built with **Power BI** and multi-relational enterprise datasets. This interactive dashboard transforms raw HR, payroll, attendance, and organizational structure data into actionable workforce insights, supporting data-driven HR management and executive decision-making.

---

## Executive Summary

The **HR Analytics & Workforce Performance Dashboard** provides a 360-degree view of organizational health, employee dynamics, compensation structures, and workplace attendance. By analyzing multi-table relational data across departments, job roles, geographic regions, and employee tenure, this project identifies critical metrics such as active vs. terminated headcount proportions, gender compensation equality, manager span of control, and attendance patterns across operational units.

---

## Key Features & Dashboard Pages

### 1. HR Overview
The **HR Overview** page provides a high-level summary of headcount metrics, regional workforce distribution, department allocation, and demographic balance.

* **Headcount Distribution by Status:** Categorizes personnel into **Active (57.55%)**, **Resigned (14.08%)**, **On Leave (14.42%)**, and **Terminated (13.95%)**.
* **Top Departments by Headcount:** Highlights primary business units including *Logistics (274)*, *Internal Audit (270)*, *Records Management (266)*, *Data Analytics (265)*, *Contract Management (264)*, *Sales (264)*, and *Supply Chain (264)*.
* **Geographic Workforce Share:** Displays workforce distribution across key operational regions (*Mingachevir*, *Shirvan*, *Nakhchivan*, *Sheki*, *Sumgait*, *Baku*, *Lankaran*, and *Ganja*).
* **Gender Balance Overview:** Demonstrates balanced organizational representation (**50.67% Female** vs. **49.33% Male**).
* **Interactive Slicers:** Dynamic filtering by *Department Name* and *Position Title*.

---

### 2. Attendance & Turnover
The **Attendance & Turnover** page tracks employee presence, absence dynamics, monthly leave trends, and individual base salaries.

* **Monthly Attendance Overview (Absence Records):** Tracks top departments by total absence entries (*Records Management*, *Sustainability*, *Compliance*, *Environmental*, *Asset Management*, *Data Analytics*, *Events*, *Finance*, *Security*, *Tax*).
* **Absence Dynamics Over Time:** Line chart tracking monthly absence volumes from peak periods (*September: 173*, *August: 167*, *December: 166*) to lower volume periods (*November: 112*).
* **Attendance Status Breakdown:** Evaluates work presence categories including **Present (20.5%)**, **Remote (20.48%)**, **On Leave (19.87%)**, **Absent (19.73%)**, and **Late (19.41%)**.
* **Employee Salary Distribution:** Benchmarks top individual base salary distributions across staff positions.

---

### 3. Salary & Positions
The **Salary & Positions** page delivers in-depth financial compensation analysis, manager spans of control, and salary tier breakdowns across demographics.

* **Average Sales / Revenue Contribution by Department:** Analyzes mean revenue and operational contributions across units such as *Technical Support*, *Product Management*, *Engineering*, *Asset Management*, *Treasury*, *Communications*, *Environmental*, and *Innovation*.
* **Average Salary by Gender:** Evaluates pay parity between **Female (50.35%)** and **Male (49.65%)** personnel groups.
* **Headcount by Direct Manager:** Visualizes manager span of control and team sizes across key line managers.
* **Salary Range Breakdown Table:** Structured matrix summarizing total compensation distribution ($51.19M total budget) across defined salary brackets (`<1000` up to `7000+`).

---

## Data Architecture & Data Model

The analytical model is driven by four key enterprise datasets connected in a relational star-schema design:

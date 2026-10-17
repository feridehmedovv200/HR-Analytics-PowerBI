📊 HR Analytics & Workforce Dashboard (Power BI)

This project is an Interactive Power BI Dashboard designed for comprehensive analysis of HR Management, Employee Attendance, and Payroll Analytics. The objective of this project is to enable effective human resource management, analyze employee turnover, and visualize salary distribution across the workforce.

📸 Dashboard Pages & Visualizations

1. HR Overview

Provides a high-level view of workforce structure, employee status distribution, and regional breakdown:

Headcount Distribution by Status: Breakdown of personnel status (Active - 57.55%, Resigned, On Leave, Terminated).

Total Headcount by Department: Overview of top business units by employee headcount (Logistics, Internal Audit, Records Management, etc.).

Geographic Workforce Share: Regional distribution of employees across Azerbaijan (Mingachevir, Shirvan, Nakhchivan, Sheki, Sumgait, Baku, Lankaran, Ganja).

Gender Balance Overview: Gender representation across the organization (49.33% Female / 50.67% Male).

2. Attendance & Turnover

Monitors employee attendance trends, absenteeism, and work arrangements:

Attendance Status Breakdown: Distribution of employee work status (Present, Remote, Late, Absent, On Leave).

Monthly Attendance Overview: Tracking total absence records and attendance trends across months.

Employee Salary Distribution: Breakdown of individual employee salaries.

3. Salary & Positions

Detailed analysis of compensation matrices, gender-based salary trends, and manager workload:

Average Salary by Gender: Comparison of average base compensation across gender groups (~4.24K vs 4.3K).

Headcount by Direct Manager: Number of direct reports assigned to each line manager.

Salary Range vs Gender Matrix: Total compensation distribution across salary bands (e.g., 7000+, 6000-7000, <1000) grouped by gender.

📁 Repository Structure

.
├── data/
│   ├── attendance.xlsx      # Attendance records and logs
│   ├── departments.xlsx     # Department structures and metadata
│   ├── employees.xlsx       # Employee demographic and status data
│   └── positions.xlsx       # Job titles and salary ranges
├── screenshots/             # Visual assets and dashboard screenshots
├── HR_Analytics.pbix        # Power BI project file
└── README.md                # Project documentation


🛠️ Tech Stack & Key Concepts

Power BI Desktop: Dashboard design, data visualization, and reporting.

Power Query: Data extraction, transformation, and loading (ETL).

DAX (Data Analysis Expressions): Dynamic measures, calculated columns, and KPI calculations.

Data Modeling: Star schema modeling connecting employees, departments, positions, and attendance tables.

🚀 Getting Started

Clone the repository:

git clone https://github.com/USERNAME/REPOSITORY-NAME.git


Open HR_Analytics.pbix in Microsoft Power BI Desktop.

If prompted with data source errors, update the file paths to point to the local data/ folder in Power Query Editor.

🤝 Contact & Contributions

Feel free to open an issue or reach out directly if you have any questions or feedback regarding this project!

# Workforce Operations KPI Monitoring
### Operational performance monitoring and workforce analytics platform

A data-driven workforce management and operational performance monitoring system built to support decision-making through KPIs, reporting and process visibility.

This project simulates a real company operational environment where managers need to monitor attendance, productivity, absences and overtime in order to detect deviations and improve performance.


 🎯 Business Problem

## Organizations often manage workforce attendance and operational performance using spreadsheets or fragmented tools, which leads to:

- Lack of visibility over productivity
- Delayed identification of operational issues
- Manual reporting effort
- Data inconsistency across departments

This platform centralizes operational data and transforms it into actionable insights through dashboards and automated reports.


🧠 What This Project Demonstrates

- KPI monitoring & operational performance analysis
- Data validation & data quality control
- Process automation
- Reporting & dashboarding
- Business rules implementation
- Relational database modelling
- Decision-support analytics


 ⚙️ Core Features

### Workforce Management
- Employee records management (CRUD operations)
- Attendance tracking (work, absence, vacation, leave)
- Overtime calculation
- Absence justification tracking

### Operational Monitoring
- Monthly operational occurrence matrix
- Hours worked vs expected hours analysis
- Deviation detection

### Reporting & Analytics
- Consolidated operational reports
- Monthly attendance dashboard
- Export to Excel / CSV
- Payroll support reports


 📊 KPIs Tracked

- Total worked hours
- Overtime hours
- Absence rate
- Vacation usage
- Attendance consistency
- Operational deviations


🗄️ Data Architecture

Relational database designed to simulate a real ERP operational dataset:

Tables include:
- Employees
- Daily Records
- Absences
- Vacations
- Occurrence Types
- Overtime Balances

Ensures:
- Referential integrity
- Historical tracking
- Data consistency


🛠️ Tech Stack

**Frontend**
- Streamlit

**Backend**
- Python

**Data Processing**
- Pandas
- Business rules logic

**Database**
- Microsoft SQL Server
- Azure SQL Database
- PyODBC connection

**Reporting**
- Excel export (XlsxWriter)
- PDF generation (ReportLab)

**Version Control**
- Git & GitHub


🔄 Data Pipeline Flow

1. User inputs operational data
2. Data validated and stored in SQL database
3. Business rules applied
4. KPIs calculated
5. Dashboard updated
6. Reports generated


🚀 How to Run

git clone https://github.com/suvgoncalves/workforce-operations-kpi-monitoring
cd workforce-operations-kpi-monitoring
pip install -r requirements.txt
streamlit run app.py


🔮 Roadmap (Planned Enhancements)

- Role-based access control (RBAC)
- Automated anomaly detection for attendance deviations
- Predictive absence and overtime forecasting
- Power BI integration for executive dashboards
- Automated email alerts for operational risks


👩‍💻 About the Author

Susana Gonçalves  
Junior Operations & Performance Analyst

Specialized in operational analytics, KPI monitoring and process optimization.
Focused on transforming operational data into actionable business insights.


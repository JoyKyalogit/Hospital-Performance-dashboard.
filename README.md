

# Hospital Operations & Financial Analytics Dashboard
A multi-layered Power BI solution designed to provide healthcare administrators with a 360-degree view of hospital performance, staff productivity, and financial debt status.

## Dashboards Overview
### 1. Hospital Performance Dashboard
This high-level executive view tracks the primary KPIs of the facility.

KPIs: Monitors Total Appointments (1,006), Total Outstanding Balance ($2.59M), and average Cancellation Rate (0.33%).

Specialization Split: A donut chart showing the distribution of patients across Oncology, Orthopedics, Pediatrics, Cardiology, and Neurology.

Financial Comparison: A stacked bar chart comparing Paid Amounts vs. Outstanding Balances by year.

### 2. Doctor Productivity Dashboard
Focused on human resource efficiency and individual performance metrics.

Top Performers: A bar chart ranking doctors by total completed appointments.

Cancellation Analysis: A scatter plot correlating total appointments with cancellation rates across specializations to identify operational bottlenecks.

Status Tracking: Ability to filter data by appointment status (Cancelled, Completed, or Scheduled).

### 3. Debt Status Analysis Dashboard
A granular look at the hospital’s revenue cycle and accounts receivable.

Billing Trends: Line charts showing the relationship between Billed Amounts and Outstanding Balances over time.

Patient Ledger: A detailed table listing billed amounts and debt per patient (e.g., John, Alice, Alex).

Debt Treemap: A visual breakdown of outstanding balances by month to identify seasonal payment trends.

# Tech Stack
Tool: Power BI Desktop

Data Source: Hospital Management System (SQL/Excel)

Languages: DAX (for measures) and Power Query (M) for data cleaning.

#  Key Features
Dynamic Filtering: Use the "Doctor FullName," "Specialization," and "Status" slicers to drill down into specific data points.

Temporal Analysis: Integrated year/month sliders (2021–2025) to track growth and decline trends.

Cross-Visual Filtering: Clicking on a specific doctor or department updates all related charts instantly for deep-dive analysis.

 Business Impact
Reduced Revenue Leakage: By identifying high cancellation rates in specific specializations (e.g., Pediatrics), management can implement reminder systems.

Improved Collections: The Debt Dashboard allows the finance team to target specific high-balance patients and months for collections.

Resource Optimization: Visualization of appointment volume helps in adjusting doctor shifts based on departmental demand.

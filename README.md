# HAL MRO Fleet Reliability & Predictive Maintenance Project

### Project Overview
An end-to-end data engineering pipeline designed for the HAL MRO division to calculate the Remaining Useful Life (RUL) of aircraft components using the NASA C-MAPSS dataset.

### Tech Stack Deployed
* **Database:** MySQL (Advanced CTEs & Virtual Views)
* **Automation:** Python 3 (Pandas & SQLAlchemy connection management)
* **Business Intelligence:** Power BI Desktop (Dynamic slicing & custom conditional UI mapping)

### How to Run the Pipeline
1. Execute the script inside `/sql/database_setup.sql` to initialize the data schema.
2. Run the Jupyter Notebook inside `/notebooks/` to check database pipeline status.
3. Open `/dashboards/Fleet_Reliability.pbix` to view live telemetry updates.
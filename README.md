# Aviation Turbofan Predictive Maintenance Pipeline

### Project Overview
An end-to-end data engineering and predictive analytics pipeline designed to calculate the Remaining Useful Life (RUL) of commercial aircraft turbofan engines. Using high-fidelity sensor simulation data, the framework processes raw telemetry, applies temporal feature engineering, and deploys an advanced machine learning model to optimize fleet maintenance scheduling.

### Tech Stack Deployed
* **Database Engine:** MySQL (Advanced CTEs & Virtual Views)
* **Predictive AI:** Python 3 (XGBoost Regressor, Pandas, & SQLAlchemy)
* **Business Intelligence:** Power BI Desktop (Dynamic slicing & custom risk UI mapping)

### Key Features
* **Temporal Engineering:** Extracts rolling means and standard deviations to capture sensor signal volatility.
* **XGBoost Regression:** Achieves a highly robust baseline prediction curve tracking physical wear-and-tear trends.
* **Executive Cockpit:** Interactive dashboard displaying actual asset countdown metrics right next to live AI estimates.

### How to Run the Pipeline
1. Execute the script inside `/sql/database_setup.sql` to initialize the relational schema.
2. Run the Jupyter Notebook inside `/notebooks/` to process telemetry and update the ML model.
3. Open `/dashboards/Fleet_Reliability.pbix` to visualize live asset updates.

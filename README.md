💊 **Clinical Trial Performance & Adherence Monitoring System**
**Actionable Insights for Trial Managers to Boost Enrollment and Retention**
A comprehensive project utilizing **data analysis, machine learning, and a modern web dashboard** to optimize the management of multi-site clinical trials. This system provides trial managers with real-time visibility into recruitment funnels, site performance, and a predictive model to flag patients at high risk of dropping out.

✨ **Key Features**
This project delivers a full-stack solution to address critical pain points in clinical trial management:
**Recruitment Funnel Visualization:** Track the patient journey from Screened to Enrolled to Randomized with clear performance metrics like Screen Pass Rate and Enrollment Velocity.
**Site Performance Leaderboard:** Benchmark sites against key performance indicators (KPIs) like enrollment count and data completeness to identify top performers and areas needing intervention.
**Patient Adherence Dashboard:** Monitor vital metrics, including Medication Adherence % and Missed Visits, to proactively flag "at-risk" patients and improve retention strategies.
**Predictive Dropout Modeling:** A machine learning pipeline developed in the accompanying notebook uses patient demographics and early trial data to predict the likelihood of patient dropout, driving timely intervention.
**Secure & Scalable Architecture:** Built on a modern, robust tech stack (React and FastAPI) designed for multi-site data integration and real-time updates.

📁 **Project Structure**
This repository is organized to clearly separate the data, analysis, and application components.

├── data/
│   └── clinical_trial_dataset.csv  # Raw clinical trial data
├── notebooks/
│   └── Clinical Trail EDA.ipynb    # Data cleaning, EDA, Feature Engineering, and Dropout ML Modeling
├── dashboard/
│   ├── frontend/                   # React application for the dashboard
│   └── backend/                    # FastAPI server and API endpoints
├── docs/
│   ├── Clinical Trail Dashboard.pdf # Screenshots and key visualizations from the final dashboard
│   └── Project_Report_Template.pdf  # Detailed project report, objectives, and architecture
└── README.md

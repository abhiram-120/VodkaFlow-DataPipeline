VodkaFlow-DataPipeline
A mock data engineering project simulating an end-to-end ETL pipeline using Python, SQL, and Streamlit
🧪 VodkaFlow: A Mock Data Engineering Pipeline 🍾

This project simulates a full data pipeline — from raw CSV ingestion to data transformation, loading into a database, and visualization through Streamlit.

Tech Stack
- Python (Pandas, NumPy)
- PostgreSQL (or SQLite for local)
- Apache Spark (optional upgrade)
- Streamlit for Dashboard
---
 Pipeline Stages

1. Extract – Raw CSV files are read using Python
2. Transform – Data cleaning & aggregation with Pandas
3. Load– Store the clean data in PostgreSQL
4. Visualize – Use Streamlit to plot sales KPIs

📂 Folder Structure




⚙️ How to Run
VodkaFlow-DataPipeline/ ├── data/ │ └── sales_data.csv ├── scripts/ │ └── etl_pipeline.py ├── dashboard/ │ └── streamlit_app.py ├── requirements.txt └── README.md
```bash


pip install -r requirements.txt
python scripts/etl_pipeline.py
streamlit run dashboard/streamlit_app.py



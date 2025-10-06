📊 Vendor-Based Performance Analysis Dashboard

A comprehensive data analytics project designed to assess and visualize vendor performance based on sales data. This solution streamlines the analysis of vendor-wise sales, returns, discounts, and profit margins, enabling data-driven decision-making for procurement and vendor management teams.

🚀 Features

✅ Automated Data Ingestion from CSV files

🧹 Data Cleaning & Preprocessing using Pandas

🗂️ Vendor Summary Generation with custom KPIs

📊 Interactive Power BI Dashboard with filters for vendor, date range, and location

🔍 Visual Insights:

Top-performing vendors

Monthly/quarterly sales trends

Impact of discounts & returns

Profit margin comparisons

🛠️ Tech Stack
Layer	Tools & Technologies
Data Handling	Pandas, NumPy, SQLite3
Backend Scripting	Python
Dashboarding	Power BI
Logging & Debugging	Python logging module
File I/O	CSV ingestion with os.listdir()
📁 Project Structure
vendor-performance-analysis/  
├── data/                   # Raw sales CSV files  
├── cleaned_data/           # Cleaned vendor-wise datasets  
├── scripts/  
│   ├── ingestion_db.py     # Loads raw data into SQLite DB  
│   ├── summary_generator.py # Generates vendor summary  
│   └── clean_data.py       # Cleans and prepares data  
├── dashboard/              # Power BI / Tableau files  
├── inventory.db            # SQLite database file  
└── README.md               # Project documentation  

📊 Vendor-Based Performance Analysis Dashboard
A comprehensive data analytics project designed to assess and visualize vendor performance based on sales data. This dashboard streamlines the analysis of vendor-wise sales, returns, discounts, and margins, enabling data-driven decision-making for procurement and vendor management teams.

🚀 Features
✅ Automated Data Ingestion from CSV files
🧹 Data Cleaning & Preprocessing using Pandas
🗂️ Vendor Summary Generation with custom KPIs
📊 Interactive Dashboard with filters for vendor, date range, and location
🔍 Visual Insights:
Top-performing vendors
Monthly/quarterly trends
Discount & return impact
Profit margin comparisons
🛠️ Tech Stack
Layer	Tools & Technologies
Data Handling	Pandas, NumPy, SQLite3
Backend Scripting	Python
Dashboarding	Power BI
Logging & Debugging	logging module
File I/O	CSV file ingestion with os.listdir()
📁 Project Structure
vendor-performance-analysis/ ├── data/ # Raw sales CSV files ├── cleaned_data/ # Cleaned vendor-wise datasets ├── scripts/ │ ├── ingestion_db.py # Loads raw data into SQLite DB │ ├── summary_generator.py # Generates vendor summary │ └── clean_data.py # Cleans and prepares data ├── dashboard/ # Power BI / Tableau files ├── inventory.db # SQLite database file ├── README.md

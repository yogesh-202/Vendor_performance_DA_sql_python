# Inventory Analysis Project

## Overview
A comprehensive data analysis project focused on inventory management, sales tracking, and vendor performance analysis using Python and SQL.

## Project Structure
```
Inventory_project/
│
├── data/                      # Data directory (not tracked)
│   ├── begin_inventory.csv    
│   ├── end_inventory.csv      
│   ├── purchases.csv          
│   ├── sales.csv             
│   ├── purchase_prices.csv    
│   └── vendor_invoice.csv     
│
├── notebooks/
│   ├── create_sqlite_db.ipynb     # Database creation and ETL
│   ├── Analysis_using_SQL.ipynb   # SQL-based analysis
│   └── Analysis_using_Python.ipynb # Python-based analysis
│
└── inventory_db.db           # SQLite database (not tracked)
```

## Technologies Used
- Python (pandas, numpy)
- SQL (SQLite)
- Jupyter Notebooks
- Git/GitHub

## Setup
1. Clone the repository
2. Create a virtual environment (recommended)
3. Install required packages:
```bash
pip install pandas numpy jupyter sqlite3
```

## Data Pipeline
1. **Data Ingestion**: CSV files containing inventory, sales, and purchase data
2. **Database Creation**: Using SQLite for data storage
3. **Analysis**: 
   - SQL queries for data aggregation
   - Python for statistical analysis and visualization

## Analysis Components
- Inventory turnover analysis
- Sales performance tracking
- Purchase price variations
- Vendor invoice reconciliation

## Notes
- Large data files and database are not tracked in version control
- See individual notebooks for detailed analysis steps

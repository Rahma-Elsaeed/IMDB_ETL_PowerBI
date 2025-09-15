# IMDB_ETL_PowerBI
## Overview
This project scrapes the IMDb Top 250 movies, transforms the data, and loads it into SQL Server. 
A Power BI dashboard is created for visualization and analysis.

## Project Structure
├── Extract.ipynb           # Notebook to extract IMDb Top 250 movies data

├── Transform.ipynb         # Notebook to clean and transform the extracted data

├── Load.ipynb              # Notebook to load transformed data into SQL Server

├── IMDb_dashboard.pbix     # Power BI dashboard for data visualization

└── README.md               # Project documentation

## Usage
1. Run Extract.ipynb to scrape the data from IMDb.
2. Run Transform.ipynb to clean and format the data.
3. Run Load.ipynb to load the data into SQL Server.
4. Open IMDb_dashboard.pbix in Power BI to explore the visualizations.

## Requirements
- Python 3.x
- Libraries: pandas, selenium, sqlalchemy, pyodbc
- Power BI Desktop
- SQL Server (local or remote)

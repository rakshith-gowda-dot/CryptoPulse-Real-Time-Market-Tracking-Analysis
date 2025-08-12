# Cryptocurrency Price Tracking & Analysis

In this data engineering and analytics project, I developed a Python-based automated pipeline to track, store, and analyze real-time cryptocurrency market data using the CoinMarketCap REST API.

The system fetches updated price data every 10 minutes, processes and validates it, stores it in CSV format, and connects it to a Power BI dashboard for interactive visualizations and trend monitoring.
<img width="1911" height="904" alt="Screenshot 2025-08-12 234754" src="https://github.com/user-attachments/assets/9beb4d2e-f9a0-48c9-82c5-50fe937da979" />
<img width="1409" height="889" alt="Screenshot 2025-08-12 235452" src="https://github.com/user-attachments/assets/eb359ac7-0c42-4153-804c-b3ab907f3a91" />
<img width="864" height="642" alt="Screenshot 2025-08-12 235511" src="https://github.com/user-attachments/assets/1cb0d329-54f8-4ade-b034-5dcbc8497c45" />
<img width="1902" height="970" alt="Screenshot 2025-08-12 234702" src="https://github.com/user-attachments/assets/94cb6909-f316-4d1e-8235-7656f56d31e4" />




---

## Objective

To design and implement a robust data pipeline that:
- Fetches real-time cryptocurrency price data from the CoinMarketCap API  
- Cleans, normalizes, and validates data for accuracy  
- Stores datasets for long-term analysis  
- Integrates with visualization tools for real-time insights  

---

## Tools & Technologies Used

- **Python** – API integration, data processing, and automation  
- **CoinMarketCap API** – Real-time cryptocurrency data source  
- **Pandas** – Data cleaning, preprocessing, and trend analysis  
- **Matplotlib & Seaborn** – Data visualization and pattern identification  
- **Power BI** – Interactive dashboard for insights  
- **OS & Datetime Modules** – Automated file storage with timestamped CSVs  

---

## Dataset Summary

The dataset includes:
- Cryptocurrency Name & Symbol  
- Market Rank  
- Current Price (USD)  
- Percentage Change (24h, 7d, etc.)  
- Market Capitalization  
- Total Supply & Circulating Supply  
- Data Retrieval Timestamp  

Data was pulled every 10 minutes, normalized, and stored with unique filenames for time-series tracking.

---

## Key Features

| Feature | Description |
|---------|-------------|
| **Automated API Calls** | Fetches cryptocurrency prices every 10 minutes |
| **Data Validation** | Handles API errors, timeouts, and redirects |
| **Historical Tracking** | Saves timestamped CSV files for each run |
| **Trend Analysis** | Identifies price fluctuations and anomalies |
| **Real-Time Dashboards** | Power BI integration for live monitoring |

---

## What I Learned

- Implementing API requests and handling exceptions in Python  
- Using Pandas for real-time data cleaning and normalization  
- Storing and managing time-series data for analysis  
- Integrating Python pipelines with BI tools like Power BI  
- Automating repetitive data retrieval and storage tasks  

---

## About Me

Passionate about turning data into actionable insights.  
Combining technical expertise in Python, SQL, and visualization tools with problem-solving skills to deliver impactful solutions.

**GitHub**: [github.com/rakshith-gowda-dot](https://github.com/rakshith-gowda-dot)  
**LinkedIn**: [linkedin.com/in/rakshith-n-81b34329a](https://www.linkedin.com/in/rakshith-n-81b34329a/)

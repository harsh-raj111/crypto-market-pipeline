# 🪙 Crypto Market Data Pipeline & Dashboard

> An end-to-end automated data engineering pipeline 
> that extracts live cryptocurrency data from 
> CoinMarketCap API, transforms it using Python & 
> Pandas, stores it in MySQL, and visualizes it 
> through an interactive Power BI dashboard.

---

## 🏗️ Pipeline Architecture

CoinMarketCap API
       ↓
  Python + Requests
  (Data Extraction)
       ↓
    Pandas
  (Clean & Transform)
       ↓
    MySQL
  (Data Storage)
       ↓
   Power BI
 (Dashboard)
       ↓
Task Scheduler
 (Daily Automation)

---



---

## ✅ Features

- Live extraction of top 100 cryptocurrencies
- Automated ETL pipeline
- MySQL relational database storage
- Interactive Power BI dashboard
- Daily automation via Task Scheduler

---

## 📈 Dashboard Visuals

| Visual | Description |
|--------|-------------|
| KPI Cards | Market Cap, Total Coins, Highest Price, Average Price, Volume 24h |
| Bar Chart | Top 10 coins by Market Cap |
| Bar Chart | Top 10 coins by Volume 24h |
| Price Change | Red/Green conditional chart |
| Pie Chart | Crypto market dominance |
| Slicer | Filter by crypto name |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Extraction & scripting |
| Requests | API calls |
| Pandas | Data cleaning |
| CoinMarketCap API | Live data source |
| MySQL | Database storage |
| Power BI | Visualization |
| Task Scheduler | Automation |

---

## 📁 Project Structure

crypto-market-pipeline/
│
├── 📁 scripts/
│   └── stock.ipynb          # ETL pipeline notebook
│
├── 📁 dashboard/
│   └── crypto_dashboard.png # Dashboard screenshot
│
├── 📁 data/
│   └── sample_data.csv      # Sample output
│


---

## ⚙️ How to Run

 1. Clone the repo
bash
git clone https://github.com/harsh-raj111/crypto-market-pipeline.git
cd crypto-market-pipeline

2. Install dependencies
bash
pip install -r requirements.txt

 3. Add your API key
python

# Get free key at coinmarketcap.com

4. Set up MySQL
bash
# Run in MySQL Workbench
source sql/create_table.sql

 5. Run the pipeline
bash
# Open stock.ipynb in VS Code
# Run All cells

 6. Open Power BI
Open Power BI Desktop
Connect to MySQL database
Click Refresh

---

 Automation

6:00 AM → Task Scheduler runs pipeline
6:05 AM → MySQL updated with fresh data  
6:30 AM → Power BI refreshes
7:00 AM → Dashboard ready ✅

---

 Key Insights

- Bitcoin holds **69.85%** market dominance
- Tether USDt leads **24h trading volume**
- Total market cap: **$2.37 Trillion**
- **100 cryptocurrencies** tracked live

---

 Requirements

requests
pandas
mysql-connector-python
python-dotenv

---

 Skills Demonstrated

- REST API integration
- ETL pipeline design
- Data cleaning with Pandas
- SQL database management
- Data visualization
- Pipeline automation

---

👤 Author

Harsh Raj
Data Analyst | Python • SQL • Power BI | ETL Pipelines

[LinkedIn]:https://www.linkedin.com/in/harsh-raj-335b94222?utm_source=share_via&utm_content=profile&utm_medium=member_android
[[GitHub]:https://github.com/harsh-raj111

---


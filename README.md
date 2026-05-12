# Eco-Grid: Smart Energy Analytics System

Eco-Grid is a data engineering project built using PySpark and Databricks to simulate and analyze smart electricity grid data using a multi-layer architecture.

---

## 🚀 Project Overview
This project processes smart meter data and generates insights for energy usage, theft detection, and system maintenance.

---

## 🧱 Architecture
- **Bronze Layer** → Raw JSON data ingestion  
- **Silver Layer** → Data cleaning and transformation  
- **Gold Layer** → Aggregated insights for dashboard  

---

## ⚙️ Features
- Real-time smart meter data simulation  
- Electricity theft detection (usage-based logic)  
- Predictive maintenance (voltage analysis)  
- Eco-score classification (GREEN, YELLOW, RED)  
- Geo-spatial analysis using latitude & longitude  
- Dashboard visualization (bar, pie, scatter charts)

---

## 🛠 Tech Stack
- PySpark  
- Databricks  
- Delta Lake  
- SQL  

---

## 📊 Sample Output
- Usage analysis chart  
- Eco score distribution  
- Theft detection insights  
- Geo-based consumption visualization  

---

## 📌 Key Learnings
- End-to-end data pipeline design  
- Working with distributed data using Spark  
- Data transformation and aggregation  
- Building business logic for real-world use cases  


## 📁 Project Structure

eco_grid_smart_energy/
│
├── 📓 eco_grid notebook.ipynb      # Main pipeline notebook
│   ├── 🥉 Bronze Layer             # Raw JSON data ingestion & simulation
│   ├── 🥈 Silver Layer             # Data cleaning & transformation
│   └── 🥇 Gold Layer               # Aggregated insights & business logic
│
└── 📄 README.md                    # Project documentation

---

## 🔑 Key Features

- ⚡ Real-time smart meter data simulation
- 🔍 Electricity theft detection (usage-based logic)
- 🔧 Predictive maintenance (voltage analysis)
- 🌿 Eco-score classification (GREEN, YELLOW, RED)
- 🗺️ Geo-spatial analysis using latitude & longitude

---

## 🧰 Tech Stack

| Tool | Purpose |
|------|---------|
| PySpark | Distributed data processing |
| Databricks | Cloud execution environment |
| Delta Lake | Layered data storage |
| SQL | Data querying & aggregation |
| Matplotlib/Plotly | Visualization |

---

## 🚀 How to Run

1. Open Databricks workspace
2. Import `eco_grid notebook.ipynb`
3. Run cells sequentially (Bronze → Silver → Gold)

# 🧧 Tet 2026 Sales Analytics & Forecasting Dashboard

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF9D00?style=for-the-badge&logo=gradio&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

## 📌 Project Overview
This project provides a comprehensive data-driven perspective on consumer behavior during the peak Lunar New Year (Tet) season in 2026. By integrating transaction data with predictive modeling, the system delivers strategic insights for revenue optimization and supply chain management.

## 🎯 Key Analytics Goals
* **Demand Forecasting:** Identifying market peaks and "The Drop" between Pre-Tet and Tet phases.
* **Product Performance:** Analyzing GMV contribution by SKU (e.g., "Xuan Nhu Y" Gift Sets).
* **Operational Management:** Real-time monitoring of **Days of Supply (DOS)** to prevent stockouts.
* **Regional Comparison:** Benchmarking performance across North, Central, and South Vietnam.

## 📊 Live Interactive Dashboard
The dashboard is built using Gradio Blocks and hosted on Hugging Face Spaces for real-time interaction.
* **Link Dashboard:** [[Click here to view Dashboard](https://anhthanh-tet-sales-analytics.hf.space/)]
* **Detailed Documentation:** [(https://massive-lead-079.notion.site/Ph-n-T-ch-Hi-u-Su-t-Kinh-Doanh-D-B-o-Nhu-C-u-T-t-2026-30706f48b4d780e0b546cbd54ee9305e)]

## 📂 Data Architecture
The project utilizes a **Star Schema** within a SQLite database:
* `fact_sales`: Contains 1,000+ transaction records including dates, quantities, and regions.
* `dim_products`: Stores SKU details, categories, and pricing.
* `dim_customers`: Demographic data for customer segmentation.

## 🛠️ Tech Stack
* **Language:** Python (Pandas, Numpy).
* **Database:** SQLite3.
* **Interface:** Gradio (Blocks API).
* **Deployment:** Hugging Face Spaces.

## 🚀 Installation & Usage
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/username/tet-sales-analytics.git](https://github.com/username/tet-sales-analytics.git)

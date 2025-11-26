# 📌 Project Title  
🎁 Golden Gift Store Analysis

# 📌 Introduction  
This project analyzes two years of sales data (2023–2024) from the Golden Gift Store. The goal is to uncover actionable insights across product performance, customer behavior, and regional sales trends.

The analysis focuses on identifying:  
- Revenue and profit trends over time  
- High-performing and low-performing product categories  
- Customer purchasing patterns and contribution to sales  
- Regional and monthly performance variations  
- Opportunities for increasing revenue and improving store efficiency  

These insights help guide strategic decisions in inventory planning, marketing, and customer targeting.

## 📂 Data Cleaning & Preparation

The dataset was obtained from Kaggle datasets websites.  
During the cleaning phase, several adjustments were made to ensure the dataset was accurate and analysis-ready.

---

### 🧹 Data Cleaning Overview

| Step | Description | Action Taken |
|------|-------------|--------------|
| Removed Duplicates | Ensured each record was unique | Used `Remove Duplicates` (Power Query / Excel) |

These steps ensured the dataset was clean, consistent, and ready for visualization and model building.

---

## ⚙️ Calculated Fields & Columns Created

To support advanced analysis of sales and marketing performance, calculated columns were created.

### ➕ Calculated Columns

| Column Name | Description |
|-------------|-------------|
| **Year** | Extracted from `Order Date` to enable yearly trend analysis |
| **Month** | Extracted from `Order Date` to analyze monthly trends |
| **Profit Category** | Categorized profit values into segments (e.g., Low, Medium, High) |

---

## 🔧 Data Transformation Tools Used

During the data preparation and transformation stage, the following tools were used to clean, format, and prepare the dataset for analysis:

| Tool / Platform | Purpose | Key Actions Performed |
|-----------------|---------|---------------------|
| **Power Query (Excel)** | Initial data review and quick cleaning | Removed duplicates, checked column consistency |
| **Pivot Tables (Excel)** | Data summarization and exploration | Aggregated revenue, units sold, and marketing spend |
| **Microsoft Excel** | Data visualization | Created calculated columns and KPIs |
| **GitHub** | Version control and documentation | Stored cleaned dataset and project documentation |

---

These tools helped streamline **data ingestion, cleaning, transformation, and visualization** across the entire analysis process.



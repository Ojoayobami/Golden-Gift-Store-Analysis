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
| **Pivot Tables (Excel)** | Data summarization and exploration | Aggregated revenue, total profits, quantity sold and total unit price |
| **Microsoft Excel** | Data visualization | Created calculated columns and KPIs |
| **GitHub** | Version control and documentation | Stored cleaned dataset and project documentation |

---

These tools helped streamline **data ingestion, cleaning, transformation, and visualization** across the entire analysis process.

## 🔍 Exploratory Data Analysis (EDA)

After cleaning and transforming the dataset, an exploratory data analysis was carried out to understand overall performance, customer behaviour, and revenue contribution across all regions, products, and sales channels.

### ✅ Key EDA Steps

| Analysis Performed                  | Purpose / Insight Gained |
|------------------------------------|--------------------------|
| **Descriptive Statistics Overview** | Identified YoY changes across Revenue, Profit, Unit Price, and Quantity. |
| **Regional Performance Review**     | Compared contribution of East, West, Central, and South regions to overall sales. |
| **Product Category Deep-Dive**      | Highlighted top-performing categories and revealed Electronics as the strongest line. |
| **Customer Leaderboard Analysis**   | Ranked customers by revenue to identify Michael Smith as the top buyer. |
| **State-Level Contribution Mapping**| Determined high-value locations, with California emerging as the leading state. |
| **Monthly Trend Visualization**     | Tracked monthly revenue and quantity changes to reveal growth patterns. |

### 📊 Insights Uncovered

- Business performance improved by **+1% YoY** across major KPIs.  
- **Electronics** remained the strongest product category in revenue, while **Clothing & Apparel** remained the strongest in quantity sold, and **Home and Furniture** remained the strongest in profit.  
- The **East Region** contributed the highest share of revenue and profit across all regions.  
- **California** ranked as the top-performing state by total revenue and total profit.  
- **Michael Smith** emerged as the highest-value customer for the period.  
- Overall, the business is growing steadily, with consistent performance across months.  

These insights formed the foundation for the final visualizations and strategic recommendations.

## 📊 Statistical Analysis

Statistical analysis was conducted to understand the relationships between key metrics such as Revenue, Profit, Unit Price, and Quantity. This helped identify patterns, trends, and factors influencing business performance.

### ✅ Key Statistical Analysis Steps

| Analysis Performed                  | Purpose / Insight Gained |
|------------------------------------|--------------------------|
| **Correlation Analysis**            | Measured the strength and direction of relationships between Revenue, Profit, Unit Price, and Quantity. |
| **Year-over-Year (YoY) Comparison**| Quantified changes in Revenue, Profit, Unit Price, and Quantity to track business growth. |
| **Descriptive Statistics**          | Calculated total values (Revenue, Profit, Unit Price and Quantity). |
| **Top Customer & Product Analysis** | Identified which customers and products contributed most significantly to revenue and profit. |
| **Regional Performance Metrics**    | Analyzed metrics by region to identify high-performing and underperforming areas. |

### 📈 Insights Uncovered

- Revenue and Profit showed a **strong positive correlation**, confirming that higher sales directly impacted profitability.  
- YoY performance improved by **+1%** across all major KPIs.  
- Electronics emerged as the **top-performing product category**, contributing the highest revenue.  
- The **East Region** continued to lead in overall revenue and profit, followed by West and South regions.  
- Michael Smith remained the **highest-value customer**, driving a notable portion of total revenue.  
- Statistical trends supported the business’s steady growth and validated strategic focus areas.

These findings informed further visualization, reporting, and data-driven strategic decisions.

## 🚀 Executive Summary

The business is growing steadily, showing **+1% YoY improvement** across all major KPIs (Revenue, Profit, Unit Price, Quantity).  
Performance is strongest in **Electronics**, **East Region**, and **California**, with **Michael Smith** remaining the top customer.

---

### 📊 Overall Performance (YoY Key Metrics)

| Metric          | Current Year (CY) | Previous Year (PY) | YoY Change |
|-----------------|-----------------|------------------|------------|
| Revenue         | $71,652,372     | $70,755,373      | ▲ +1%      |
| Profit          | $15,869,646     | $15,678,962      | ▲ +1%      |
| Unit Price      | $38,452,227     | $38,118,896      | ▲ +1%      |
| Quantity Sold   | 186,191         | 184,609          | ▲ +1%      |

➡️ **Insight:** Business is healthy and stable with controlled growth—revenue and profit rising at the same pace signals consistent pricing and solid demand.

---

### 📈 Monthly Trend Insights

- **November** is the top month for revenue and profit.  
- Both metrics show a sharp upward jump in Q4, indicating:
  - Holiday season demand  
  - Promotional/discount-driven sales  
  - Strong year-end purchasing behavior  

➡️ **Insight:** Business should double down on Q4 marketing — peak revenue period.

## 🧠 Insights & Recommendation

## 📊 Insights

### 🌎 Regional Performance Insights

- **Top Region: East**  
  - Revenue: $44.98M  
  - Profit: $9.22M  
  - Consistently outperforms other regions by a large margin  

- Other Regions:  
  - West and Centre perform moderately well  
  - South is the lowest performer  

➡️ **Insight:** East drives overall business success — potential for deeper market penetration or premium product push.  
➡️ **Opportunity:** South region can improve through local promotions and distribution optimization.

---

### 🏙️ State Performance Insights

- **Top State: California** (Western state)  
  - Revenue: $6.7M  
  - Profit: $1.56M  
- Followed closely by Arizona (also a Western state)  

➡️ **Insight:** While the East Region leads overall revenue, California is the single highest-performing state. Western states remain high-value territories for strategic focus.

---

### 🛒 Customer Insights

- **Top Customer: Michael Smith**  
  - Revenue contribution: $76,415  
- Other top customers:  
  - Michael Williams, Michael Johnson, Christopher Smith, David Smith  

➡️ **Insight:** High-value customers belong to similar demographic clusters (similar names, possibly same region). Retention programs here would be effective.

---

### 🛍️ Product Category Insights

| Category           | Revenue       | Profit       | Quantity Sold |
|-------------------|---------------|-------------|---------------|
| Electronics       | $57.48M       | $8.06M      | 97,115 units  |
| Home & Furniture  | $47.67M       | $11.22M     | 90,403 units  |
| Clothing & Apparel| $27.13M       | $8.83M      | 115,523 units |
| Accessories       | Lowest        | Lowest      | Lowest        |

➡️ **Insights:**  
- Electronics drives revenue  
- Home & Furniture generates highest profit per unit
- Clothing & Apparel drives quantity sold
- Accessories underperform significantly  

---

### 🏙️ City-Level Insights

- **Top Cities by Revenue:**  
  - Wilmington — $2.31M  
  - Providence — $2.29M  
  - Burlington — $2.37M  
  - Manchester — $2.31M  
  - Rochester — $2.31M  

- **Top Cities by Profit:**  
  - Burlington — $471K  
  - Manchester — $470K  
  - Rochester — $478K  

➡️ **Insight:** Northeastern cities dominate both revenue and profit.

## 🎯 Key Recommendations

### 1. Overall Performance
- **Strengthen Q4 Strategy**: Increase marketing budget for Oct–Dec, launch holiday bundles, flash sales, loyalty rewards, and expand inventory for high-demand items.  
- **Improve Underperforming Regions (South)**: Run region-specific promotions, strengthen distributor/retailer relationships, and resolve logistics issues.  
- **Optimize Customer Retention**: Introduce VIP programs, personalized offers, early access sales, and upsell recommendations for top customers.

### 2. Revenue Growth
- **Expand High-Performing Regions (East & West)**: Launch premium products, targeted ads, influencer partnerships, and add pickup/micro-fulfillment points.  
- **Increase Average Order Value**: Use volume discounts, cross-selling, and product bundles.  
- **Diversify Customer Base**: Target mid-tier customers, re-engage inactive ones, and run referral promotions.  
- **Strengthen Repeat Purchases**: Automated remarketing emails, loyalty points, subscription or replacement reminders.

### 3. Product Performance
- **Electronics**: Prioritize volume, introduce new variants, offer bulk incentives, partner with suppliers for exclusive deals.  
- **Home & Furniture**: Promote for profit, market as premium line, offer extended warranties/assembly services.  
- **Accessories**: Redesign or bundle with other products, adjust pricing, reduce underperforming Stock Keeping Unit.  
- **Stock Management**: Prevent Electronics stock-outs during Q4; manage Accessories to avoid overstock.

### 📌 High-Level Takeaways
- Invest in **Q4 marketing** — peak revenue period.  
- Focus on **East & West regions** for expansion.  
- Promote **Home & Furniture** for profitability, **Electronics** for volume.  
- Retain top customers via personalized loyalty programs.  
- Reduce reliance on **Accessories** unless redesigned or bundled.

## Main Dashboard

<img width="6055" height="2969" alt="image" src="https://github.com/user-attachments/assets/3b54f30d-edc0-4dd9-9fe9-697fefe95238" />

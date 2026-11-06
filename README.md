# 📊 Retail Sales & Supply Chain Performance Dashboard

An interactive, multi-tab Excel dashboard designed to evaluate retail sales performance, regional profitability, customer segment distribution, and the margin impact of promotional discounting across 9,900+ transactions.

---

## 🚀 Key Features & Insights

### **Tab 1: Executive Overview**
* **High-Level Metrics:** Real-time tracking of **Total Sales (₹2.30M)**, **Total Profit (₹286.4K)**, **Profit Margin (12.47%)**, and **Total Quantity Sold (37,843)**.
* **Temporal & Category Trends:** Evaluates year-over-year growth trajectories and identifies **Technology** as the highest-grossing category (₹836K Sales | ₹145K Profit).
* **Regional Breakdown:** Analyzes performance across Central, East, South, and West regions, highlighting the West as the top revenue generator (₹725K Sales).

### **Tab 2: Deep-Dive Analytics & Customer Segmentation**
* **Customer Segment Distribution:** Identifies the **Consumer segment** as the primary revenue driver, contributing **50.5% of total sales** (₹1.16M Sales | ₹134K Profit).
* **Discount Toxicity Analysis:** Uncovers a critical operational leak—demonstrating that promotional discounts **exceeding 20% enter negative net profitability** (incurring losses up to -₹86k at 60%+ discounts).
* **Product Margin Highlights:** Pinpoints high-margin sub-categories like **Paper & Labels** delivering >40% margins.

---

## 🛠️ Data Architecture & Tools Used
* **Data Modeling:** Built on a structured relational model linking transactional data to a dedicated Date/Calendar Dimension Table.
* **Advanced Excel Features:** 
  * Advanced **PivotTables & PivotCharts** for dynamic aggregation.
  * **Interactive Slicers** for real-time filtering by Region and Period (2014–2017).
  * Custom KPI summary cards and clean ETL data-cleaning workflows.

---

## 📷 Dashboard Preview

### **Executive Overview (Tab 1)**
<img width="1075" height="532" alt="image" src="https://github.com/user-attachments/assets/8e0be161-5a49-4540-8efc-d83969a091f6" />


### **Customer Segments & Discount Profitability (Tab 2)**
<img width="1002" height="448" alt="image" src="https://github.com/user-attachments/assets/83808f8c-8f10-46b9-ab41-d1e15ee98338" />


---

## 📂 Repository Structure
```text
├── Data/                   # Cleaned underlying dataset (Superstore dataset)
├── Dashboard/              # Final .xlsx workbook containing both dashboard tabs
└── README.md               # Project documentation

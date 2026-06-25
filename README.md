# 🛒 Blinkit Grocery Sales Dashboard — Power BI

> An end-to-end **Power BI analytics dashboard** built on Blinkit's grocery sales data — designed to help business teams track sales performance, outlet trends, and product-level insights at a glance.

---

## 📌 Project Overview

Blinkit (formerly Grofers) is India's leading instant grocery delivery platform. This dashboard transforms raw grocery transaction data into actionable visual insights for **sales analysts, category managers, and business stakeholders**.

The goal is to replace scattered spreadsheet reporting with a **single, interactive dashboard** that answers key business questions in seconds.

---

## 📊 Dashboard Pages

### 1. Sales Overview
- Total Sales, Average Sales, Number of Items, Average Rating — KPI cards
- Sales breakdown by **Fat Content** (Low Fat vs Regular)
- **Item Type** wise sales distribution
- Sales trend by **Outlet Establishment Year**

### 2. Outlet Analysis
- Sales comparison by **Outlet Size** (Small / Medium / High)
- Performance breakdown by **Outlet Location Type** (Tier 1 / Tier 2 / Tier 3)
- **Outlet Type** wise — Total Sales, Avg Sales, No. of Items, Avg Rating, Item Visibility

### 3. Product Insights
- Top performing **Item Types** by sales volume
- Fat Content analysis across outlet tiers
- Item visibility vs sales correlation

---

## 🗂️ Files in This Repository

| File | Description |
|------|-------------|
| `Blinkit.pbix` | Main Power BI dashboard file |
| `BlinkIT Grocery Data.xlsx` | Primary source dataset |
| `Patient_History_data.xlsx` | Supporting reference data |

---

## 📁 Dataset Details

**BlinkIT Grocery Data.xlsx** contains:

| Column | Description |
|--------|-------------|
| `Item Identifier` | Unique product ID |
| `Item Type` | Category (Fruits, Snacks, Dairy, etc.) |
| `Item Fat Content` | Low Fat / Regular |
| `Item Visibility` | Product shelf visibility score |
| `Item MRP` | Maximum Retail Price |
| `Outlet Identifier` | Unique outlet ID |
| `Outlet Size` | Small / Medium / High |
| `Outlet Location Type` | Tier 1 / Tier 2 / Tier 3 |
| `Outlet Type` | Grocery Store / Supermarket |
| `Outlet Establishment Year` | Year outlet was opened |
| `Sales` | Total sales amount |
| `Rating` | Customer rating |

---

## 🔑 Key Metrics (KPIs)

| Metric | Value |
|--------|-------|
| 💰 Total Sales | $1.20M |
| 📦 No. of Items | 8,523 |
| ⭐ Avg Rating | 3.9 |
| 📈 Avg Sales | $141 |

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard development
- **Microsoft Excel** — Data source
- **DAX** — Custom measures and KPIs
- **Power Query** — Data transformation & cleaning

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `Blinkit.pbix` in **Power BI Desktop**
3. If prompted, update the data source path to point to `BlinkIT Grocery Data.xlsx`
4. Refresh the data — all visuals will update automatically
5. Use slicers to filter by Outlet Location, Outlet Size, and Item Type

---

## 📸 Dashboard Preview

> *(Add a screenshot of your dashboard here)*
> `![Dashboard Preview](preview.png)`

---

## 👤 Author

**[Mohd Aseem]**
- 🔗 [LinkedIn Profile](https://www.linkedin.com/in/aseem-kassar-023893348/)
- 💻 [GitHub Profile](https://github.com/aseemkassar)

---

## 📄 License

This project is for **educational and portfolio purposes** only.
Data sourced from publicly available Blinkit grocery datasets.

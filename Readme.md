# 📊 Superstore Sales Dashboard

An interactive, single-file sales analytics dashboard built with HTML, CSS, and Chart.js — no frameworks, no build tools, no dependencies to install.

![Dashboard Preview](https://img.shields.io/badge/Status-Live-brightgreen) ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?logo=chartdotjs&logoColor=white) ![License](https://img.shields.io/badge/License-MIT-blue)

---

## 🔍 Overview

This dashboard visualizes Superstore retail data across sales, profit, region, product category, and customer segment dimensions. It is styled with a dark military-green theme and gold accents, and is fully interactive with live-filtering controls.

---

## 📸 Preview

> Open `sales-dashboard.html` directly in any browser — no server required.

---

## 📈 Key Metrics Displayed

| Metric | Value |
|---|---|
| Total Sales | $13M |
| Total Profit | $1.47M |
| Profit Margin | 11.62% |
| Top Category | Technology |
| Top Region | Central |

---

## 🧩 Features

- **KPI Cards** — Total Sales, Total Profit, Profit Margin with animated load-in
- **Monthly Bar Chart** — Side-by-side Sales vs Profit per month
- **Profit by Category** — Grouped bar chart (Technology, Office Supplies, Furniture)
- **Revenue by Region** — Horizontal bar chart across 13 global regions
- **Sales Trend Line** — Monthly sales trajectory with area fill
- **Customer Segments Donut** — Consumer / Corporate / Home Office breakdown
- **Category Treemap** — Visual area tiles per product category
- **Loss-Making Products Table** — Highlights sub-categories with negative profit
- **Key Insight Callout** — Flags pricing inefficiencies in high-sales, low-profit products

### 🎛 Interactive Controls

- **Month Checkboxes** (sidebar) — Select/deselect months to filter all charts and recalculate KPIs in real time
- **Region Dropdown** — Filter view by geographic region
- **Segment Dropdown** — Filter by customer segment (Consumer, Corporate, Home Office)
- **Hover Tooltips** — Formatted dollar values on every chart

---

## 🗂 File Structure

```
sales-dashboard/
└── sales-dashboard.html   # Complete dashboard — all HTML, CSS, and JS in one file
└── README.md
```

---

## 🚀 Getting Started

### View Locally

1. Clone or download this repository
2. Open `sales-dashboard.html` in any modern browser

```bash
git clone https://github.com/koskeikipngetich2-jpg/sales-dashboard.git
cd sales-dashboard
# open sales-dashboard.html in your browser
```

### View Live (GitHub Pages)

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under **Source**, select `main` branch and `/ (root)`
4. Click **Save**
5. Your dashboard will be live at:

```
https://koskeikipngetich2-jpg.github.io/sales-dashboard/sales-dashboard.html
```

---

## 🛠 Built With

| Tool | Purpose |
|---|---|
| HTML5 | Structure |
| CSS3 (custom properties, grid, flexbox) | Layout & theming |
| JavaScript (vanilla) | Interactivity & filtering |
| [Chart.js 4.4.1](https://www.chartjs.org/) | All charts (loaded via CDN) |
| [Google Fonts – Orbitron & Rajdhani](https://fonts.google.com/) | Typography |

> No npm, no build step, no framework. Just open and run.

---

## 📊 Data Source

Based on the [Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) — a widely used retail analytics dataset covering orders, products, regions, and customer segments.

---

## 💡 Key Insight

> Certain sub-categories (notably **Tables**) generate losses of **-$64,083** despite strong sales volume, indicating pricing inefficiencies that require margin review.

---

## 👤 Author

**Kipngetich Koskei**
Freelance Data Analyst

[![GitHub](https://img.shields.io/badge/GitHub-koskeikipngetich2--jpg-181717?logo=github)](https://github.com/koskeikipngetich2-jpg)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
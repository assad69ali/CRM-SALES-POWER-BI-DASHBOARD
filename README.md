# 📊 CRM Sales Opportunities Analysis — Power BI Dashboard

**Author:** Asad Ali  
**Tool:** Power BI Desktop  
**Data Source:** [Maven Analytics](https://www.mavenanalytics.io/) — CRM Sales Opportunities Dataset

---

## 📌 Table of Contents

- [About the Project](#about-the-project)
- [Dataset](#dataset)
- [Project Objectives](#project-objectives)
- [Key Metrics](#key-metrics)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Dashboard](#dashboard)
- [Repository Structure](#repository-structure)
- [Tools Used](#tools-used)
- [Contact](#contact)

---

## 📖 About the Project

A comprehensive Business Intelligence project analysing a simulated B2B CRM sales pipeline. The analysis covers sales performance, win rates, product trends, regional profitability, and revenue forecasting — all visualised through interactive Power BI dashboards.

---

## 📁 Dataset

The dataset simulates a real-world B2B sales environment with **5 interconnected tables**:

| Table | Description |
|---|---|
| `Accounts` | Customer company details — sector, revenue, employees, location |
| `Products` | Product catalogue with series (GTX, MG, GTK) and pricing |
| `Sales Teams` | Sales reps, managers, and regional office assignments |
| `Sales Pipeline` | Opportunity tracking across deal stages (Prospecting → Won/Lost) |
| `Data Dictionary` | Metadata definitions for all fields |

---

## 🎯 Project Objectives

- Analyse **sales performance** across reps, regions, and sectors
- Calculate **win rates** and identify key drivers of deal success
- Identify **top-performing products** and customer segments
- Detect **seasonal trends** and forecast future revenue
- Surface **cross-selling opportunities** to maximise deal value

---

## 📈 Key Metrics

| Metric | Value |
|---|---|
| Total Customer Companies | 85 |
| Total Sales Representatives | 35 |
| Total Closed Deals | 6,711 |
| Deals in Prospecting Stage | 500 |
| Overall Win Rate | 63% |
| Highest Net Profit Region | West ($3.21M) |
| Top Product by Revenue | GTX Plus Pro ($2.6M) |
| Forecasted Monthly Revenue | ~$934,165 |

---

## 💡 Key Insights

### 🏆 Product Performance
- **GTX family** dominates across all regions — GTX (4 products), MG (2 products), GTK (1 product)
- **GTX Plus Pro** generates the highest revenue from won deals at **$2.6M**
- **MG Advanced** follows at **$2.2M**, and **GTX Plus B** at **$0.7M**

### 🌍 Regional Performance
- **West region** leads with the highest win rate (**0.64**) and net profit (**$3.21M**)
- Central region follows at **$3.01M**, and East at **$2.78M**
- Sales reps are evenly distributed: East (12), West (12), Central (11)
- **Top sales rep:** Darcel Schlecht — **37% of deals won**
- Reps with the fastest sales cycles (e.g. Hayden Neloms, Maureen Marcano) also show the highest win rates

### 🏭 Sector Insights
- **Retail** has the most customer companies (**17**), followed by Medical and Technology (**12** each), and Finance (**8**)
- **Entertainment** sector generates the highest average revenue per deal (**$2.7K**)
- **Technology** and **Retail** sectors show the most room to improve prospecting-to-engaging conversion rates

### 📅 Seasonal Trends
- Sales **peak in March and June**; slower periods observed in **April and October**
- Revenue forecast predicts steady performance with peaks in **July–August**
- Forecasted baseline: **~$934,165/month** for the next 3 months

### 🔁 Deal Stage Progression
- Prospecting → Engaging conversion: **76%**
- Engaging → Closed conversion: **81%**
- Stage 1 → Stage 2 probability: **3.18%**; Stage 2 → Close probability: **4.22%**
- Parent companies and subsidiaries show similar average deal sizes (**~$1.5K**), but subsidiaries handle a **larger volume**

### 👥 Customer Analysis
- Companies acquired in **2016** show higher lifetime revenue and win rates vs. those from **2017**
- **Cross-sell score: 7** — multi-family customers consistently generate higher average deal values
- **GTX products** perform strongest in the **Technology** sector; **MG products** lead in **Retail** and **Marketing**

---

## ✅ Recommendations

1. **Prioritise Retail, Technology, and Medical sectors** — highest customer concentration and growth potential
2. **Replicate West region best practices** across East and Central teams to close the performance gap
3. **Launch cross-sell campaigns** targeting multi-product customers for higher average deal values
4. **Expand the GTX product line** — top performer across all regions with strong customer demand
5. **Improve prospecting conversion in Tech and Retail** through personalised, targeted outreach
6. **Align marketing campaigns with seasonal peaks** (March, June); use April and October for lead nurturing
7. **Enhance predictive models** by incorporating product preferences and customer engagement data
8. **Implement retention programmes** for newer customer cohorts (acquired 2017+) to close the revenue gap
9. **Reallocate resources to the West region** to reinforce profitability while auditing East region efficiency
10. **Target high-conversion product–sector pairings** (e.g. GTX in Tech, MG in Retail) to maximise close rates

---

## 🖥️ Dashboard

The project includes **two Power BI dashboards**:

- **Practice Dashboard** — exploratory analysis and initial visualisations (3 pages)
- **Assignment Dashboard** — final polished analysis with full insight coverage (6 pages)

Dashboard pages cover:
- Overview metrics & KPIs
- Product & customer analysis
- Deal stage progression & win probability heatmap
- Sales rep performance (win rate vs. days to close)
- Regional profitability (net profit after cost-to-sell)
- Seasonal trends & 3-month revenue forecast

---

## 📂 Repository Structure

```
📦 crm-sales-analysis
 ┣ 📂 screenshots/
 ┃ ┣ 🖼️ practice-dashboard-1.png
 ┃ ┣ 🖼️ practice-dashboard-2.png
 ┃ ┣ 🖼️ practice-dashboard-3.png
 ┃ ┣ 🖼️ assignment-dashboard-1.png
 ┃ ┗ 🖼️ ...
 ┣ 📄 WORD_REPORT.docx
 ┗ 📄 README.md
```

---

## 🛠️ Tools Used

- **Power BI Desktop** — data modelling, DAX measures, and interactive dashboards
- **Maven Analytics** — CRM Sales Opportunities dataset

---

## 📬 Contact

**Asad Ali**  
Feel free to open an issue or reach out if you have any questions about the analysis.

# 🤰 Maternal Health Analytics Dashboard – India (2024)

An interactive **Power BI dashboard** that analyzes maternal healthcare indicators across **34 States/UTs and 588 Districts** in India, using data from the **Ministry of Health & Family Welfare (NHM Health Indicator)**.

<img width="779" height="472" alt="Maternity Health Analytics Dashboard" src="https://github.com/user-attachments/assets/faa76f0e-f3b0-4188-9595-8dd3cd061859" />

---

## 📌 Project Overview

Maternal health is a key indicator of a country's healthcare system. This project analyzes **district-level maternal care data** across India to identify:
- Regions with strong maternal healthcare performance
- Districts/States that need urgent policy attention
- Gaps in the **maternal care continuum** — from pregnancy registration to post-natal care

The dashboard converts raw government survey data into a **decision-ready visual tool** for health administrators, NGOs, and researchers.

---

## 🎯 Objectives

- Track key maternal health KPIs at a national, regional, and district level
- Rank states based on institutional birth performance
- Classify districts into **risk tiers** (Excellent, Good, Watch, Critical) for targeted intervention
- Compare the 5-stage maternal care journey across regions

---

## 🗂️ Dataset

| Detail | Description |
|---|---|
| **Source** | Ministry of Health and Family Welfare (NHM Health Indicators) |
| **Level** | District-wise, aggregated to State & Region |
| **Rows** | 601 districts |
| **File** | `datafile.csv` |

**Key columns / indicators used:**
- ANC 1st Trimester Registration (%)
- Mothers with 3+ ANC (Ante-Natal Care) Visits (%)
- TT (Tetanus Toxoid) Injection Coverage (%)
- Institutional Births (%)
- Home Delivery Assisted by Medical Staff (%)
- Postnatal Care (PNC) within 48 hrs (%)

> Missing values (`NA`) were handled during data cleaning in Power Query before building the model.

---

## 🛠️ Tools & Techniques Used

- **Power BI** – Data modeling, DAX measures, interactive report design
- **Power Query (M)** – Data cleaning, handling blanks/NA, region mapping
- **DAX** – Custom measures for averages, rankings, and risk-tier classification
- **Excel** – Initial data exploration and validation
- **Filled Map Visual** – Geographic view of institutional births by region

---

## 📊 Dashboard Features

**1. KPI Summary Cards**
Total States, Total Districts, Average Institutional Births, ANC Registration %, TT Injection %, PNC %, Districts at Risk — all at a glance.

**2. Best & Worst Performing States**
Horizontal bar charts ranking top 5 and bottom 5 states by average institutional births.

**3. Districts by Risk Tier (Donut Chart)**
Districts classified into **Excellent / Good / Watch / Critical**, showing that **~23% of districts are in the Critical zone** — a key insight for policymakers.

**4. Maternal Care Stages (Funnel View)**
Visualizes the drop-off across the 5-step maternal care journey — from ANC registration to postnatal care — revealing where mothers are "lost" in the system.

**5. Care Continuum by Region (Clustered Bar Chart)**
Compares all five indicators across India's 7 regions (North, South, East, West, Central, Northeast, Islands).

**6. Interactive India Map**
A filled shape map colored by institutional birth %, with slicers for Region, State, Risk Tier, and District — clicking a state reveals a detailed tooltip card.

<img width="907" height="528" alt="Maternal health analysis map" src="https://github.com/user-attachments/assets/c76e2cd2-c478-4703-8e23-64b8d507f85b" />
<img width="961" height="519" alt="Maternal health analytics" src="https://github.com/user-attachments/assets/a475c335-5a73-4cbe-935f-2e06235f2381" />

---

## 🔍 Key Insights

- **Kerala, Goa, Puducherry, Tamil Nadu, and Andaman & Nicobar** lead in institutional births.
- **Uttar Pradesh, Uttarakhand, Meghalaya, Jharkhand, and Chhattisgarh** need urgent policy focus.
- Nearly **1 in 4 districts (22.8%)** fall in the **Critical** risk tier.
- Identified 374 at-risk districts (22.8% Critical,40.37% Watch) based on ANC registration, TT injections, and institutional birth rates.
- Revealed care gaps with 45.18% ANC 1st trimester registration and 74.15% TT injection rate nationally.
- There is a noticeable gap between **ANC 1st trimester registration (45%)** and **institutional births (45%)**, showing consistent drop-off through the care journey.

---

## 📁 Repository Structure

```
maternal-health-analytics-dashboard/
│
├── datafile.csv                                  # Cleaned dataset
├── Maternal_Health_Dashboard.pbix                 # Power BI file
├── Maternity_Health_Analytics_Dashboard.png       # Full dashboard screenshot
├── Maternal_health_analysis_map.png               # Map view screenshot
├── Maternal_health_analytics.png                  # Tooltip detail screenshot
└── README.md
```

---

## 🚀 How to Use

1. Clone this repository
2. Open `Maternal_Health_Dashboard.pbix` in **Power BI Desktop**
3. Use the slicers (Region, State, Risk Tier, District) to explore the data
4. Click any state on the map for a detailed indicator tooltip

---

## 🧠 What I Learned

- Building interactive **map-based visuals** and drill-through tooltips in Power BI
- Writing **DAX measures** for ranking and tier classification
- Cleaning real-world government data with missing/inconsistent entries
- Translating raw health indicators into a story that supports **policy decision-making**

---

## 📬 Connect With Me

If you have feedback or suggestions on this project, feel free to connect!

- **LinkedIn:** [Add your link]
- **Email:** [Add your email]

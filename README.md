# 📊 YouTube Creator Engagement & Optimization Analysis

An executive-level Power BI Capstone project analyzing global YouTube engagement metrics and channel attributes. This analysis uncovers hidden viewer patterns, subscription behaviors, and content strategy benchmarks to help content creators and digital marketers maximize audience interaction on the platform.

---

## 📸 Dashboard Previews

### Executive Summary & KPIs
![Dashboard Page 1](assets/dashboard_page1.png)

### Deep-Dive Categorical Distributions
![Dashboard Page 2](assets/dashboard_page2.png)

---

## 🛠️ Project Core Deliverables & Solutions

This end-to-end business intelligence project addresses key strategic metrics required by stakeholders, systematically completing all core technical requirements:

1. **Strategic Key Performance Indicators (KPIs):** Integrated dedicated card containers to display critical platform scale metrics, including maximum channel uploads, minimum view rankings, and data-cleansed 30-day rolling average views.
2. **Channel Scale Filtering:** Built a customized line chart isolating hyper-active creators with over 200,000 total uploads to evaluate high-volume consistency patterns.
3. **Advanced Categorical Distributions:** Implemented specialized visuals including a Radar Chart to map channel types against platform ranking tiers, and a Packed Bubble Chart to cluster subscriber weights across content categories.
4. **Calculated Audience Interaction Metrics (DAX):** Engineered a custom metric to track true viewer efficiency per subscriber:
   $$\text{Viewed by Subscriber} = \text{DIVIDE}(\text{SUM}(\text{Views}), \text{SUM}(\text{Subscribers}), 0)$$
   This metric is systematically mapped alongside channel types in an analytical table visual.
5. **Interactive Root-Cause Exploration:** Leveraged a built-in Decomposition Tree visual allowing stakeholders to drill down and explore category hierarchies based entirely on global ranks.
6. **Polished Navigation & Distribution:** Integrated seamless page navigation buttons for fluid report storytelling, fully formatted with branding layouts, and staged for enterprise deployment via the Power BI Service.

---

## ⚙️ Tech Stack & Implementation Steps
* **Power Query Editor (ETL):** Handled critical null value removal, attribute cleansing, and strict data-type enforcement on rolling 30-day metrics.
* **DAX Modeling:** Created specialized optimization measures and calculated columns for viewer engagement ratios.
* **Power BI Service:** Deployed the interactive report into a dedicated workspace, designed an executive web dashboard using pinned report tiles, and generated portable multi-page presentation reports.

---

## 📈 Key Portfolio Insights Discovered
* **Upload Scale vs Rank:** Channels crossing the 200k upload threshold show a distinct correlation with specific corporate media/news structures rather than standard independent creator channels.
* **True Value of a Subscriber:** High subscriber counts do not always translate to optimal "Viewed by Subscriber" metrics.
* **Niche Engagement:** Specific niche channel types maintain significantly higher relative interaction scores despite lower absolute follower metrics.

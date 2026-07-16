# Industrial Procurement & Cost Analytics Dashboard

An enterprise business intelligence application built in Power BI to analyze a large-scale $517 Million supply chain portfolio, optimize vendor costing pipelines, and mitigate supplier concentration risks.

## 📊 Live Interactive Visuals
<img width="1122" height="633" alt="image" src="https://github.com/user-attachments/assets/125bf0c3-3712-447a-9c5e-8f7dba5c7a98" />


## 💡 Key Business Insights & Engineering Narrative
* **Portfolio Scope:** Managed and structured multi-table transactional datasets covering a $517M AED organizational spend.
* **Capital Leakage Controls:** Engineered an iterative DAX matrix to back-calculate, identify, and track $8M AED in total negotiated contract savings.
* **Risk Mitigation:** Isolated critical single-source supplier dependencies, identifying that a single vendor (Trisice Inc.) controlled 19% ($22M AED) of global procurement.
* **Commodity Alignment:** Configured dynamic data mapping tailored to industrial manufacturing infrastructure, slicing expenditures across core commodities including Fabrication, Metals, and Electrical components.

## 🛠️ Tech Stack & Advanced Features Built
* **Data Visualization Platform:** Power BI Desktop
* **Advanced Modeling Engine:** Star Schema relational data model linking transactional invoice fact tables to dimensional lookup tables (`Vendor`, `Item(Category)`).
* **Advanced DAX Analytics:** Engineered nested iterative calculations (`SUMX`, `RELATED`) to compute complex row-by-row margin variances across diverse database sources.
* **Executive User Experience (UX):** Deployed responsive scatter plot matrices, targeted parent category filters, and clear KPI summary indicators designed specifically for C-suite decision-making.

## 📁 Repository Contents
* `Industrial_Procurement_Cost_Dashboard.pbix`: Full operational Power BI dashboard file containing structural database relationships and analytical measures.


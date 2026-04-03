🏥 California Licensed Healthcare Facility Analysis
2022 – January 2026  |  Python  |  Pandas  |  Matplotlib  |  Seaborn  |  Plotly

📌 Project Overview

Analysis of 3,294 licensed healthcare facilities across California from 2022 to January 2026 using Python. This project covers data loading, cleaning, statistical analysis, 12 visualizations, and predictive trend analysis.

This project analyzes licensed healthcare facilities in California to understand:
• Geographic distribution
• Facility types
• Bed capacity
• Service availability

The analysis focuses on facilities licensed between January 2022 and January 2026, enabling trend analysis and decision-making for healthcare planning.

🎯 Business Problem

Healthcare planners and policymakers need to:
• Identify high and low facility concentration areas
• Understand capacity distribution (beds)
• Detect gaps in emergency services
• Improve resource allocation

👉 This project provides data-driven insights to support these decisions.

📂 Dataset

• Source: <a href="https://catalog.data.gov/dataset/licensed-healthcare-facility-listing-46300">California Department of Public Health CDPH via Data.gov (Public Access)</a>
• Raw Records: 10,921
• Filtered Records: 3,294 (2022 – January 2026)
• Columns: 18 → 21 (after cleaning)
• Geographic Scope: California, USA

🛠️ Tools & Technologies
•	Python — Core programming language
•	Pandas — Data loading, cleaning, filtering, groupby
•	NumPy — Numerical calculations, polyfit prediction
•	Matplotlib — Base chart library
•	Seaborn — Styled statistical visualizations
•	Plotly — Interactive geographic scatter map

📋 Project Stages

🔎 Stage 1: EDA: Explored 10,921 raw records
🧹 Stage 2: Data Cleaning: Processed dataset to 20 columns with 3 engineered features
📊 Satge 3: Visualization: Built 12 charts (Univariate, Bivariate, Multivariate)
💡 Stage 4: Insights: Derived 5 key findings with trend forecasting (2026–2027)

🎯 Objectives
1.	Maintain central dataset with location, license type, beds, county, and service level
2.	Understand how facilities are distributed across California by county, city, and facility level
3.	Evaluate the availability of Emergency (ER) services and total bed capacity
4.	Track facility status updates and year wise licensing trends (2022–2026)

📊 Objectives → Visualizations → Insights

| #  | Objective         | Charts Used                  | Key Insight                                                        |
| -- | ----------------- | ---------------------------- | ------------------------------------------------------------------ |
| 01 | Central Dataset   | Charts 3, 12 + 3 New Columns | 3,294 rows × 20 columns; 44 counties; 15 facility types            |
| 02 | Distribution      | Charts 5, 11, 12             | LA = 72.1%; heavy clustering; rural areas underserved              |
| 03 | ER & Bed Capacity | Charts 1, 4, 7, 8, 9         | 96.7% no beds; only 10 ER facilities; mean = 53.14, median = 17.50 |
| 04 | Year-wise Trends  | Charts 6, 10 + Stage 4       | Decline: 946 → 519; forecast: 487 (2026), 353 (2027)               |

➕ New Columns Table

| Column           | Values                                 | Purpose                                            |
| ---------------- | -------------------------------------- | -------------------------------------------------- |
| has_beds       | True = 108 / False = 3186              | Identify hospital-type facilities for bed analysis |
| valid_location | True = 3291 / False = 3                | Remove invalid (0.0) coordinates from maps         |
| year           | 2022→946, 2023→943, 2024→883, 2025→519 | Enable time-series trend analysis                  |

💡 Key Findings
•	LA county = 72.1% of all facilities
•	96.7% facilities have no beds
•	Only 10 ER facilities exist
•	Licensing declining 946→519 (2022→2025)
•	Predicted: 487 (2026), 353 (2027)
•	Mean beds 53.14 vs Median 17.50 — bed inequality

🔍 What I Discovered

📍 Geographic Concentration: Los Angeles county alone holds 72.1% of all California licensed healthcare facilities — creating a severe geographic imbalance across the state.
🏠 Outpatient Dominance: 96.7% of facilities have no beds — confirming California's healthcare model is predominantly home-based and outpatient, not hospital-based.
🚨 Emergency Care Gap: Only 10 facilities out of 3,294 offer emergency services — a critical gap in California's healthcare network.
📉 Declining Trend: Facility licensing declined from 946 in 2022 to 519 in 2025. Linear prediction shows 487 in 2026 and 353 in 2027 — decline continues.
🛏️ Bed Capacity Inequality: Mean beds 53.14 is significantly higher than median 17.50 — a few large hospitals dominate bed capacity while most facilities remain small.

👤 Author

💼 Aspiring Data Analyst

📧 Email: sathicse5@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/sathiya-priyan-da/

🐙 GitHub: https://github.com/priyan5295

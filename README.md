# EV-MARKET-SEGMENTATION
Market segmentation analysis for launching electric two-wheelers in India. Includes clustering (K-Means), vehicle sales trends (2020–2025), CAGR analysis, customer profiling, and scooter sales insights. Built with Python, pandas, seaborn, and scikit-learn.
Electric Two-Wheeler Market Segmentation & Analysis (India)

Overview:
This project explores India's two-wheeler market using multiple datasets to support a strategic electric scooter launch. It combines sales trend analysis, customer profiling, clustering, and market research to identify the most promising customer and geographic segments.

Datasets Used:
1. india_vehicle_sales_yearly.csv – National/state-level vehicle registration data.
2. lifestyle.csv – Customer financial and lifestyle data.
3. buying_behav.csv – Purchase behavior and demographic segmentation.
4. cleaned_ev_scooter_sales.csv – Monthly EV scooter sales and OEM rankings.

Techniques Applied:
- K-Means Clustering (with Elbow Method)
- PCA for cluster visualization
- CAGR Calculation for trend assessment
- Label Encoding & OneHot Encoding
- Data Scaling using MinMaxScaler and StandardScaler
- Visualizations using matplotlib and seaborn

Key Outputs:
- CAGR by vehicle segment (2020–2025)
- Top two-wheeler states by market share
- Lifestyle and buying behavior clusters
- Heatmaps and bar graphs for customer insight
- EV scooter trends, YoY and MoM growth metrics

Conclusions & Recommendations:
- Target dual-income, mid-to-high income consumers aged 30–40
- Focus on high-demand states like Maharashtra, Karnataka
- Customize marketing based on spending and saving habits
- Launch premium electric two-wheeler models aligned with lifestyle segments

Folder Structure:
notebooks/
  ├── Q1_Vehicle_Sales_Analysis.ipynb
  ├── Q2_Market_Segmentation.ipynb
  └── EV_Scooter_Sales_Trends.ipynb

data/
  ├── india_vehicle_sales_yearly.csv
  ├── lifestyle.csv
  ├── buying_behav.csv
  └── cleaned_ev_scooter_sales.csv

README.txt

Developed By:
Sujal Dhandre  
Market Research & Data Science Intern

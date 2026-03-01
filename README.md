# Olist Brazil E-Commerce Analysis

## Project Overview
This project analyzes over 100,000 transactions from the Olist Brazil E-Commerce dataset, uncovering key business insights through data analysis and interactive visualizations. The analysis covers revenue trends, customer behavior patterns, delivery performance, and seller metrics.

## Key Highlights
- **Dataset Size**: 100,000+ transactions
- **Time Period**: Multi-year e-commerce transaction data
- **Analysis Focus**: Revenue, customer behavior, delivery performance, and seller performance
- **Visualizations**: Interactive Tableau dashboards with actionable business insights

## Technologies & Tools
- **Data Analysis**: Python (Pandas, NumPy)
- **Data Visualization**: Matplotlib, Seaborn, Tableau
- **Data Cleaning**: Pandas, custom Python scripts
- **EDA**: Exploratory Data Analysis with statistical insights


## DATASET - https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

## Analysis Components

### 1. Data Cleaning & Preparation
- Handled missing values and data inconsistencies
- Standardized date formats and categorical variables
- Removed outliers and validated data quality

### 2. Exploratory Data Analysis (EDA)
- Distribution analysis of key metrics (revenue, order value, delivery time)
- Customer segmentation and behavior patterns
- Geographic analysis of orders and revenue
- Seasonal trends and peak periods

### 3. Feature Engineering
- Created new features for business insights
- Aggregated metrics by customer, seller, and product category
- Calculated delivery performance indicators

### 4. Key Insights
- **Revenue Trends**: Identified top-performing product categories and seasonal patterns
- **Customer Behavior**: Analyzed purchase frequency, average order value, and repeat customer rates
- **Delivery Performance**: Measured on-time delivery rates and delivery time patterns
- **Seller Metrics**: Evaluated seller performance and customer satisfaction ratings

## Tableau Dashboards
Interactive Tableau dashboards have been created to visualize:
- **Sales Dashboard**: Revenue by category, product performance, and time-based trends
- **Customer Dashboard**: Customer segmentation, lifetime value, and repeat purchase patterns
- **Delivery Dashboard**: On-time delivery metrics, delivery time distribution, and regional performance
- **Seller Dashboard**: Top sellers, seller ratings, and performance metrics

*Access the Tableau visualizations [here](link-to-tableau-public-dashboard)* (update with your Tableau Public link if available)

## Files & Structure
```
├── README.md
├── data/
│   └── [dataset files]
├── notebooks/
│   └── analysis.ipynb (or .py files)
├── visualizations/
│   └── [charts and figures]
└── tableau/
    └── [Tableau workbook files]
```

## How to Use This Project
1. Review the analysis notebooks for detailed methodology
2. Explore the Tableau dashboards for interactive insights
3. Use the findings to inform business decisions on:
   - Product strategy
   - Customer retention initiatives
   - Seller performance management
   - Delivery optimization

## Requirements
- Python 3.7+
- pandas
- numpy
- matplotlib
- seaborn
- tableau (for dashboard viewing)

## Installation
```bash
pip install pandas numpy matplotlib seaborn
```

## Results & Conclusions
## 📊 Results & Conclusions

### Revenue Trends
- Olist experienced strong revenue growth throughout 2017, peaking in **November 2017** — 
  clearly driven by Black Friday/Cyber Monday sales.
- Revenue stabilized in early 2018 but showed consistent month-over-month growth, 
  indicating a maturing and expanding customer base.

### Top Performing Product Categories
- **Health & Beauty**, **Watches & Gifts**, and **Bed/Bath/Table** were the top 3 
  revenue-generating categories, collectively accounting for a significant share of total sales.
- These categories should be prioritized for marketing spend, promotional campaigns, 
  and inventory stocking.

### Customer Satisfaction by Region
- The national average review score was approximately **4.0 / 5.0**.
- States in the **South and Southeast** (SP, RJ, MG) generated the most orders but had 
  slightly lower satisfaction scores — likely due to higher volume causing delivery strain.
- Smaller northern states showed **higher satisfaction scores**, possibly due to lower 
  volume and more manageable logistics.

### Key Business Recommendations
1. **Invest in logistics for SP and RJ** — these states drive the most revenue but show 
   signs of delivery-related dissatisfaction.
2. **Double down on Health & Beauty** — highest revenue category with strong repeat 
   purchase potential.
3. **Run targeted campaigns around November** — the data clearly supports a seasonal 
   spike; planning inventory and ads ahead of Q4 would maximize revenue.
4. **Improve delivery times in the North/Northeast** — longer delivery distances are 
   likely hurting satisfaction scores in states like AM, RR, and AP.

### Dashboard KPIs (Summary)
| Metric | Value |
|--------|-------|
| Total Revenue | R$ ~13.6M |
| Total Orders | ~96,000 |
| Avg Review Score | ~4.07 / 5 |
| Top Category | Health & Beauty |
| Highest Order Volume State | SP (São Paulo) |

---
*Analysis performed using Python (pandas, matplotlib, seaborn) and visualized in Tableau Public.*

## Author
r0c9y


## Contact
For questions or collaboration, feel free to reach out!

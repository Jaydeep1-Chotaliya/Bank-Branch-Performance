# Bank-Branch-Performance
This project presents an interactive Power BI dashboard designed to analyze and monitor the performance of bank branches for the financial year 2024 (FY2024).  The dashboard provides key insights into loans, deposits, revenue, profitability, customer growth, and asset quality (NPA), enabling data-driven decision-making.


<img width="1024" height="800" alt="pexels-nicosiegl01-14638897" src="https://github.com/user-attachments/assets/32face54-b231-4a3a-a23d-b9adf7ca2bc6" />



# **Introduction:** 
Outline of the Problem to Solve

Banks generate large volumes of data across branches, including loans, deposits, revenue, and NPAs. However, without a structured BI system, it is difficult to:

Track branch-wise performance
Monitor financial KPIs in a single view
Identify high-risk areas (NPA-heavy branches)
Analyze regional and monthly trends

This project solves the problem by building an interactive Power BI dashboard with a proper data model and KPI layer.


# **Objective:** 
Build a centralized performance dashboard
Analyze branch, region, and time-based metrics
Create reusable DAX measures for KPIs
Enable interactive filtering and drill-down analysis
Provide insights into growth, profitability, and risk
Importance
Improves decision-making speed using real-time insights
Helps identify underperforming branches
Tracks financial health metrics efficiently
Enables data-driven strategy planning
Reduces dependency on manual reporting
Applications
Banking analytics & performance monitoring
Business Intelligence portfolio project
KPI dashboards for financial institutions
Risk analysis (NPA monitoring)
Customer growth & trend analysis

# **Methodology:** 
1. Data Extraction – Imported data from Excel files.
2. ETL & Modeling – Cleaned, transformed, and modeled data using Power Query.
3. DAX Calculations – Created custom measures for KPIs and financial metrics.
4. Visualization – Built an interactive dashboard with charts, cards, and tables.
5. Interactivity – Added slicers for Branch, Region, and Month to enable dynamic filtering.

# **Snapshot of visuals:** 

Overall Performance of Bank :

The bank maintains a strong loan-to-deposit ratio, indicating efficient fund utilization.

Revenue and profitability are stable, reflecting consistent financial performance.

NPA levels in some branches highlight risk areas that need attention.

Customer growth is positive, showing expansion in market reach and business.

<img width="1343" height="752" alt="image" src="https://github.com/user-attachments/assets/b0f51f43-ebae-4095-af4e-06a3714a7e1a" />

Best Performing Region: **West**

Highest Customer Growth (3.02%) – indicates strong market penetration and customer acquisition.

Lowest NPA Amount (8.35M) – reflects better asset quality and credit management.

Lowest LD Ratio (71.12%) – conservative lending approach with room for loan growth.

Strong deposit base (291M) relative to loans (207.14M).

<img width="1344" height="751" alt="image" src="https://github.com/user-attachments/assets/b5862880-a910-4569-a55b-dc01348b3c11" />

Worst Performing Region: **South**

Highest LD Ratio (80.23%) – indicates higher lending relative to deposits, which may pose liquidity risk.

Lowest Customer Growth (2.08%) – suggests slower market expansion.

Moderate NPA (11.75M) – while not the highest, it's concerning given the lower loan portfolio.

Lowest Revenue (5.95M) among all regions.

<img width="1343" height="740" alt="image" src="https://github.com/user-attachments/assets/9987cfd9-1b86-4f51-b855-4eb78535fdb8" />


# **Results / Insight:** 

- Strong deposit base with room for loan growth – Total deposits stand at 1,501M, while total loans are 1,121.01M, resulting in a Loan-to-Deposit Ratio of 74.66%. This indicates a conservative lending strategy with scope for future expansion.
- NPA concentration in specific branches – Salt Lake (5.09%), Andheri (4.66%), and Kharvel Nagar (4.65%) are the top 3 branches with highest NPA percentages, contributing significantly to the total NPA amount of 47.87M. These branches need focused recovery and monitoring efforts.
- Regional revenue disparity – The South and West regions generate the highest revenue, while the East and North regions underperform. Targeted interventions and strategy replication could help bridge this gap.
- Customer growth shows positive but seasonal trends – Overall customer growth is 2.25%, with monthly new customer additions fluctuating between 1,399 and 2,170. Peaks observed in February and December suggest seasonal or promotional influences that can be leveraged in future campaigns.
- High-loan branches not always high-NPA, except one outlier – The top loan disbursement branches are Kharvel Nagar (123.32M), Banjara Hills (118.52M), and Salt Lake (118.15M). However, Salt Lake also appears in the top NPA list, making it a critical outlier requiring immediate credit quality review.

# **Conclusion:** 

This project successfully demonstrates the application of a structured Business Intelligence framework—integrating data modeling, DAX calculations, and interactive visualizations—to convert raw banking data into meaningful, actionable insights. The dashboard offers a clear and scalable view of branch-level performance, enabling stakeholders to monitor key metrics such as loan distribution, NPA concentration, revenue trends, and customer growth. With its user-friendly design and analytical depth, the solution serves as a solid foundation for informed decision-making and ongoing performance tracking.

# **Limitations & Challenges Faced:** 

- Dataset is limited to only 10 branches, restricting the scope of cross-branch comparisons and broader trend analysis.
- The dashboard relies on static historical data with no real-time or automated data refresh capabilities.
- Analysis is confined to descriptive analytics; advanced functionalities like predictive modeling, forecasting, or anomaly detection are not included.
- Data preprocessing and cleaning were performed manually, which increases effort and reduces efficiency for frequent updates.
- The current design may face scalability challenges when applied to larger, enterprise-level datasets with multiple regions and time periods.

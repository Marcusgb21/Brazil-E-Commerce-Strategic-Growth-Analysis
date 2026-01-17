# Brazil-E-Commerce-Strategic-Growth-Analysis
This project demonstrates an end-to-end analytical workflow: leveraging SQL for complex data transformation, aggregation, and year-over-year (YoY) performance calculations, and Tableau for building strategic, interactive dashboards that translate raw data into actionable business intelligence.

Data Source
This analysis utilizes the Brazilian E-Commerce Public Dataset by Olist, available on Kaggle.
[Link to Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)


## 🚀 How to Run the Analysis
1. Install DuckDB.
2. Download the Olist dataset from the Kaggle link above.
3. Ensure that the data folder is a directory below the database file.
4. Run CMD in the directory line where the folder is located
5. Type duckdb 'project-name'.db -ui
6. It will then move you to Duckdb to reproduce all KPIs and views. Ensure that the 'Environment Setup' section is executed first to ingest the CSVs into tables.


Key Performance Indicators (KPIs):

Revenue & Growth: Analyzed a 138% YoY revenue surge and a 203.9% growth momentum, validating the platform's ability to scale rapidly.

Product & Category Performance: Optimized a 70+ category portfolio by identifying high-margin anchors like 'Relógios' through 2x2 Matrix analysis, while utilizing ABC Pareto modeling to prove that 80% of revenue is concentrated in just 16 core categories, including hyper-growth leaders like 'Agro Indústria'.

Regional Intelligence: Mapping national market reach to reveal a strategic divide between the Southeast 'Volume Anchor' (São Paulo)—which drives 32% of total orders—and Northeast 'Premium Clusters' (João Pessoa/Belém), where Average Order Values (AOV) reach $209.31, or 68% above the national average.

[📊 View the Interactive Executive Portal here](https://public.tableau.com/views/BrazilEcommerce_17680444562380/BrazilE-CommerceStrategicGrowthAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

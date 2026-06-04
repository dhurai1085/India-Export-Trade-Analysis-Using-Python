India's Export Trade Performance Analytics

1. Objective:

This project focuses on analysing India’s export trade statistics using Python to identify export trends, high-performing commodities, top destination countries, and regional trade patterns. The dataset contains real-world international trade records including export values, quantities, commodity classifications, and geographic information. Through data cleaning, exploratory data analysis, and visualization techniques, the project aims to generate meaningful business and economic insights from India’s global export activities.

2. Business Problem

India exports thousands of commodities to multiple countries and regions worldwide. However, identifying top-performing export commodities, high-value export destinations regional trade patterns, export growth trends, quantity vs revenue relationships is difficult without proper data analysis.

Organizations and policymakers require insights into export performance to:
•
Understand international market demand

•
Identify profitable export sectors

•
Monitor trade growth

3. Expected Outcome:

The project aims to:
•
Analyse India’s export performance over time
•
Identify top export destination countries
•
Determine high-performing commodities
•
Study regional and sub-regional trade trends
•
Compare export quantity and export value
•
Generate meaningful business insights using visualization and EDA techniques

4. Dataset Information:

Source: Indian Data Portal
The dataset is sourced from: India Data Portal Trade/export records published through Indian government statistical systems. This is a government/public economic dataset, which makes your project look more authentic and professional compared to random practice datasets.

Dataset Size:

Metric Value Number of Rows 532K

Number of Columns 17

Dataset Size ~ 50.6 MB

5. Attribute (Column / Feature) Details:
| Column            | Description                                                            |
| ----------------- | ---------------------------------------------------------------------- |
| `id`              | Unique identifier for each export transaction record.                  |
| `date`            | Date of the export transaction.                                        |
| `country_name`    | Destination country where the goods were exported.                     |
| `region`          | Geographic region of the destination country.                          |
| `region_code`     | Code representing the destination region.                              |
| `sub_region`      | Sub-region classification of the destination country.                  |
| `sub_region_code` | Code representing the destination sub-region.                          |
| `hs_code`         | Harmonized System (HS) code used to classify the exported commodity.   |
| `commodity`       | Name or description of the exported commodity/product.                 |
| `unit`            | Measurement unit used for the exported quantity (e.g., KGS, NOS, SQM). |
| `value_qt`        | Quantity of the exported commodity in the specified unit.              |
| `value_rs`        | Export value in Indian Rupees (INR).                                   |
| `value_dl`        | Export value in US Dollars (USD).                                      |
| `year`            | Year extracted from the transaction date.                              |
| `month`           | Numeric month extracted from the transaction date (1–12).              |
| `month_name`      | Name of the month extracted from the transaction date.                 |
| `quarter`         | Quarter of the year extracted from the transaction date (1–4).         |
-----------------------------------------------------------------------------------------------

6. Tools & Technologies:

  - Python 
  - pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Jupyter Notebook / Google Colab

7. Summary of Findings:

This project analyzed India’s exports to European countries using Python. The dataset contained approximately 532,000 export transactions covering multiple commodities, countries, quantities, and trade values.

The analysis showed that export trade value is highly concentrated among a small number of countries and commodities. The Kingdom of the Netherlands emerged as the most significant export destination in terms of trade value. Fuel-related products, particularly Automotive Diesel Fuel and Aviation Turbine Fuel, contributed a major share of export revenue.

Monthly and quarterly trend analysis revealed seasonal variations in export performance, with stronger export activity observed during the second quarter. Correlation analysis showed a strong positive relationship between export quantity and export value, indicating that larger shipment quantities generally generate higher trade revenue.

Overall, the export market is driven by a limited number of high-value commodities and major destination countries.

8. Key Insights:

1.Export value distribution is highly skewed
Most export transactions have relatively low trade values, while a small number of transactions contribute exceptionally high values. This creates a positively skewed distribution with numerous outliers.

2.Netherlands is the dominant export destination
The Kingdom of the Netherlands consistently records the highest export value among European countries, making it the most important market in the dataset.

3.Fuel products drive export revenue
Automotive Diesel Fuel and Aviation Turbine Fuel contribute significantly more export value than other commodities, indicating heavy dependence on energy-related exports.

4.Quantity and export trade values are strongly related
Correlation analysis and scatter plots show a strong positive relationship between export quantity and trade value. Higher shipment volumes generally result in higher export earnings.

5.Export performance peeks during q2 of both 2024 and 2025
Quarterly analysis shows stronger export activity during the second quarter compared with other quarters, suggesting possible seasonal demand patterns.

9. Conclusion:

The analysis reveals that India’s exports to Europe are primarily driven by a few dominant countries and high-value commodities. Export performance shows clear seasonal patterns and a strong relationship between shipment quantity and trade value. By strengthening key trade partnerships while diversifying both markets and products, exporters can improve resilience and support long-term export growth.

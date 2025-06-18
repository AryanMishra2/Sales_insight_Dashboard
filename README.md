Sales Insight Dashboard (Power BI + SQL)
Developed an interactive Sales Insight Dashboard using Power BI and SQL/SQL Workbench. Implemented data warehousing principles to avoid direct modifications on the production server, ensuring business process integrity. Performed data cleaning and transformation to prepare accurate and reliable datasets. Leveraged the transformed data to deliver actionable insights through a dynamic Power BI dashboard.

Data : Uploaded(https://github.com/AryanMishra2/Sales_insight_Dashboard/blob/main/db_dump.sql)

Data Warehousing:
We cannot perform transformation and cleanup directly on the data server, as it poses the risk of permanent data damage. That’s why we use data warehousing—to separate company data and work on it independently, avoiding any potential disasters or issues.
![image](https://github.com/user-attachments/assets/688d8d21-8ac1-4937-9d13-7ee5e202b302)

Data Check using SQL:
We check the data using SQL, as server data may contain nulls, garbage values, missing entries, or formatting/unit issues. Identifying these early helps prevent inaccurate analytics or visualizations, which could lead to incorrect business decisions.
:![Screenshot (5)](https://github.com/user-attachments/assets/3ad59b8d-15f8-4eab-8fbd-22f5d51e3352)

Data Transformation (Power BI):
After identifying null, missing, or garbage values, we move on to data transformation. Although such tasks are often handled in Excel, Power BI provides powerful built-in features for transforming data. These tools allow us to clean, reformat, and manipulate data efficiently, ensuring it is accurate and ready for meaningful analysis and visualization.
: ![Screenshot (7)](https://github.com/user-attachments/assets/f54854c0-a3da-4ae7-8758-23216ec470e1)

Data Visualization (Power BI Dashboard):
After transforming the data, we use Power BI to create interactive visualizations by analyzing various columns and business metrics. This helps in identifying trends, patterns, and key insights. Since Power BI supports real-time data visualization, it allows stakeholders to monitor performance, detect issues quickly, and make accurate, data-driven decisions. The dashboard provides a clear and concise view of business operations, enabling better understanding and strategic planning.
: ![Screenshot (6)](https://github.com/user-attachments/assets/0826f804-9491-4b87-9276-ef35764f97cb)


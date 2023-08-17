# Forggith-Pharmaceautical-Report
# Introduction
I had completed a Power BI Developer program where I had the priviledge to use Power BI to solve real life reporting and Analytical problems. 

The goal of the project is to create an interactive Power BI report to assist Forggith Pharmaceuticals, a Pharmaceutical Manufacturing company based in Germany in guiding their strategies, tactics and operations as a compnay.

The Report/Analysis should:
1. Help the sales representatives to track their pergormances throughout the periods to plan their marketing activities.
2. The different team managers to track their teams performance throughout the periods to enable them plan their activities.
3. The executife team can track revenue numbers to monitor alignment with the set targets to influence medium to long term strategies.

# Data Collection and Sourcing
The Dataset was provided which is composed of two different files the PharmDataset and the PharmTarget. The PharmDateset contains 7 files; The Dimlocation, Dimsubchannel, Dimchannel, Dimproduct, DimEmployees, Sales2022, Sales2023-Sales2025. The PharmTarget houses the target datasets of the company.

# Understanding of the Dataset
The first step I took before embarking on the analysis is to ensure, I had a good understanding of the individual features that made up the datasets.

# Data Transformation/Modelling
After laoding the dataset into Power query editor. I merged the Dimchannel and Subchannel using the channelId to form a single table which was connected to the main table (PharmDataset). I appended the sales2022 dataset with Sales2023-2025 dataset.

Looking at the PharmTarget, I noticed that the sales column had structural issues and were widespread across the spreadsheet, using the unpivot feature, I transposed the values to form a single year column.  Having completed the transformation and cleaning in power query. I loaded the dataset into Power BI for Analysis and visualization. I created the appropriate data model and relationships after loading into Power BI. 

Before calculating my time intelligence functions, I created a Calendar/Date table which was connected to the Sales and Target table. I created measures table for all my DAX calculation/measures.

# Visualization
All visualizations were created using MS Power BI to form a report. The following insights were drawn from the Analysis.

1. The total revenue
2. Target revenue
3. Year-over-Year (YoY%) and Month-o-Month (MoM%) change
4. Total revenue by Name and Employee
5. Total Revenue by Product Category
6. Total Revenue by Top 10 product
7. Total Revenue by Least 10 product
8. Total Revenue by Channel and Subchannel
9. Total Revenue by Teams
10. Average sales
11. Total Volume Achieved
12. Total volues achieved by managers
13. Total Revenue by Month
14. Total Revenue by Top 10 cities
15. Total Revenue by Top 5 distributors etc

# Reommendations

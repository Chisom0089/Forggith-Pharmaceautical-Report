# Forggith-Pharmaceautical-Report
# Introduction
I had completed a Power BI Developer program where I had the priviledge to use Power BI to solve real life reporting and Analytical problems. 

The goal of the project is to create an interactive Power BI report to assist Forggith Pharmaceuticals, a Pharmaceutical Manufacturing company based in Germany in guiding their strategies, tactics and operations as a compnay.

The Report/Analysis should help;
1. The sales representatives to track their performances throughout the periods to plan their marketing activities.
2. The different team managers to track their teams performance throughout the periods to enable them plan their activities.
3. The executive team can track revenue numbers to monitor alignment with the set targets to influence medium to long term strategies.

# Data Collection and Sourcing
The Dataset was provided which is composed of two different files the Sales Data and the Target Data. The Sales Data contains the details of: The Location, Subchannel, Channel, Products, Employees, 2022 Sales and , 2023-2025 Sales respectively. The Target file houses the details of the company's target sales. 

# Understanding of the Dataset
The first step I took before embarking on the analysis is to ensure, I have a good understanding of the individual features that made up the datasets. I prepared a data dicitionary which can be seen in the picture below.

![Uploading Forggith Data dictionary.png…]()

# Data Transformation/Modelling
After laoding the dataset into Power query editor. I merged the Dimchannel and Subchannel using the channelId to form a single table which was connected to the main table (Sales). I appended the 2022 sales dataset with 2023-2025 sales dataset to form a single Sales data for all the years.

Looking at the Target data, I noticed that the sales column had structural issues and were widespread across the spreadsheet, using the unpivot feature, I transposed the values to form a single year column.  Having completed the transformation and cleaning in power query. I loaded the dataset into Power BI for Analysis and visualization. I created the appropriate data model and relationships after loading into Power BI. 

Before calculating my time intelligence functions, I created a Calendar/Date table which was connected to the Sales and Target table respectively. I created measures table for all my DAX calculation/measures.

# Visualization
All visualizations were created using MS Power BI to form a report. The following insights were drawn from the Analysis.
1. The total revenue (Card Visual)
2. Target revenue (Card Visual)
3. Average sales (Card Visual)
4. Year-over-Year (YoY%) and Month-o-Month (MoM%) change (Card Visual)
5. Total revenue by Name and Employee (Matrix Chart)
6. Total Revenue by Product Category (Clustered Bar Chart)
7. Total Revenue by Top 10 product (Clustered Bar Chart)
8. Total Revenue by Least 10 product (Clustered Bar Chart)
9. Total Revenue by Channel and Subchannel (Clustered Column Chart)
10. Total Revenue by Teams (Clustered Column Chart)
11. Total Volume Achieved (Card Visual)
12. Total volume achieved by Managers (Clustered Bar Chart)
13. Total Revenue by Month (Line Chart)
14. Total Revenue by Top 10 cities (Map Visual)
15. Total Revenue by Top 5 distributors (Clustered Bar Chart) etc

# Insights
- The total revenue generated is $11.12bn against target revenue of $20.51M
- The total volume achieved was $11.1bn
- The pharmacy channel generated a total of 52.9% while the hospital channel has 47..1% of the total revenue
- The distributor Gerlach LLC generated the highest revenue
- The top 10 cities with the highest revenue includes: Butzbach with the highest revenue of $93,561,780, followed by Baesweiler with $64,890,501, Cuxhaven $56,006,680, Friedberg $52,13,527, Altenburg $50,885,320, Emsdetten $45,939,009, Bottrop $44,454,616,  Freising $43,779,381, Tier $43,495,626 and Castrop-Rauxel $42,066,844 respectively
- Team Delta generated the highest revenue
- Analgesic drugs generated the highest total revenue followed by Antiseptic, Mood Stabilizer, Antipiretics, Antibiotics and Antimalarial drugs respectively
- The year 2024 has the highest total revenue of $2.93bn against target revenue of $5.35M, with YoY% change of 3.71 and MoM% change of 2.18 while 2025 generated the least revenue of $2.66bn against target revenue of $5.88M with YoY% change of -9.26 and MoM% change of 2.83.

# Reommendations
1. From the overal analysis, More resources and efforts should be allocated to the Pharmacy channel to further capitalize on the success
2. Identify areas for improvement in the hospital channel so as to strengthen its revenue generation
3. The distributors relationships needs to be prioritize and monitor their strategies to ensure their optimium performance
4. To the low performing cities, strategies such as marketing campaigns, promotions and availabiltity of products should be employed for better yield.
5. share best practices across teams to improve their overal performance
6. Further investigation should be done to know why Analgesic medicines generated the highest revenue which may be adopted to improve the sales of the other products.

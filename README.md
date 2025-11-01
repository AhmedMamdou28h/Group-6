________________________________________
🚇 MTA Daily Ridership Analysis & BI Dashboard

🧩 Executive Summary
This project focuses on analyzing the MTA Daily Ridership dataset to understand and visualize post-pandemic recovery trends. Using Power BI, we aim to uncover actionable insights into operational performance across different transit modes (Subways, Buses, Railroads) and track key recovery metrics against pre-pandemic levels.

🎯 Project Objectives
•	Analyze and visualize daily ridership trends over time.
•	Track and measure ridership recovery progress against pre-pandemic benchmarks.
•	Identify and compare patterns between different transit modes (e.g., Subways vs. Buses).
•	Provide a clear, interactive Power BI dashboard for stakeholders to understand performance at a glance.

📊 Dataset Overview
•	Source: MTA_Daily_Ridership.csv (provided by the MTA)
•	Content: Contains daily estimated ridership figures for 4 major transit modes.
o	Date: The date of the record.
o	Transit_Mode: (e.g., Subways, Buses, LIRR, Metro-North).
o	Total_Estimated_Ridership: The daily count of riders.
o	Percent_of_Pre_Pandemic: The recovery percentage for that day.
•	Supporting Files: MTA_data_dictionary.csv, MTA_DailyRidershipData_Overview.pdf

🧠 Technologies & Tools
Category	Tools
Data Cleaning & Transformation	Excel, Power BI (Power Query)
Data Modeling	Power BI (Model View, DAX)
Data Visualization & Reporting	Power BI (Report View)
Collaboration & Documentation	GitHub, MS Word

👥 Roles & Responsibilities
Role	Member Name	Responsibility
Team Leader / Data Analyst	Ahmed Mamdouh	Project coordination, dashboard design, final insights.
Data Analyst	Omar Gaber	Data cleaning, transformation (Power Query), and EDA.
Data Analyst	Abdelrahman Mostafa	Data modeling (Star Schema) and DAX calculations.
Data Analyst	Sameh Abo El-enin	Data visualization and KPI integration in Power BI.

🔍 Methodology
1.	Data Understanding & Cleaning: Loaded the .csv file into Power Query. Checked data types (especially for Date), handled any missing values, and ensured consistency.
	
2.	Data Modeling (Star Schema): Transformed the flat file into a Star Schema within Power BI.
	
3.	Created a Dim_Date table (Date Dimension).
	
4.	Created a Dim_Transport_Type table (Transport Dimension).
	
5.	Created a Fact_Ridership table (Fact Table) containing the measures (Total_Ridership, Pre_Pandemic_Percent).
	
6.	Established relationships between the tables.
	
7.	Dashboard Design (UI/UX): Designed an interactive dashboard focused on clarity and key insights.
	
8.	Insights & Recommendations: Analyzed the final visuals to derive conclusions about recovery trends.
   
📈 Key Performance Indicators (KPIs)
•	Total Estimated Ridership (Daily, Weekly, Monthly)
•	Overall % of Pre-Pandemic (Average)
•	% of Pre-Pandemic by Transit Type (Subways, Buses, LIRR, Metro-North)
•	Ridership by Day of Week (Weekday vs. Weekend Analysis)
•	Month-over-Month (MoM) Growth Rate

🗓️ Project Timeline & Milestones
Phase	Description	Duration
Phase 1	Project Planning & Data Understanding	Week 1
Phase 2	Data Cleaning & Transformation (Power Query)	Week 2
Phase 3	Data Modeling (Star Schema in Power BI)	Week 3
Phase 4	Dashboard Design & Visualization (Power BI)	Week 4
Phase 5	Final Insights, Documentation & Review	Week 5

⚙️ Setup & Execution Guide
1.	Download the MTA_Daily_Ridership.csv dataset.
2.	Open Power BI Desktop.
3.	Get Data > Select Text/CSV and load the dataset.
4.	Click Transform Data to open the Power Query Editor for cleaning.
5.	After cleaning, Close & Apply.
6.	Go to the Model View to create the Dim_Date and Dim_Transport_Type tables and build the relationships.
7.	Go to the Report View to build the visuals and KPIs.
8.	
🚀 Future Enhancements
•	Integrate External Data: Combine the dataset with external data (e.g., Weather, Public Holidays, City Events) to find new correlations.
•	Predictive Modeling: Use Python (Scikit-learn) or R to build a model that forecasts future ridership.
•	Automate Refresh: Deploy the report to Power BI Service and set up a scheduled refresh.

📧 Contact Information
•	Gmail [ahmedmamdouhsoltan13@gmail.com]
•	Linked in: [www.linkedin.com/in/ahmed-mamdo28h]
________________________________________


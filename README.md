🚗 Road Accident Analysis Dashboard
📌 Project Overview
This project analyzes road accident data to identify patterns and trends in accidents and casualties.
The project uses SQL Server, Microsoft Excel, and Power BI to perform data analysis and create an interactive dashboard. SQL queries were used to calculate key accident and casualty metrics, while Power BI was used to present the results through interactive visualizations.
The dataset contains 307,973 accident records with information related to accident severity, casualties, vehicles, road conditions, weather, light conditions, location, and other accident-related factors.
________________________________________
🎯 Project Objectives
The main objectives of this project are to:
•	Analyze total accidents and casualties
•	Analyze casualties by accident severity
•	Compare current-year and previous-year casualty trends
•	Analyze casualties by vehicle type
•	Analyze casualties by road type
•	Compare casualties in urban and rural areas
•	Analyze casualties under different light conditions
•	Identify locations with higher numbers of casualties
•	Understand patterns in road accident data
•	Present the analysis through an interactive Power BI dashboard
________________________________________
🛠️ Tools & Technologies
•	Microsoft Excel – Dataset and initial data handling
•	SQL Server / SSMS – Data analysis and SQL queries
•	Power BI – Interactive dashboard and data visualization
•	GitHub – Project documentation and version control
________________________________________
📊 Dataset
Dataset: Road Accident Data.xlsx
The dataset contains 307,973 records and 21 columns.
Key columns include:
•	Accident Index
•	Accident Date
•	Day of Week
•	Junction Control
•	Junction Detail
•	Accident Severity
•	Latitude
•	Longitude
•	Light Conditions
•	Local Authority
•	Carriageway Hazards
•	Number of Casualties
•	Number of Vehicles
•	Police Force
•	Road Surface Conditions
•	Road Type
•	Speed Limit
•	Time
•	Urban or Rural Area
•	Weather Conditions
•	Vehicle Type
________________________________________
🔍 SQL Analysis
The SQL analysis was performed using the road_accident table.
The queries calculate and analyze:
1. CY Casualties
Calculates total casualties for the year 2022.
2. Casualties on Dry Road Surfaces
Analyzes casualties where the road surface condition was recorded as dry.
3. CY Accidents
Calculates the number of distinct accidents during 2022.
4. Fatal Casualties
Calculates casualties associated with fatal accidents.
5. Serious Casualties
Calculates casualties associated with serious accidents.
6. Slight Casualties
Calculates casualties associated with slight accidents.
7. Casualties by Vehicle Type
Vehicle types are grouped into categories such as:
•	Agricultural
•	Cars
•	Bike
•	Bus
•	Van
•	Other
This grouping is then used to analyze casualties by vehicle category.
8. Monthly Casualty Trend
Compares monthly casualty totals for 2022 and 2021.
9. Casualties by Road Type
Analyzes casualties across different road types.
10. Casualties by Urban/Rural Area
Calculates the percentage distribution of casualties between urban and rural areas.
11. Casualties by Light Conditions
Light conditions are grouped into:
•	Day
•	Night
The percentage of casualties under each condition is then calculated.
12. Casualties by Location
Analyzes casualties by local authority and orders locations by total casualties.
The SQL documentation contains the complete queries used for these analyses.
________________________________________
📈 Power BI Dashboard
The Power BI dashboard presents the analysis through interactive visualizations.
The dashboard is designed to help users explore:
•	Accident and casualty metrics
•	Accident severity
•	Vehicle categories
•	Monthly trends
•	Road types
•	Urban vs. rural areas
•	Light conditions
•	Locations
•	Other accident-related factors
The Power BI dashboard is available in the PowerBI folder.
________________________________________
🔄 Project Workflow
Road Accident Dataset
        ↓
Microsoft Excel
        ↓
SQL Server / SSMS
        ↓
SQL Analysis
        ↓
Key Accident & Casualty Metrics
        ↓
Power BI
        ↓
Interactive Dashboard
        ↓
Insights & Analysis
The documented workflow follows loading the dataset into SQL Server, using the road_accident table, running SQL queries, using the results to support the Power BI dashboard, and presenting findings through interactive visualizations.
________________________________________
📁 Repository Structure
Road-Accident-Analysis/
│
├── README.md
│
├── Dataset/
│   └── Road Accident Data.xlsx
│
├── PowerBI/
│   └── Road Accidents Analysis Dashboard.pbix
│
├── SQL/
│   └── SQL Queries.docx
│
└── Screenshots/
    └── Road Accident Dashboard.png
________________________________________
💡 Key Skills Demonstrated
•	SQL querying
•	Data analysis
•	Data aggregation
•	Data transformation
•	Data categorization
•	Power BI dashboard development
•	Data visualization
•	Excel data handling
•	Business-oriented analysis
•	Analytical problem solving
________________________________________
📚 Documentation
The SQL folder contains the complete SQL Queries Documentation used in this project.
The documentation includes the SQL analysis for accident and casualty metrics and explains how the query results support the Power BI dashboard.
________________________________________
📂 Project Files
File	Description
Road Accident Data.xlsx	Original road accident dataset
Road Accidents Analysis Dashboard.pbix	Interactive Power BI dashboard
SQL Queries.docx	SQL analysis queries and documentation
Road Accident Dashboard.png	Dashboard preview
README.md	Project documentation
________________________________________
🎓 What I Learned
Through this project, I strengthened my ability to:
•	Work with a large real-world dataset
•	Analyze accident and casualty data using SQL
•	Create meaningful categories for analysis
•	Calculate percentages and aggregated metrics
•	Build interactive Power BI dashboards
•	Convert raw data into meaningful visual insights
•	Organize and document an end-to-end data analytics project
________________________________________
👩‍💻 Author
Sakshi Dhumane
Aspiring Data Analyst
Skills: SQL | Power BI | Excel | Python | Tableau | Data Analytics
________________________________________
⭐ If you find this project useful, feel free to explore the repository and the Power BI dashboard.

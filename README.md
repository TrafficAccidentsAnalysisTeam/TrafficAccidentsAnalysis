🚦 Traffic Accident Data Analysis
A Data Analytics and Visualization (DAV) Semester Project
An exploratory data analysis and visualization project focused on understanding traffic accident patterns across multiple cities and states in India using Python and Microsoft Power BI.

📌 Project Overview
Traffic accidents are influenced by several factors, including road conditions, weather, vehicle types, time, location and human behavior.
This project analyzes a traffic accident dataset to identify patterns, trends and relationships among these factors. Using data cleaning, exploratory data analysis (EDA), statistical analysis and visualization, the project transforms raw data into meaningful insights.
The project also includes an interactive Power BI dashboard to present the findings in an accessible and understandable format.
🎯 Problem Statement
To analyze traffic accident data and identify patterns, trends, accident severity and contributing factors across different locations and time periods.
🎯 Project Objectives

Clean and preprocess the traffic accident dataset.
Perform Exploratory Data Analysis (EDA).
Analyze accident trends across different months, years and locations.
Identify cities with the highest recorded accident counts.
Examine accident severity, injuries and fatalities.
Analyze accident causes and contributing factors.
Explore the impact of weather and road conditions.
Study accident distribution across different vehicle types.
Develop an interactive dashboard using Power BI.

📊 Dataset Overview



Attribute
Details




Total Records
500


Total Columns
13


Cities Covered
20


States Covered
15


Date Range
2 January 2023 – 27 December 2024


Dataset Type
Synthetic / Simulated



Dataset Attributes
The dataset contains the following attributes:



Column
Description




Accident_ID
Unique accident identifier


Date
Date of accident


Time
Time of accident


City
City where accident occurred


State
State where accident occurred


Accident_Severity
Severity classification


Accident_Cause
Recorded contributing factor


Weather_Condition
Weather during accident


Road_Condition
Road condition


Vehicle_Type
Type of vehicle involved


Vehicles_Involved
Number of vehicles involved


Injuries
Number of injuries


Fatalities
Number of fatalities




Note: The dataset is synthetic/simulated and is not an official extract from NCRB, MoRTH or any traffic-police database. All findings represent patterns within this dataset and should not be interpreted as official Indian road accident statistics.

🧹 Data Cleaning and Preprocessing
The raw dataset was processed using Python and Pandas to improve data quality and consistency.
The preprocessing workflow includes:

Checking and handling missing values.
Identifying and removing duplicate records.
Removing duplicate accident identifiers.
Standardizing categorical and text values.
Converting date and time columns into appropriate formats.
Converting numerical attributes into suitable data types.
Identifying invalid values.
Validating the cleaned dataset.

Input Dataset: traffic_accidents_raw.csv
Output Dataset: traffic_accidents_cleaned.csv
📈 Exploratory Data Analysis – Key Findings
The analysis of the 500 accident records produced the following observations.
1. Overall Accident Statistics



Metric
Total




Total Accidents
500


Total Vehicles Involved
1,264


Total Injuries
2,031


Total Fatalities
20



2. Year-wise Analysis

2023: 250 accidents
2024: 250 accidents

Both years have an equal number of accident records.
3. Monthly Analysis

Highest accident month: July – 50 accidents.
Lowest accident month: June – 29 accidents.

4. Accident Severity



Severity
Accidents
Percentage




Minor
244
48.8%


Moderate
174
34.8%


Severe
65
13.0%


Fatal
17
3.4%



5. City-wise Analysis
Cities with the highest recorded accident counts:



City
Accidents




Delhi
36


Bhopal
33


Visakhapatnam
31


Kochi
31


Indore
31



6. Accident Causes
Most frequently recorded accident causes:



Accident Cause
Records




Speeding
79


Weather
77


Drunk Driving
75


Distracted Driving
73


Poor Road Condition
72



7. Weather Conditions

Rain: 110
Overcast: 109
Cloudy: 97
Clear: 92
Fog: 92

8. Vehicle Type Analysis

Bus: 80
Car: 77
Van: 74
Truck: 74
Auto Rickshaw: 67
SUV: 64
Motorcycle: 64

These results are descriptive findings from the available dataset. They do not establish causation or account for exposure factors such as population, traffic volume or road mileage.
📊 Power BI Dashboard
An interactive dashboard is being developed using Microsoft Power BI to visualize the analysis results.
Planned Dashboard Components

Accident Overview: KPI cards displaying total accidents, injuries, fatalities and vehicles involved.
Monthly Accident Trends: Line chart showing changes in accident frequency over time.
City-wise Analysis: Bar chart highlighting cities with the highest recorded accident counts.
Accident Severity: Donut chart showing the distribution of accident severity.
Accident Cause Analysis: Visualization of frequently recorded accident causes.
Weather Analysis: Accident distribution across weather conditions.
Vehicle Type Analysis: Comparison of accident counts by vehicle category.
Road Condition Analysis: Analysis of accidents across different road conditions.
Interactive Filters: Filters for year, state, city and accident severity.

The completed dashboard will be included in the project deliverables as Dashboard.pbix.
🔄 Project Workflow

Data Collection and Understanding
Data Cleaning and Preprocessing
Exploratory Data Analysis
Statistical Analysis
Data Visualization
Pattern and Trend Identification
Power BI Dashboard Development
Insights and Interpretation

🛠️ Technologies Used



Technology
Purpose




Python
Data processing and analysis


Pandas
Data manipulation and cleaning


NumPy
Numerical operations


Matplotlib
Data visualization


Seaborn
Statistical visualization


Jupyter Notebook
Analysis environment


VS Code
Development environment


Microsoft Power BI
Interactive dashboard


Git & GitHub
Version control and collaboration



📁 Repository Structure
TrafficAccidentsAnalysis/
│
├── data/
│   ├── traffic_accidents_raw.csv
│   ├── traffic_accidents_cleaned.csv
│   └── data_dictionary.xlsx
│
├── docs/
│   ├── data_sources.md
│   └── project_documentation.md
│
├── notebooks/
│   └── data_analysis.ipynb
│
├── proposal/
│   └── project_proposal.pdf
│
├── results/
│   ├── analysis_summary.md
│   ├── cleaning_report.md
│   └── analysis_results.csv
│
├── scripts/
│   ├── data_cleaning.py
│   ├── data_analysis.py
│   └── data_visualisation.py
│
├── Dashboard.pbix
├── README.md
└── LICENSE

Note: The structure above describes the intended project organization. Refer to the repository for the actual available filenames and folders.
⚠️ Limitations

The dataset is synthetic/simulated rather than verified official accident data.
The analysis is limited to 500 records.
City-level accident counts are not normalized by population or traffic volume.
The dataset has a limited number of attributes and categories.
Recorded contributing factors do not establish direct causation.

🚀 Future Scope

Incorporate verified government traffic accident datasets.
Expand the dataset to cover more locations and years.
Implement geographic accident hotspot visualization.
Perform deeper statistical and correlation analysis.
Enhance the Power BI dashboard with additional interactive features.
Explore predictive analytics using suitable, representative datasets.

👥 Project Development
Developed collaboratively by a team of three students as part of the Data Analytics and Visualization (DAV) semester project.
📄 License
This project is licensed under the Apache License 2.0. Refer to the LICENSE file for details.

Traffic Accident Data Analysis | DAV Semester Project

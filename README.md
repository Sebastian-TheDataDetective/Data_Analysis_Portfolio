# Data_Analysis_Portfolio_Projects
# Introduction
Hiya !!

Welcome to my Portfolio. My name is Sebastian Lotanna Nnorom and I am excited to share my data analysis projects here!

I have a technical/research background and hold a PhD in Petroleum Geoscience from The University of Manchester, with a major in 3D Seismic Interpretation of fluid flow features (Sandstone Intrusions or Sand Injectites). After about a year of transitioning from geoscience to Data Analysis, due to my passion for working with numbers, I am currently searching for opportunities (internships and full-time jobs) to improve and apply my data skills. I have over the past year acquired the necessary skills needed to kickstart my new found interest in data analysis.

In subsequent sections, I will provide a brief description and summary of my projects. The projects will demonstrate the following skills: cleaning and preparing data for analysis, analysing data to identify trends, querying a relational database with SQL and creating data visualisation and dashboards. These projects were carried out using the following tools: EXCEL, TABLEAU, PYTHON, SQLite.

Finally, this repository serves as a means to showcase my data skills, and a platform to share my projects and track my progress in data analysis.

# Projects
## Project 1: Explore a Dataset on Energy Usage and Draw Conclusions

**Worksheet:** [AusEnergy Demand Analysis.xlsx](https://github.com/Sebastian-TheDataDetective/Data_Analysis_Portfolio/files/11343021/AusEnergy.Demand.Analysis.xlsx)

**Description:** In this project, dataset from a domestic and industrial energy supplier (**AusEnergy**) was analyzed to understand how to efficiently manage supply of electricity. In other to achieve the above, some important questions were raised based on the available data, to guide my analaysis. These questions include:

**i).** What does demand look like over time? - To show and understand how demand varies over time (day of week/month/year). 

**ii).** What does extreme demand look like, and under what circumstances does it happen? - To identify/highlight what happens during extreme demand, what causes it and when it does happen. 

**iii).** How do factors like weather and holidays affect demand? - To understand how/if weather conditions and holidays affect demand

The project includes the following steps: data loading; data cleaning, sorting and formatting, data visualization

**Skills:** Data cleaning and preprocessing; Data analysis; Data visualization; Pivot tables; Formulas and functions, Data validation

**Technology/Tools:** Microsoft Excel, Google Sheets


## Project 2: Create a Dashboard Meeting Business Requirements

**Tableau Public Dashboard:** https://public.tableau.com/views/Project2_DentalPharma_Corrected/Dashboard1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link  

**Tableau Public Data Story:** https://public.tableau.com/views/Project2_DentalPharma_Corrected/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link 

**Description:** In this project, a dashboard was created to meet business requirements by applying requirement gathering and capture to implement the expected dashboard design. The project was aimed at standardizing the monitoring of various projects within a pharmaceutical company (**Dental Pharma**). As such, the goal was to use data visualization to keep track of how projects (IT & Marketing) are doing, to measure current and future project performance. In addition, the dashboard will help make strategic project data visually accessible to stakeholders (each with restricted access) which includes the General Manager (see all projects), Regional Manager (see projects in their region), and Country Manager (view indicators of projects in their country). The key dashboard requirements were: 

**1. Projects:** Show which projects are running/have run in which countries (i.e. map showing the countries that Dental Pharma operates in; table of the projects, showing the region, country, country type, project type, phase, date,     planned and actual cost, planned and actual duration).

**2. Countries Over Cost:** Identify countries with a 15% difference between actual costs versus target cost. This difference should be adjustable by the user (i.e. chart showing countries where the cost has overrun)

**3. Countries Over Duration:** Identify countries with a 15% difference between actual duration versus target duration. This difference should be adjustable by the user (i.e. chart showing countries where the duration has overrun).

**4. Countries Under Delivering:** Identify countries with a 15% difference between actual deliverable versus target deliverable. This difference should be adjustable by the user (i.e. chart showing countries under-delivering - where the
deliverables are below the target).

**Skills:** Business requirements gathering, capture and analysis; Design implementation; Interactive dashboard design; User experience (UX) design; Qualitative and quantitative data interpretation; Data transformation and calculation; Data integration; Data visualization; and Data storytelling

**Technology/Tools:** Tableau



## Project 3: Assess the Quality of a Dataset for a Public Service Agency

**Code:** [Camden_Tree_Data Quality Report_Project 3.md](https://github.com/Sebastian-TheDataDetective/Data_Analysis_Portfolio/files/11602583/Camden_Tree_Data.Quality.Report_Project.3.md)

**Presentation:** [Project 3_presentation_032023.pdf](https://github.com/Sebastian-TheDataDetective/Data_Analysis_Portfolio/files/11602247/Project.3_presentation_032023.pdf)

**Data source list:**  [Data_Source_List.pdf](https://github.com/Sebastian-TheDataDetective/Data_Analysis_Portfolio/files/11602201/Data_Source_List.pdf)

**Data requirements:** [Data_Requirements_Template.pdf](https://github.com/Sebastian-TheDataDetective/Data_Analysis_Portfolio/files/11602197/Data_Requirements_Template.pdf)


**Description:** In this project, the quality of three datasets {Trees Data (excel), Common Names Data (.json), and Environmental Data (.csv)} required by a public service agency (**Camden Council**) was assessed to ascertain if the datasets contain the required data and information needed by the council to strategically deliver its planned projects (i.e. Public Tree Data, Tree Walk Brochure, and Environmental Report). 

The aim of this project was to evalaute the datasets and determine the extent to which it is possible to use the datasets to deliver the three proposed projects. The assessment of data quality was carried out using various functions {e.g. .head(); .shape(); .column(); .dtype(); .value_counts(); .describe(); .unique(); .isnull(); .isin(), etc.} in python. 

**Skills:** Python programming; Requirement gathering and analysis; Exploratory data analysis (EDA); Data visualization; Detecting data anomalies and dealing with outliers (i.e. data validation and reliability checks); and Data profiling  

**Technology/Tools:** Python, Pandas, Numpy, Matplotlib, Seaborn


## Project 4: Retrieve User Activity Data on an Online Forum Using SQL

**Code:** [chat_data_student_Project 4.md](https://github.com/Sebastian-TheDataDetective/Data_Analysis_Portfolio/files/11604274/chat_data_student_Project.4.md)

**Normalized entity relationship diagram (ERD):** [DBMS_Entity relationship diagram_ERD.pdf](https://github.com/Sebastian-TheDataDetective/Data_Analysis_Portfolio/files/11604397/DBMS_Entity.relationship.diagram_ERD.pdf)

**Presentation:**  [Project 4_ presentation_2023.pdf](https://github.com/Sebastian-TheDataDetective/Data_Analysis_Portfolio/files/11604417/Project.4_.presentation_2023.pdf)

**Description:** In this project, SQL was used to query user activity (interaction) data from an online forum (**ChatData**) to learn how their website is being used in the real world, to understand which features are useful to the users and what additional features might be worth introducing at a later time. This was accomplished using three separate CSV files consisting of user activity data: posts, comments and users.

SQL queries were executed on the available data to provide answers to the business questions raised by the Social Media Manager by creating single-table and cross-table queries to analyze user engagements. The following steps were taken:

   **1.** Create an entity relationship diagram (ERD)

   **2.** Create database (SQLite database) and add data

   **3.** Create single-table queries to analyze engagement (e.g. Find the 5 posts with the highest viewcount; What are the top 5 locations of users?; How many posts have 2 comments or more?)

   **4.** Create cross-table queries to further analyze engagement (e.g. Considering only the users with an "AboutMe," how many posts are there per user?; Who are the top 10 users who comment the most?)

**Skills:** SQL; Python programming; Requirement gathering and analysis; Data retrieval and analysis; Query optimization; Database management; Data exploration; Data validation; Data privacy and security  

**Technology/Tools:** SQLite, Python, Pandas, Numpy  

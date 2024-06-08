HR Analytics Case Study in Power BI

The HR Analytics case study, aims to build a comprehensive HR analytics report for Atlas Labs, a fictional tech company. The primary focus is on monitoring key employee metrics and understanding factors affecting employee attrition.

Objective and Process Overview

The main objective of this case study is to apply existing knowledge to create an interactive HR analytics report. This involves an end-to-end report development process in Power BI, which consists of four key steps: building the data model and analyzing data, report design, preparing to share the report, and sharing the report with stakeholders. This case study emphasizes the first two steps: building the data model and report design.

Building the Data Model

The process begins with requirements gathering, where the specific needs of Atlas Labs' HR team are identified. Following this, the data sources are connected, and data transformation is carried out to clean and prepare the data for analysis. The data model is built using the Kimball Model approach, which involves creating relationships between different tables, specifically a fact table and multiple dimension tables.

The fact table, central to the data model, stores performance ratings and contains information about employees' yearly reviews. This table is essential for managing employee performance and contains 11 different columns with multiple rows per employee. Alongside the fact table, there are several dimension tables providing additional context, including Employee, EducationLevel, RatingLevel, SatisfiedLevel, and Date tables.

Report Design

The second step in the process is report design, which includes branding, defining the report layout, and building chart visualizations. Branding involves customizing the report to align with Atlas Labs' identity. The report layout is structured for easy navigation and comprehension, while chart visualizations are created to represent data insights effectively.

Key Insights and Data Model

Throughout the case study, several key insights are uncovered. For instance, Atlas Labs has employed 1,470 people, with over 1,200 active employees at the time of data collection. As expected for a software company, the largest department is Technology. The company's attrition rate is 16%, prompting further questions about employee satisfaction and competitiveness as an employer.

The final data model follows a snowflake schema, with one dimension table not directly connected to the fact table, efficiently organizing the data and providing context through dimension tables.

Metadata Sheet

The metadata sheet is a crucial component, providing helpful context for each table and column within the dataset. It aids in understanding the structure and content of the data being analyzed.

Final Dashboard and Recap

The final interactive dashboard allows the Atlas Labs HR team to navigate key metrics around employees easily. This enables informed decision-making on various aspects, including hiring, diversity, inclusion, performance, and attrition. The case study concludes with a recap of the topics covered, emphasizing data modeling, exploratory data analysis, DAX functions, and report design, showcasing the potential of Power BI in creating reusable and interactive HR reports.


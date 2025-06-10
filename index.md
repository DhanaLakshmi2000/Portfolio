---
layout: default
title: Dhanalakshmi Nangunuri
---

# Dhanalakshmi Nangunuri

## About Me
I’m a versatile Data Engineer with over 3 years of experience designing and optimizing scalable data pipelines, workflow automations, and analytics solutions across enterprise environments. My expertise spans cloud-native platforms like Microsoft Fabric, Azure, and Google Cloud, where I’ve developed robust ETL/ELT workflows using tools such as Dataflows Gen2, Airflow, PySpark, and Snowflake.

My work is centered on building clean, auditable, and performance-driven data systems that transform business operations—from automating ingestion pipelines to surfacing actionable insights in Power BI and Tableau. I have strong foundations in SQL, Python, DAX, and dimensional modeling (Star/Snowflake schemas, SCD), with hands-on experience implementing data quality frameworks and CI/CD automation using GitHub Actions and Azure DevOps.

Beyond pipelines and code, I thrive on cross-functional collaboration, having worked closely with product, QA, and engineering teams to deliver impactful solutions that meet real-world needs. Whether it’s automating Jira analytics, streamlining healthcare ingestion, or visualizing KPIs, I approach every project with a mindset focused on efficiency, data integrity, and business alignment.

- **email -** nangunuri.dhanalakshmi@gmail.com
- [LinkedIn](https://www.linkedin.com/in/dhanalakshmi-nangunuri/)

## Key Strengths
**Big Data Ecosystems:**	Apache Spark, Google BigQuery, Snowflake, Microsoft Fabric, Delta Lake
**Databases:** Snowflake, Azure SQL Database, Google Cloud BigQuery, MySQL, Oracle, SQL Server
**Languages:**	SQL, Python, PySpark, Java, DAX
**Cloud Computing:**	Microsoft Azure (Data Factory, Dataflows, Synapse), Google Cloud Platform (GCP), AWS 
**ETL & Reporting:**	Azure Data Factory, Snowflake Tasks & Streams, Microsoft Fabric Pipelines, Apache Airflow, Power BI, Tableau, Python
**CI/CD:**	GitHub Actions, Azure DevOps, Git
**Defect Management Tools:**	Jira, Azure Boards 
**Others:**	Dimensional Modeling (Star/Snowflake schema), SCD, Data Quality Frameworks, Orchestration Tools (Airflow, Control-M)
**Operating Systems:**	Windows, Linux 

## Professional Highlights
- Designed and implemented scalable data pipelines using Microsoft Fabric, Snowflake, and Apache Spark, enabling seamless ingestion and transformation of enterprise data across cloud 
 platforms.
- Developed end-to-end ELT workflows with Azure Data Factory, Snowflake Tasks, and Google BigQuery, ensuring structured and auditable data delivery for advanced analytics.
- Built automated orchestration workflows using Apache Airflow and Control-M, improving scheduling reliability and reducing system downtime for complex data operations.
- Engineered and enforced data quality frameworks involving validation rules for nulls, duplicates, referential integrity, and formatting—enhancing data trust and business reporting 
  accuracy.
- Created dynamic, real-time dashboards in Power BI and Tableau to visualize performance metrics, SLA adherence, and pipeline health, empowering decision-making with actionable insights.
- Designed robust dimensional data models using Star Schema, Snowflake Schema, and Slowly Changing Dimensions (SCD) to support historical tracking and cross-domain analytics.
- Automated CI/CD deployments for data pipelines using GitHub Actions and Azure DevOps, ensuring seamless delivery across development, staging, and production environments.
- Collaborated with cross-functional teams to translate business requirements—especially in compliance-heavy industries—into technical specifications that improved accessibility and 
  usability of data systems.
- Achieved a 30% reduction in resolution time and significantly improved operational efficiency through automation, monitoring, and optimization of data ingestion frameworks.

## Career Goal: 
To leverage my expertise in data engineering, cloud integration, and automation to build intelligent, scalable, and secure data solutions that drive real-world impact. I aim to contribute to organizations that prioritize innovation, efficiency, and data integrity—while continuously evolving my skills in modern platforms like Microsoft Fabric, Power Platform, Snowflake, and Apache Spark. My long-term goal is to lead cross-functional data initiatives that align technology with strategic business outcomes.

## Professional Experience

**University of Central Missouri - Graduate Research Assistantship-** MO,US | April 2023 - April 2024
- Designed and implemented an end-to-end data pipeline using Microsoft Fabric to extract, process, and analyze Jira tickets for identifying performance-related issues across multiple engineering teams.
- Ingested ticket data from Jira’s REST API using Dataflows Gen2, and stored structured outputs in OneLake Lakehouse (Bronze layer) for further processing.
- Developed data cleaning workflows with Power Query and normalized ticket details (e.g., summary, tags, resolution time) into Silver-layer tables.
- Built a keyword-based classifier using PySpark in Notebooks to flag tickets related to performance issues by analyzing text patterns in summaries and descriptions.
- Created calculated fields (e.g., % performance-related, avg resolution time) and promoted enriched insights into the Gold layer for reporting.
- Developed an interactive Power BI dashboard within Fabric to visualize ticket trends, team-wise distributions, and hotspots for recurring performance concerns.
- Automated data refresh cycles using Fabric Pipelines and monitored the entire process via Lineage View and trigger-based alerts.
- Resulted in a 30% reduction in mean time-to-resolution for performance-related tickets and enabled targeted optimization efforts.


**Advanced Business and Health Care Solutions — Associate Software Engineer -** Bangalore, India | Feb 2022 – Jul 2023 
-	Engineered a scalable PySpark-based ingestion framework that automated file ingestion from Dropbox into Hive data lakes, reducing manual data onboarding time by 70%.
-	Developed reusable shell and HiveQL scripts to support ingestion pipelines across 5+ product lines, enabling metadata-driven processing with consistent data quality enforcement.
-	Implemented parameterized ingestion logic via .properties files (e.g., delimiters, headers, key fields), increasing ingestion flexibility and enabling support for 10+ file formats without code rewrites.
-	Automated daily ingestion workflows using Zena job scheduler, ensuring timely and reliable ingestion of critical datasets including high-priority eApp submissions with zero SLA breaches.
-	Designed robust batch control utilities (batch_open.sh, batch_close.sh) to enforce process windows, monitor job states, and ensure end-to-end data integrity across all ingestion layers.
-	Enabled real-time KPI validation during ingestion through kpi_run.sh, providing immediate insights into operational and compliance metrics at data landing time.
-	Standardized ingestion directory structures and logic through detailed documentation and PoC collaboration (e.g., Value Momentum PoC), accelerating future onboarding by 40%.
-	Established resilient logging and repair mechanisms to support self-healing pipelines, while promoting modular design for rapid scalability and easy maintenance across ingestion environments.


**The Internship Studio — ML Intern -** Hyderabad, India | Jul 2020 - Aug 2020 
- Performed EDA on car datasets using Python (Pandas, Matplotlib, Seaborn); cleaned data, handled missing values and outliers, and applied feature engineering (correlation analysis, one-hot encoding, scaling) to improve dataset quality.
- Built and evaluated ML models including Linear/Polynomial Regression, SVM, Decision Trees, and Random Forest to predict car prices; optimized using R², MSE, and feature importance analysis.
- Reduced processing time through workflow optimization; visualized predictions and insights using Tableau and Matplotlib; delivered findings via interactive dashboards and stakeholder reports.

## Projects

### [Exploratory Data Analysis of Car](https://github.com/DhanaLakshmi2000/EDA_OF_CAR) 
**Objective:** Conducted an advanced exploratory data analysis to uncover key trends and factors influencing car prices in the U.S. market, leveraging data-driven insights to support strategic decision-making in the automotive sector.
- **Tech Stack:** Python (Pandas, NumPy), Visualization Tools (Seaborn, Matplotlib), Jupyter Notebook
- **Algorithms Used:** Linear Regression,Polynomial Regression, Support Vector Machine,Decision Trees,Random Forest.
- Identified key factors influencing car prices, such as brand, year, and mileage, providing actionable insights for market trend analysis.
- Executed comprehensive exploratory data analysis on 50,000+ automotive records using Python (Pandas, NumPy) and visualization tools
- Developed machine learning models using scikit-learn (Linear Regression, Random Forest, SVM) achieving 85% prediction accuracy
- Created interactive dashboards using Matplotlib and Seaborn to visualize key market trends and price indicators
- Engineered feature preprocessing pipeline reducing data preparation time by 60% and improving model performance


### [Exploring GCP Components for Data Ingestion & Analytics](https://docs.google.com/document/d/1I1qZivY2eeWfimANRpndZVb44Ti-bAqFSTgPSqB-YH4/edit?usp=sharing)
**Objective:** Designed and implemented a scalable data pipeline to ingest Yelp batch data from Google Cloud Storage (GCS) into BigQuery using Airflow DAGs and Dataflow. 
**Tech Stack:** GCP (BigQuery, GCS, Composer, Dataflow), Apache Beam, Python
-  Designed and implemented scalable data pipelines for ingesting and processing large-scale datasets, including Yelp business reviews and real-time insurance claims.
- Architected a fault-tolerant claims processing system using Apache Airflow, Apache Spark, and Apache Kafka, improving data accuracy to 80% and significantly reducing manual intervention.
- Orchestrated end-to-end ETL workflows using Airflow to schedule, monitor, and manage tasks such as ingestion, validation, enrichment, and routing.
- Developed Spark jobs in Python for distributed data transformations, ensuring real-time stream processing and high throughput via Kafka integration.
- Leveraged Google BigQuery to store cleansed and validated data, applying referential integrity constraints and keys to reduce inconsistencies by 30%.
- Collaborated with data science teams to integrate a fraud detection model within the Spark pipeline, achieving 95% accuracy in identifying suspicious claims and cutting manual review time by 50%.
- Integrated pipeline outputs with legacy claims management systems using custom Python scripts and SQL-based data exchange for seamless adjudication and payment workflows.
- Tuned Spark jobs through smart partitioning, caching, and resource optimization, achieving a 30% improvement in overall processing speed.
- Embedded SQL-based data quality checks and compliance rules within Spark pipelines to ensure data reliability and regulatory adherence.
- Developed unit tests and validation checks as part of a CI/CD pipeline to prevent data anomalies in production, reducing error rates by 40%.
- Monitored and maintained pipeline reliability via Airflow’s web UI and custom dashboards, proactively identifying and resolving bottlenecks.

### Library management system
**Objective:** Developed a web-based application for managing library resources and user interactions.
- **Tech Stack:** HTML, CSS, JavaScript, PHP, SQL
- Delivered a dynamic, user-friendly system with secure authentication and efficient database management.

### Exchequer
**Objective:** Collaborated with a multi-site Agile team to implement new MFA functionality and improve system reliability.
- **Role:** Implemented features in Java, conducted unit and integration testing, resolved bugs, and maintained version control using Git.
- **Tech Stack:** Java, C/C++, Git

### [Chess Game: AI and Gameplay Development](https://github.com/DhanaLakshmi2000/chess)
**Objective:** Built a fully functional chess game with AI capabilities and an intuitive user interface.
- **Tech Stack:** Python, Pygame, Minimax Algorithm with Alpha-Beta Pruning
- Designed and implemented chess rules and movement validation for all pieces.
- Developed an AI opponent using the Minimax Algorithm, enhancing decision-making through Alpha-Beta Pruning.
- Created a graphical user interface using Pygame, providing an engaging player experience.
- Integrated multiplayer functionality and move tracking to enable detailed game analysis.
  
## Publications

- **A Platform-Agnostic Framework for Automatically Identifying Performance Issues Reports with Heuristic Linguistic Patterns -**
 -  **Role: -** Data Validator
  - **Description: -** Collaborated with a professor on a paper published on IEEE Xplore. Assisted in validating data to support the development of a framework for automatically identifying performance issues in reports using heuristic linguistic patterns.
- [Check it out!](https://ieeexplore.ieee.org/abstract/document/10504708)

## Certifications
-[Microsoft Fabric Data Engineer Associate](https://learn.microsoft.com/api/credentials/share/en-us/DhanalakshmiNangunuri-3778/D50CCCA79ABC2CDC?sharingId=70F1A013760D651E)
-[Microsoft Azure Developer Associate](https://learn.microsoft.com/api/credentials/share/en-us/DhanalakshmiNangunuri-2469/5425A5F070CEE857?sharingId=B59773C27A6A96F1
)
-[professional technical training in Certificate Program in Data Science]( https://verifyawards.stackroute.in/verify?url=https://awards.stackroute.in/public/assertions/h8rmMhhXRmmUWGbofK_ziQ.json?v=2_0 )
- [Sql and Relational Databases 101 ](https://courses.cognitiveclass.ai/certificates/4b37b68f2359422e9876e95af1a797de)
- [Java 8 Practical approach](https://www.udemy.com/certificate/UC-f32165eb-82ec-4bb6-a45a-99e925195897/)
  

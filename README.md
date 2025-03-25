# data-analyst-abdur
Project Title: Descriptive Analysis of Water Systems in the City of Vancouver

Objective: To analyze water quality in Vancouver by examining turbidity levels relative to temperature, identifying key trends, and providing actionable insights for system optimization.

Dataset: Data from the City of Vancouver on water systems, operating permits, and water quality reports.
Includes 524 instances with details on address, mechanical system type, operating permit number, permit status, and system report date.
Contains temperature and turbidity data for 2025.

Methodology
1. Data Collection and Preparation: Data stored in Amazon S3 buckets: raw (cov-raw-abd), transformed (cov-trf-abd), and curated (cov-cur-abd).
AWS Glue Data Brew used for data cleaning, handling missing values, and normalizing schemas.
AWS Glue Crawler used to catalog and structure data in a cloud database.
2. Descriptive Statistics:
Summary of turbidity values: minimum, average, and trends relative to temperature.
Identifying patterns in water quality through statistical measures.
3. Data Visualization:
Graphs illustrating temperature vs. turbidity relationships.
Trend lines showing changes in turbidity levels based on temperature fluctuations.
4. Customer Segmentation:
Segmentation based on permit types and water system classifications.
Identifying key risk areas in water quality management.
5. Insights and Findings:
The lowest recorded turbidity is 0.12 at 15.3°C.
The highest average turbidity is 0.72 at 12.8°C, indicating temperature influence.
A positive correlation between turbidity and temperature up to 14.5°C, after which it reverses.
6. Recommendations:
Monitor water quality closely in areas with high turbidity at lower temperatures.
Adjust filtration and treatment processes based on seasonal temperature shifts.
Improve data collection processes to minimize missing values and improve predictions.
Tools and Techniques:
AWS Services: S3, Glue Data Brew, Glue Crawler, ETL pipelines.
Data Processing: ETL pipeline with AWS Glue, Data Cleaning with Data Brew.
Data Storage: Cloud-based AWS databases, S3 buckets.
Visualization: Graphical representation of trends using data visualization tools.
Deliverables:
Cleaned and Processed Dataset stored in S3 with CSV and Parquet outputs.
Descriptive Analysis Report detailing water quality trends.
Visualizations and Dashboards for turbidity analysis based on temperature.
Recommendations Document for improving water quality monitoring.

Project Description: Diagnostic Analysis of Water System Issues in the City of Vancouver
Project Title: Investigating Water System Quality and Infrastructure in Vancouver
Objective: The primary objective of this project is to conduct a diagnostic analysis of the water system in Vancouver to identify underlying issues affecting water quality and system infrastructure. This includes examining active and inactive mechanical systems, identifying bacterial contamination, and ensuring proper security and governance measures for data integrity. The goal is to provide actionable insights for the City of Vancouver to implement improvements.
Background: The City of Vancouver maintains a complex water distribution system that includes multiple mechanical subsystems such as cooling towers, building water treatment systems, decorative water features, and rainwater harvesting systems. Recent assessments have highlighted concerns regarding inactive systems, bacterial contamination, and potential data security vulnerabilities. This analysis aims to pinpoint critical issues and provide recommendations for mitigating risks and improving overall water quality and system efficiency.
Dataset: The analysis will leverage multiple datasets, including:
Water System Data: Information on mechanical systems, including active and inactive counts for different system types.
Bacterial Contamination Data: Records identifying instances of Legionella pneumophila in various mechanical systems and their locations.
Security Implementation Data: Logs related to encryption, replication, and governance measures applied to protect data integrity.
Governance and Monitoring Data: Compliance checks, data completeness assessments, and AWS monitoring logs to track changes and anomalies.
Methodology:
Data Collection and Preparation:
Gather and clean datasets from multiple sources, ensuring accuracy and consistency.
Normalize data for analysis.
Trend Analysis:
Analyze trends in active versus inactive mechanical systems.
Identify water features with the lowest active percentages and potential operational inefficiencies.
Correlation Analysis:
Identify relationships between inactive systems and their impact on water quality.
Examine links between bacterial contamination and specific mechanical systems.
Use statistical methods such as regression analysis to quantify the impact of inactive systems on water quality concerns.
Root Cause Analysis:
Investigate the factors leading to inactive systems and potential technical failures.
Conduct in-depth analysis of bacterial contamination, identifying high-risk locations and patterns.
Utilize the "5 Whys" and Fishbone Diagram methodologies to determine core causes.
Segmentation Analysis:
Segment mechanical systems based on their activity levels and operational efficiency.
Categorize bacterial contamination by severity and geographical distribution.
Synthesis of Findings:
Integrate quantitative and qualitative data to identify critical patterns and key insights.
Summarize actionable recommendations to address issues in water quality and infrastructure management.
Tools and Techniques:
Data Analysis Tools: SQL (Amazon Athena), Python (Pandas, Scikit-learn) for data extraction and correlation analysis.
Data Security Tools: AWS Key Management Services (KMS), S3 encryption, and bucket versioning for data protection.
Monitoring Tools: AWS monitoring systems for anomaly detection and alert generation.
Visualization Tools: Tableau or Power BI for presenting trends and insights.
Deliverables:
A comprehensive diagnostic report detailing analysis results, key findings, and identified issues.
Visualizations and dashboards summarizing water system trends and bacterial contamination risks.
Actionable recommendations for improving water system quality and security measures.
Timeline:
Week 1-2: Data collection, cleaning, and initial trend analysis.
Week 3: Correlation analysis and root cause investigation.
Week 4: Segmentation and synthesis of findings.
Week 5: Development of recommendations and report preparation.
Week 6: Final review, stakeholder presentations, and implementation planning.
This diagnostic analysis aims to provide a structured understanding of the challenges within the Vancouver water system, guiding the City towards effective solutions to enhance water quality and system efficiency.

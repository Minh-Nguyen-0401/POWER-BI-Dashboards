
### Technical-Support-Dashboard-Development-&-Analysis-Project
---
#### Project Overview:

This project focuses on developing a Technical Support Dashboard and conducting a comprehensive analysis of the support operations within a business environment. As organizations increasingly depend on technology, the efficiency of technical support becomes crucial to maintaining operational continuity. This project leverages data-driven insights to evaluate and optimize key performance indicators (KPIs) of the Technical Support Center.

#### Project Structure:

- **`README.md`**: Provides an overview and essential details of the project.
- **`Technical Support Dashboards.pbix`**: The main BI development file containing data retrieval, preprocessing, generating calcualted columns and measures, and dashboard building.
- **`Technical Support Dataset - May 2024.xlsx`**: The original dataset provided by [onyxdata.co.uk](https://onyxdata.co.uk/)
- **`Final Outcome`***: A folder containing all deliverables of the project

#### About the Dataset:

The dataset, extracted from the company's technical support system, includes attributes necessary for further metrics generation and evaluating the performance of the Technical Support Center. The dataset features 22 columns include:
- **Status**
- **Ticket ID**
- **Priority**
- **Source**
- **Topic**
- **Agent Group**
- **Agent Name**
- **Created Time**
- **Expected SLA to Resolve**
- **Expected SLA to First Response**
- **First Response Time**
- **SLA for First Response**
- **Resolution Time**
- **SLA for Resolution**
- **Close Time**
- **...**

#### Objectives and Methodologies:

1. **Data Cleaning and Structuring**: Ensuring data quality through cleaning and structuring for subsequent analysis.
2. **Ticket Volume Trends Analysis**: Evaluating ticket volume trends across different time frames and identifying peak activity periods.
3. **Ticket Content and Resolution Analysis**: Analyzing ticket topics, resolution times, and channel effectiveness.
4. **Performance Metrics Evaluation**: Assessing agent performance against SLAs and customer satisfaction ratings.
5. **Visualizing and Reporting Insights**: Creating and saving visual reports to inform strategic decision-making.

#### Languages/Tools Used:

- **Power BI**: <i>(DAX code, Power Query)</i> For metrics generation, dashboard development, and analysis.
- **Excel**: For data collection, intepretation, and preprocessing
---
This project aims to deliver actionable insights to enhance the performance of technical support operations on a daily basis, ensuring better service delivery and improved customer satisfaction.

---
#### Key Findings from the Project:

The analysis of the technical support dataset revealed several critical insights:

1. **Temporal Analysis**: Support requests displayed distinct temporal patterns, with peak volumes in January, May, and November. The highest activity was during weekdays between 2 pm and 4 pm, particularly outside standard working hours (9 am to 5 pm). These after-hours requests experienced quicker responses, averaging 9.34 minutes ahead of the expected schedule.

2. **Results Tracking**: Approximately one-third of requests failed to meet service level agreements (SLAs), highlighting potential areas for improvement. Only one-eighth of the tickets met the SLA for first responses, indicating a need for more prompt initial engagement. Despite an 82% closure rate, the average customer satisfaction score was 3.51 out of 5, with significant variance across different ticket types.

3. **Issue Analysis**: "Product setup" was the most common issue, followed by "Pricing" and "Licensing." However, "Training Requests" were significantly less frequent. The majority (71%) of issues related to "Ready to Use Software" and "Custom Software Development," indicating a need to bolster expertise in these areas to improve customer satisfaction.

4. **Location & Channel Analysis**: The majority of ticket submissions originated from Germany, Italy, and Poland, accounting for 50% of the total. Email and chat were the most used channels, representing 89% of all submissions, suggesting the need for resource optimization in these support areas.
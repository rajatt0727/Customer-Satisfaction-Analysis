## Project Overview

This project aims to analyze a **call center dataset** using Power BI to provide valuable insights based on key performance indicators (KPIs) related to call center operations. The analysis focuses on understanding call volume, agent performance, customer satisfaction, and call resolution metrics to help improve overall efficiency and customer experience.

## Steps Followed for Data Preparation and Analysis
1. **Data Cleaning in Power BI**:
   - Replaced all `null` or blank values with `0` in relevant columns.
   - Ensured proper data types for columns:
     - Date and Time columns were formatted to the correct date-time format.
     - Columns such as `SATISFACTION RATE`, `SPEED OF ANSWER`, and `AVG. TALK DURATION` were converted to numeric formats.
   - Created a new column `Duration on Calls`, extracting minutes and seconds from `AVG. TALK DURATION`.

2. **Data Transformation**:
   - Added calculated columns:
     - **Total Calls Answered vs. Rejected**: Based on the "ANSWERED" column (Yes/No).
     - **Resolved vs. Unresolved Calls**: Based on the "RESOLVED" column.
   - Calculated new metrics:
     - **Percentage of Answered and Rejected Calls**.
     - **Top Agents**:
       - Agent who answered the most calls.
       - Agent with the highest satisfaction rate.
     - **Total Call Duration** by each agent.

3. **Analysis Objectives**:
   The project focused on visualizing:
   - **Total Number of Calls**: The total call volume for 2021.
   - **Calls Answered vs. Rejected**: Breakdown of calls that were answered vs. rejected.
   - **Resolved vs. Unresolved Calls**: A metric showing how many calls were resolved successfully.
   - **Agent Performance**:
     - The agent who answered the most calls.
     - The agent with the highest satisfaction rate.
   - **Topic-Wise Call Volume**: Visualizing the number of calls based on different topics.
   - **Call Duration**: Duration of calls per agent.
   - **Call Volume by Day/Month**: Analyzing call volume trends over the days and months of 2021.
   - **Overall Satisfaction for 2021**: A summary of performance based on satisfaction ratings.

4. **Power BI Visualizations**:
   - **Bar Chart**: Displays the total number of calls by topic.
   - **Pie Chart**: Shows the percentage of answered vs rejected calls.
   - **Line Chart**: Tracks the duration of calls by agent.
   - **Stacked Bar Chart**: Represents resolved vs unresolved calls by agent.
   - **Slicers**: For interactive filtering by month and day to explore detailed call center performance.

5. **KPI Metrics**:
   - **Total Number of Calls**.
   - **Percentage of Calls Answered vs. Rejected**.
   - **Percentage of Resolved vs. Unresolved Calls**.
   - **Agent Performance**:
     - Top agent based on answered calls.
     - Top agent based on satisfaction ratings.
   - **Topic-Wise Distribution of Calls**.
   - **Call Duration Analysis**: Average call duration per agent.

## How to Use the Power BI Dashboard
1. **Import the Dataset**: Open the `Call-Center-Dataset.xlsx` file in Power BI.
2. **Data Transformation**: Use Power BI’s "Transform Data" functionality to clean, format, and transform the data as described above.
3. **Visualizations**: 
   - Use **bar charts**, **line charts**, and **pie charts** to visualize call data.
   - Use **slicers** to create interactive reports by filtering data by month, day, or agent.
   - Create custom charts to showcase the **2021 overall performance** based on satisfaction ratings.
4. **Exporting Results**: After creating the visuals, you can export the report or share it within the organization.

## Insights Provided by the Analysis
- **Total Call Volume**: Overall calls handled by the call center during 2021.
- **Call Answer Rate**: The percentage of calls that were successfully answered vs rejected.
- **Agent Performance**: Identified top-performing agents based on the number of answered calls and satisfaction ratings.
- **Topic Analysis**: Gained insights into the most common issues/topics handled by agents.
- **Peak Call Times**: Analysis of call volume by day and month to identify busy periods.
- **Performance Ratings**: Overview of the customer satisfaction scores for 2021, enabling the identification of areas for improvement.

## Key Recommendations
- **Staffing Adjustments**: Increase staff during peak call times to reduce call rejection rates.
- **Agent Training**: Focus on agents with lower satisfaction rates to improve customer service.
- **Topic-Specific Action Plans**: Address frequently occurring topics with better resources or specialized training to improve resolution rates.
- **Long-Term Performance Tracking**: Use similar metrics to track performance across future years to monitor improvement.

## Requirements
- **Power BI Desktop**: The dashboard and visualizations are designed using Power BI.
- **Call-Center-Dataset.xlsx**: Contains the data for analysis.

This project provides a detailed analysis of call center operations, helping identify key areas for performance improvement and future growth.


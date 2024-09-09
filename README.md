# Job-Market Analysis Project

## Overview
This Power BI project analyzes job postings to uncover valuable insights into job market trends, skill demand, and industry hiring practices. The dataset includes information on job positions, skills, salaries, locations, and companies, providing a comprehensive view of the current job landscape.

## Dataset Columns:
- **Job Posting ID**: Unique identifier for each job posting.
- **Job Posting Date**: The date the job was posted.
- **Job Title**: The title of the job being advertised.
- **Job Title Full**: The full title of the job.
- **Job Title Additional Info**: Extra details related to the job title.
- **Job Position Type**: Indicates if the position is full-time, part-time, etc.
- **Job Position Level**: The level of the position (e.g., Junior, Mid, Senior).
- **Years of Experience**: Required years of experience for the job.
- **Job Skills**: Skills required for the job.
- **Job Location**: The location where the job is based.
- **Minimum Pay**: Minimum salary for the job.
- **Maximum Pay**: Maximum salary for the job.
- **Pay Rate**: The pay rate type (e.g., hourly, annual).
- **Number of Applicants**: Number of applicants for the job.
- **Company Name**: Name of the company posting the job.
- **Company Industry**: The industry the company belongs to.
- **Company Size**: Size of the company (e.g., small, medium, large).

## Key Analyses Performed:

### 1. Job Posting Trends:
- **Average Years of Experience by Job Position Level**: Calculated the average years of experience required for various job position levels (e.g., Junior, Mid, Senior).
- **Number of Job Postings by Year, Quarter, and Month**: Visualized job posting trends using a **stacked column chart** and **line chart** to show fluctuations over time at different levels of granularity.

### 2. Salary vs. Experience:
- **Experience vs. Salary Analysis**: Explored how required years of experience relate to the offered salary, providing insights into compensation trends for different experience levels.

### 3. Skills Analysis:
- **Count and Percentage of Job Skills by Year and Job Skill**: Analyzed the number of job postings requiring specific skills and calculated the percentage distribution of each skill by year.

### 4. Job Position Level:
- **Job Posting Count by Job Position Level**: Counted the number of postings for each position level (Junior, Mid, Senior).

### 5. Company Analysis:
- **Count of Company Size by Company Industry**: Analyzed the number of companies by size within each industry to provide insights into hiring practices across different sectors.

## Dashboard Layout:
- **Home Page**: A central navigation hub with three options to explore:
  - **Jobs**: Focuses on job trends, experience requirements, and salary analysis.
  - **Skills**: Highlights skill demand and trends over time.
  - **Company**: Provides insights into company size and industry trends.
![HomePage](https://github.com/imttrisha/Job-Market-Analysis/blob/main/pb1.JPG?raw=true)
![Skills Overview](https://github.com/imttrisha/Job-Market-Analysis/blob/main/pb2.JPG?raw=true)

## Tools Used:
- **Power BI**: For data visualization, dashboard creation, and interactivity.
- **Data Cleaning**: Pre-processing the dataset for accurate and meaningful analysis.
- **Stacked Column Chart & Line Chart**: Used to visualize trends over time.
- **Slicer & Drill-down Features**: Added interactivity to filter and explore data at different levels.

## Key Insights:
- **Experience vs Salary**: Senior-level positions typically require more experience and offer significantly higher salaries.
- **Skill Trends**: Certain skills, such as SQL, Python, cloud and AWS show increasing demand over the years.
- **Company Size & Industry**: Larger companies tend to dominate industries like technology and finance, while smaller companies are more common in sectors like education and healthcare.

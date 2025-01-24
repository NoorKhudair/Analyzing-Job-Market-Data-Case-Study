# Analyzing-Job-Market-Data-Case-Study

## Job Market Analysis Dashboard Overview

This Power BI dashboard analyzes job market trends across eight key data-related roles: Business Analyst, Data Analyst, Data Architect, Data Engineer, Data Science Manager, Data Scientist, Machine Learning Engineer, and Research Scientist. The analysis covers over 9,500 job postings from 2017 to 2021.

## Dashboard Pages Structure
![Main Page Preview](Preview/Main%20page.PNG)

### 1. Jobs Page
![Jobs Page Preview](Preview/Jobs%20Page.PNG)

- Tree map showing proportion of job skills in each job title
- Line chart tracking job posting counts over time (2017-2021) for each position level (Associate, Director, Entry level, Executive, Internship, mid-senior level)
- Bar chart showing average years of experience required by each job position level

### 2. Skills Page
![Skills Page Preview](Preview/Skills%20Page.PNG)

- Table showing percentage of each skill in a specific job title
- Line chart tracking skill in postings percentage over time
- Bar chart showing the frequency count of all job skills

### 3. Company Page
![Company Page Preview](Preview/Company%20Page.PNG)

- Scatter plot showing years of experience and posting count by job position level across different industries
- Chart displaying average years of experience by company size
- table showing company names with an associated job title and their job postings

## Filters

All pages can be filtered by:

- Job Title (8 roles including Data Scientist, Data Engineer, Business Analyst, etc.)
- Job Position Level
- Company Name
- Company Size
- Company Industry
- Job Posting Date (range from 1/1/2017 to 12/31/2021)
  
## Questions This Dashboard Can Answer

- Is there an expected experience level for certain position levels?
- Are certain companies targeting particular job types, experience or skills?
- What are top skills needed for entry-level Data Scientists?
  
## Key Findings After Data Exploration

- March 2020 experienced a significant drop in job postings due to the onset of COVID-19
- The Data Scientist has the second highest number of job postings
- Data Analysts have the lowest salary, but over 90% of salary values are missing
- There is a positive correlation between years of experience and job position level
- As years of experience increase so does associated salary

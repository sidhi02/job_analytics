# Job Analytics Internship Project

## Overview

This project was developed as part of the **ElevanceSkills Data Analytics Internship Program** using **Tableau Public**. The objective was to extend the original Job Analytics Dashboard created during training and implement six additional analytical tasks on the same dataset while applying advanced Tableau concepts and business intelligence techniques.

The dashboard enables users to explore job market trends, salary patterns, qualification requirements, hiring preferences, company insights, and geographic distributions through interactive visualizations.

---

## Project Access

🔗 **Access the Complete Tableau Workbook:**  
[Job Analytics Dashboard & Internship Tasks](https://public.tableau.com/app/profile/sidhi.deshmukh/viz/JobAnalytics_17814643461240/Dashboard)

---

## Dataset

**Job Analytics Dataset**

📁 [Access Dataset](https://drive.google.com/drive/folders/1uujqbH61S9yY48lJzzIT4iBKUFef-NeQ?usp=sharing)

The dataset contains job posting information including salary, experience, qualifications, company size, work type, and geographic details used for dashboard development and analysis.

---

## Tools & Technologies

- Tableau Public
- Tableau Desktop
- Data Visualization
- Business Intelligence
- Dashboard Analytics

---

## Dashboard Preview

![Dashboard Overview](images/dashboard.png)

---

## Project Objectives

- Analyze job market trends across multiple regions.
- Explore salary distributions and hiring patterns.
- Compare opportunities across countries and companies.
- Apply advanced filtering and calculated field logic.
- Develop interactive business intelligence dashboards.
  
---

## Data Cleaning

- Removed duplicate records to improve data accuracy.
- Handled missing and null values in key fields.
- Standardized data formats for consistency.
- Converted date fields for time-based analysis.
- Created calculated fields and applied task-specific filters.

---

## Main Dashboard

The primary dashboard provides a comprehensive overview of job posting data through multiple analytical views.

### Key Features

- Company Analysis
- Country Distribution
- Skills Analysis
- Qualification Insights
- Salary Analysis
- Experience Distribution
- Work Type Trends
- Preference Analysis

### Key Insights

- Large organizations contribute significantly to overall job opportunities.
- Technical and professional qualifications dominate the job market.
- Salary levels vary considerably across industries and companies.
- Work preferences are relatively balanced across opportunities.
- Job postings are distributed across multiple countries and regions.

---

# Internship Tasks

## Task 1 — Preference vs Work Type Analysis

### Objective

Analyze the relationship between candidate preferences and internship opportunities.

### Filters Applied

- Work Type = Intern
- Company Size < 50,000
- Salary > $9,000

### Visualization

![Task 1](images/task1.png)

### Insights

- Female preference jobs recorded the highest count (**21,412**).
- Both preference category recorded (**21,282**) opportunities.
- Male preference jobs recorded (**21,148**) opportunities.
- Distribution is highly balanced across all preference categories.
- Internship opportunities appear broadly accessible across preference groups.

### Tableau Concepts Used

- Bar Chart
- Sorting
- Interactive Filters
- Conditional Filtering

---

## Task 2 — Company Size vs Company Analysis

### Objective

Evaluate relationships between company size and organizations satisfying complex business conditions.

### Filters Applied

- Mechanical Engineer roles only
- Experience > 5 years
- Salary > $50,000
- Full-Time or Part-Time positions
- Asian countries only
- Idealist job portal
- Additional calculated field conditions

### Visualization

![Task 2](images/task2.png)

### Insights

- Stanley Black & Decker appears as the largest company under the applied filters.
- Deutsche Post DHL Group also shows significant company size.
- Only a few companies satisfy all filtering conditions.
- Advanced filtering significantly narrows the dataset while maintaining meaningful results.

### Tableau Concepts Used

- Scatter Plot
- Calculated Fields
- String Functions
- Time-Based Visibility Logic

---

## Task 3 — Work Type Salary Distribution

### Objective

Analyze salary distribution for internship roles using statistical visualization techniques.

### Filters Applied

- Internship positions only
- Latitude < 10
- Company Size < 50,000
- Salary > $8,000
- Posting Year between 2021–2023
- Additional string and numerical conditions

### Visualization

![Task 3](images/task3.png)

### Insights

- Median salary is approximately **$58K–$59K**.
- Most internship salaries fall between **$55K and $63K**.
- Salary distribution is relatively consistent.
- No significant outliers are visible within the filtered dataset.

### Tableau Concepts Used

- Box-and-Whisker Plot
- Statistical Analysis
- Date Functions
- String Operations

---

## Task 4 — India vs Germany Job Comparison

### Objective

Compare job opportunities between India and Germany using selected qualification and experience criteria.

### Filters Applied

- Qualification = B.Tech
- Full-Time positions
- Experience > 2 years
- Salary > $10,000
- Indeed job portal
- Selected job roles

### Visualization

![Task 4](images/task4.png)

### Insights

- Germany generated valid postings after all conditions were applied.
- Aerospace Engineer and Art Teacher positions met the filtering criteria.
- Regional analysis helps identify country-specific job opportunities.
- Qualification and experience requirements substantially reduce the dataset.

### Tableau Concepts Used

- Stacked Bar Chart
- Country Comparison
- Multi-Level Filtering
- Comparative Analytics

---

## Task 5 — Top Hiring Companies

### Objective

Identify top organizations through a hierarchical company visualization.

### Filters Applied

- Data Scientist positions
- B.Tech qualification
- Female preference
- LinkedIn job portal
- Company Size ≥ 10,000
- Additional date and location conditions

### Visualization

![Task 5](images/task5.png)

### Insights

- The filtering conditions are extremely restrictive.
- Very few records satisfy all requirements simultaneously.
- Demonstrates implementation of advanced business logic through calculated fields and filters.
- Highlights the importance of balancing business rules with data availability.

### Tableau Concepts Used

- Tree Map
- Date Functions
- String Functions
- Advanced Filtering

---

## Task 6 — Qualification Drilldown Map

### Objective

Visualize job opportunities geographically across African countries using drilldown functionality.

### Filters Applied

- African countries only
- B.Tech, M.Tech, and PhD qualifications
- Full-Time positions
- Salary > $20,000
- Indeed job portal
- Geographic coordinates enabled

### Visualization

![Task 6](images/task6.png)

### Insights

- Geographic filtering enables targeted regional analysis.
- Drilldown functionality allows users to explore exact job locations.
- Multiple qualification categories can be analyzed simultaneously.
- Strict filtering criteria result in highly specific opportunities.

### Tableau Concepts Used

- Geographic Mapping
- Drilldown Actions
- Spatial Analytics
- Interactive Exploration

---

# Technical Skills Demonstrated

### Tableau Skills

- Dashboard Design
- Interactive Dashboard Development
- Data Visualization
- Storytelling with Data
- Business Intelligence Reporting

### Data Analysis Skills

- Calculated Fields
- Parameters
- Conditional Logic
- Date Functions
- String Functions
- Statistical Analysis

### Advanced Analytics

- Geographic Analysis
- Drilldown Functionality
- Comparative Analysis
- Trend Analysis
- Salary Analytics
- Company Analytics

---

# Business Value

This dashboard helps stakeholders:

- Understand hiring trends across industries.
- Evaluate salary distributions and compensation patterns.
- Compare opportunities across countries and regions.
- Analyze qualification requirements.
- Identify major hiring organizations.
- Explore geographic employment trends.
- Support data-driven decision-making.

---

# Project Outcome

Successfully extended the original training dashboard by implementing six advanced analytical tasks while maintaining a unified Tableau workbook structure.

The project demonstrates the ability to:

- Convert business requirements into analytical dashboards.
- Apply complex filtering and conditional logic.
- Design interactive and user-friendly visualizations.
- Perform geographic and statistical analysis.
- Extract actionable insights from large datasets.
- Deliver professional Business Intelligence solutions using Tableau.

---

# Repository Structure

```text
job_analytics/
│
├── data_cleaning/
│   └── data_clean.ipynb
│
├── images/
│   ├── dashboard.png
│   ├── task1.png
│   ├── task2.png
│   ├── task3.png
│   ├── task4.png
│   ├── task5.jpeg
│   └── task6.png
│
├── website/
│
└── README.md
```

---

## Author

### Sidhi Deshmukh

**Data Analytics Intern**

#### Skills Demonstrated

- Tableau
- Data Visualization
- Dashboard Development
- Business Intelligence
- Data Analysis
- Interactive Reporting

---

### Internship Submission

This project was completed as part of the **ElevanceSkills Data Analytics Internship Program** and showcases practical dashboard development, advanced Tableau analytics, and business intelligence reporting using real-world job market data.

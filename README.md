# HR-Analytics-Dashboard-PowerBI

## Overview

The HR Insights Dashboard is an interactive tool developed using Microsoft Power BI to provide comprehensive analytics on human resources data. It enables organizations to make data-driven decisions by visualizing key metrics such as employee performance, turnover rates, and demographic distributions.

## Features

- **Employee Performance Analysis:** Evaluate individual and team performance metrics to identify high achievers and areas needing improvement.
- **Turnover and Retention Metrics:** Analyze employee turnover rates and retention trends to understand workforce stability.
- **Demographic Insights:** Visualize employee demographics, including age, gender, department, and education level distributions.
- **Interactive Filters:** Utilize slicers and filters to drill down into specific data segments for detailed analysis.

## Getting Started

To explore and interact with the HR Insights Dashboard:

1. **Prerequisites:**
   - Ensure that [Power BI Desktop](https://powerbi.microsoft.com/desktop/) is installed on your machine.

2. **Clone the Repository:**
   - Clone this repository to your local machine using the command:
     ```bash
     git clone https://github.com/your-username/HR-Insights-Dashboard.git
     ```

3. **Open the Dashboard:**
   - Navigate to the cloned repository folder and open the `HR_Insights_Dashboard.pbix` file using Power BI Desktop.

4. **Explore the Data:**
   - Interact with the various visualizations, apply filters, and gain insights into the HR data.

## Data Source

The dashboard is built upon a dataset containing the following columns:

- `EmpID`: Unique Employee Identifier
- `Age`: Employee's Age
- `Attrition`: Employment Status (Active/Left)
- `Department`: Department Name
- `Education`: Education Level
- `Gender`: Employee Gender
- `JobRole`: Role/Position Title
- `MonthlyIncome`: Monthly Salary
- `PerformanceRating`: Performance Evaluation Score
- `TotalWorkingYears`: Total Years of Experience

*Note: The dataset used is fictional and intended for demonstration purposes.*

## Visualizations

The dashboard includes the following visual components:

- **Bar Charts:** Depicting employee count by department and job role.
- **Pie Charts:** Showing gender distribution and education levels.
- **Line Graphs:** Illustrating attrition trends over time.
- **Tables:** Listing key performance indicators and employee details.

## Technologies Used

- **Power BI Desktop:** For data visualization and dashboard creation.
- **DAX (Data Analysis Expressions):** To create calculated measures and columns.
- **Power Query:** For data extraction, transformation, and loading (ETL).



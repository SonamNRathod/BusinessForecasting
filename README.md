
# Employee Survey Analysis Project

## Project Overview

This project involves analyzing the employee satisfaction data from **Typical Industries** to assess key characteristics such as job satisfaction, longevity, and attitudes of the managerial, technical, and sales staff. The analysis focuses on generating descriptive statistics and visualizations using R and `ggplot2` to identify important trends and relationships in the data. The insights from this analysis are intended to support managerial decision-making by providing a clear profile of the employees.

## Data

The dataset is based on a survey of 122 employees, and it includes the following variables:
- **Age**: Employee's age (numeric).
- **Gender**: Gender of the employee (Male/Female).
- **Job Satisfaction**: Employee’s satisfaction with their job (Very Satisfied, Moderately Satisfied, A Little Dissatisfied, Very Dissatisfied).
- **Important Job Characteristic**: What the employee values most in their job (High Income, Flexible Hours, etc.).
- **Years with Employer**: Total years worked with the company.
- **Promotion Likelihood**: Likelihood of getting promoted in the next five years.
- **Decision Participation**: How often the employee is involved in decisions affecting their work.
- **Budget Participation**: Whether the employee participates in budgetary decisions.
- **Pride in Working**: How proud the employee is to work for the company.
- **Turn Down Job for More Pay**: Whether the employee would turn down another job for more pay to stay with the company.
- **Coworker Relations**: The employee’s perception of relations with their coworkers.

## Analysis Approach

1. **Descriptive Statistics**: 
   - Basic summary statistics (mean, median, etc.) for numerical columns such as **Age** and **Years with Employer**.
   - Frequency counts for categorical columns like **Job Satisfaction** and **Promotion Likelihood**.

2. **Visualizations**:
   - **Bar plots** for categorical variables like **Job Satisfaction**, **Gender**, and **Coworker Relations**.
   - **Scatter plots** to visualize relationships between numerical variables such as **Age** and **Years with Employer**.
   - **Annotated plots** to highlight key findings directly in the visualizations.

## Files

- **Typical_Employee_Survey_Data.xlsx**: The dataset containing the survey responses.
- **Employee_Survey_Analysis.Rmd**: The R Markdown file containing the code for analysis and visualizations.
- **Employee_Survey_Analysis.html**: The HTML output of the R Markdown file, displaying the analysis results and plots.

## Installation and Usage

### Prerequisites

To run the analysis in this project, you will need:
- **R** (version 4.0 or higher)
- **RStudio** (optional but recommended)
- The following R packages:
  - `readxl`: For reading Excel files.
  - `ggplot2`: For creating visualizations.

### Installing the Required Packages

If you don’t have the required R packages, you can install them using the following commands:

```r
install.packages(c("readxl", "ggplot2", "dplyr"))
```

### Running the Analysis

1. **Clone the repository** 

2. **Open the R Markdown file** in RStudio:
   - Open **Rmd file**.

3. **Run the Rmd file**:
   - Click the **Knit** button in RStudio to generate the HTML report.

4. **Explore the Results**:
   - The HTML file will contain annotated plots and descriptive statistics for the employee survey data.

### Example Plots

- **Bar Plot for Job Satisfaction**: This plot shows the distribution of employee job satisfaction levels. Most employees are satisfied.
- **Scatter Plot of Age vs. Years with Employer**: This scatter plot highlights a relationship between employee age and tenure with the company. Older employees tend to have longer tenures.
- **Scatter Plot of Years with Employer vs. Promotion Likelihood**: Shows the relationship between employee tenure and perceived likelihood of promotion.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Authors

- **Sonam Rathod** - Data Scientist / Analyst


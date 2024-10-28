# HR Analytics Dashboard using Power BI 📊

## Project Overview

The **HR Analytics Dashboard** aims to identify key factors contributing to employee attrition and provide actionable insights to improve workforce retention. This project leverages **Power BI** to create interactive visualizations, helping HR teams make informed decisions about employee engagement and retention strategies.

## Key Highlights

- **In-depth Data Analysis**: Explored and analyzed HR data to uncover insights into employee behavior, attrition trends, and department-wise performance.
- **Interactive Visualizations**: Developed dynamic dashboards in Power BI to track essential HR metrics such as attrition rate, employee demographics, and job satisfaction.
- **Data-Driven Recommendations**: Provided actionable insights to enhance employee retention and engagement based on detailed analysis.

## Process Overview

### 1. Data Collection
- **Data Source**: HR data provided in a `.csv` file.
- Imported data into **Power BI** and utilized **Power Query** for initial data processing.

### 2. Data Cleaning & Transformation
- Removed empty columns, duplicates, and errors.
- Standardized column values for consistency.
- Detected and updated data types to ensure accuracy in analysis.

### 3. Data Processing & Feature Engineering
- Created an `AttritionCount` column using conditional logic for further analysis.
- Applied **DAX** formulas to compute the **Attrition Rate**:
    ```DAX
    Attrition Rate = SUM([AttritionCount]) / SUM([EmployeeCount])
    ```
- Generated new measures and calculated fields to facilitate KPI analysis.

### 4. Data Visualization & Analysis

![HR_Analytics_Dashboard](https://github.com/user-attachments/assets/f83fab1d-35bf-4527-8aad-1a7612cde5e0)

- Developed various visualizations, including bar charts, pie charts, and tables to provide a holistic view of the data.
- Created custom KPIs to measure metrics like total employees, average age, average salary, and attrition trends.
- Visualizations include:
  - **Attrition Trends**: By department, job role, and demographics.
  - **Employee Distribution**: Gender, age, education field, and job satisfaction levels.
  - **Key Metrics Overview**: Attrition rates, active employee count, and performance indicators.

## Core Technologies & Tools
- **Power BI**: Dashboard development and data visualization.
- **SQL**: Data querying and analysis.
- **Power Query**: Data cleaning and transformation.
- **DAX (Data Analysis Expressions)**: For creating calculated measures and columns.

## Insights & Findings

- **Total Workforce**: The organization has a workforce of 1,470 employees, reflecting significant growth.
- **Attrition Trends**: Out of 1,470 employees, 237 left the organization, with a higher attrition rate among males (150) compared to females (87).
- **Departmental Insights**: The Research and Development department faced the highest attrition rate at 56.13%, indicating the need for targeted retention efforts.
- **Education Field**: Attrition is notably high among employees from the Life Sciences field, suggesting potential challenges in retaining these professionals.
- **Job Role Focus**: Sales roles had the highest turnover, highlighting the need for retention strategies within the sales team.
- **Age Group Analysis**: The 25-34 age group saw the highest attrition count, making it a critical focus area for improving retention.

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/HR_Analytics_PowerBI_SQL.git

## How to Use

1. **Load Data**: Import the `HR_Analytics_Dataset.csv` into Power BI.
2. **Explore Dashboards**:
   - Open the Power BI file (`Attrition_Analysis.pbix`) or view the `.png` snapshots for a quick overview.
   - Navigate through interactive charts and KPIs for detailed insights.
3. **Run SQL Queries**: Use the SQL scripts in the `SQL` folder for advanced data analysis and custom queries.

## Repository Structure
    ```bash
    .
    ├── Dataset
    │   ├── HR_Analytics_Dataset.csv
    │   └── Readme.txt
    ├── PowerBI
    │   ├── Attrition_Analysis.pbix
    │   ├── HR_Dashboard.png
    │   ├── Overview_Dashboard.png
    │   └── ReadMe.txt
    ├── SQL
    │   ├── HR_Analytics_SQL_Queries.sql
    │   └── README.md
    └── README.md (this file)


## Contributing

Contributions are welcome! If you have suggestions or encounter any issues, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. For more information, refer to the [LICENSE](LICENSE) file.

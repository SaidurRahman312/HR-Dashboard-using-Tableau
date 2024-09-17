# HR-Dashboard-using-Tableau
**HR Dashboard Project**  An interactive HR dashboard visualizing employee data like demographics, salaries, and performance trends. Built using synthetic data from the **Faker** library, it helps HR teams analyze workforce insights, such as gender disparity and salary trends, to support data-driven decision-making.

Tableau Public Link: [(https://public.tableau.com/app/profile/saidur.rahman1182/viz/HR-Dashboard_17249070254940/HRSummary)]

# HR Dashboard Project

## Table of Contents
1. [Project Overview](#overview)
2. [Dataset Information](#dataset)
3. [Tools and Technologies](#tools)
4. [Dashboard Features](#features)
5. [User Guide](#user-guide)
6. [Insights Derived](#insights)
7. [Findings](#findings)
8. [Future Enhancements](#enhancements)
9. [Conclusion](#conclusion)

## Project Overview <a name="overview"></a>
This project presents an interactive **HR Dashboard** built to visualize employee data trends, manage HR-related metrics, and assist decision-makers in obtaining actionable insights. The dashboard demonstrates how data visualization can be employed to make sense of large-scale employee datasets in real-time.

## Dataset Information <a name="dataset"></a>
The dataset was generated using the **Faker** library, a Python package used to generate large amounts of fake data. This includes fields such as:
- **Employee ID**
- **Name**
- **Department**
- **Hiring Date**
- **Salary**
- **Role**
- **Geographical Location**
- **Demographics** (Age, Gender, Education)

The generated dataset simulates a comprehensive employee database with over **10,000 records** to mimic a large organization's HR database.

## Tools and Technologies <a name="tools"></a>
The following tools and technologies were used to develop this dashboard:
- **Tableau**: For building interactive and dynamic dashboards.
- **Faker Library (Python)**: For generating synthetic employee data.
- **Pandas and NumPy**: For data manipulation and preprocessing.
- **Matplotlib**: For supporting visual representation (where applicable).
- **SQL Server**: For data storage and querying.

## Dashboard Features <a name="features"></a>
1. **Overview Section**:
   - Employee **Hired** vs **Terminated** metrics.
   - Department-wise employee distribution.
   - Active employees by **Location**.

2. **Demographics Section**:
   - Visual representation of gender distribution.
   - Employee age and education breakdown.
   - Performance insights linked to education levels.

3. **Income Section**:
   - Salary analysis by education level and gender.
   - Comparative salary distributions across roles and demographics.
   - Detailed breakdown by age and salary correlation with employee roles.

## User Guide <a name="user-guide"></a>
The dashboard is designed to be intuitive and interactive. Below are some key interactions available:
- **Filters**: Users can filter data by **Gender**, **Location**, **Education**, **Role**, and **Hiring Date**.
- **Click to Filter**: Most visual elements are interactive, allowing users to click on graphs to further filter data.
- **Downloadable Reports**: The dashboard provides options for exporting data in PDF format.

## Insights Derived <a name="insights"></a>
The dashboard offers several valuable insights, including:
- A clear **gender imbalance** across certain departments, highlighting the need for diversity initiatives.
- Employees with **higher education levels** tend to have a **higher performance rating**, especially in technical departments.
- **Age** and **salary trends** indicate that senior employees in leadership roles often have the highest compensation levels.

## Findings <a name="findings"></a>
1. **High Turnover Rate in Junior Roles**: Departments with entry-level roles had the highest turnover, suggesting a need for retention strategies.
2. **Gender Pay Disparity**: A significant wage gap was observed between male and female employees in certain departments, particularly in managerial positions.
3. **Underrepresentation in Leadership**: Women and minority groups were underrepresented in leadership roles, indicating room for improving diversity.
4. **Long Tenure Equals Higher Pay**: Employees who stayed longer in the company tend to be better compensated, especially in technical departments.
5. **Education Impact on Salary**: Employees with postgraduate degrees generally earned higher salaries compared to those with only undergraduate degrees.

## Future Enhancements <a name="enhancements"></a>
1. Incorporate **real-time data** from live databases to update metrics automatically.
2. Implement **predictive analytics** to identify potential employee churn based on current trends.
3. Enhance the dashboard with a **mobile-responsive version** for easier access on-the-go.

## Conclusion <a name="conclusion"></a>
This HR Dashboard serves as a comprehensive tool for managing workforce analytics. It demonstrates the potential of data visualization in human resource management, providing valuable insights for informed decision-making.

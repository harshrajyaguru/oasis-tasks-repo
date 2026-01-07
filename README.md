# Food Sales Analysis Power BI Project

## Project Overview

This project aims to provide comprehensive insights into food sales data through dynamic visualizations and detailed KPIs. By utilizing a star schema data model, the analysis explores various dimensions such as Product, Category, Region, City, and Employee. The project highlights key performance indicators (KPIs), comparisons, and trends, enabling data-driven decision-making.

## Data Modelling and Relationships

### Star Schema

To facilitate efficient data analysis and reporting, we designed a star schema. The schema consists of the following dimensions and relationships:

- **Fact Table:**
  - Orders (OrderID, ProductID, CategoryID, RegionID, CityID, EmployeeID, OrderDate, Quantity, SalesAmount)

- **Dimension Tables:**
  - Product (ProductID, ProductName, CategoryID)
  - Category (CategoryID, CategoryName)
  - Region (RegionID, RegionName)
  - City (CityID, CityName, RegionID)
  - Employee (EmployeeID, EmployeeName)

### Relationships

- **Orders to Product**: Many-to-One (ProductID)
- **Orders to Category**: Many-to-One (CategoryID)
- **Orders to Region**: Many-to-One (RegionID)
- **Orders to City**: Many-to-One (CityID)
- **Orders to Employee**: Many-to-One (EmployeeID)

## Key Performance Indicators (KPIs)

### Total Orders Year-To-Date (YTD)

- **Current Year Orders**
- **Growth/Decline % Year-over-Year (YoY)**
- **Absolute YoY Difference**

### Total Sales YTD

- **Current Year Sales Amount**
- **Growth/Decline % YoY**
- **Absolute YoY Difference**

### Total Quantity YTD

- **Current Year Quantity**
- **Growth/Decline % YoY**
- **Absolute YoY Difference**

### Comparative Analysis

- **Total Orders vs Total Sales (Yearly Comparison)**

### Breakdown Analysis

- **Employee-wise Orders**
- **Product/Category-wise Orders**
- **Most Sold Category**
- **Most Sold Product**
- **Least Sold Category**
- **Least Sold Product**

## Detailed Visualizations

### Matrix

A matrix visualization is developed with the following details:
- **Rows**: Product Category, Product
- **Columns**: Months
- **Values**: Total Sales

### Employee Orders Table

A table visualization is developed with the following details:
- **Columns**: Employee, Total Orders (Current Year), Total Orders (Previous Year), Total Order Difference (Current - Previous), Total Orders %
- **Conditional Formatting**: 
  - Red color for negative values
  - Increase/Decrease icon based on performance

## Concepts Covered

This project covers the following concepts:

- **Data Modelling**: Designing a star schema to structure data efficiently for analysis.
- **Data Relationships**: Establishing appropriate relationships between fact and dimension tables.
- **KPI Calculation**: Deriving key performance indicators to track business metrics.
- **Conditional Formatting**: Applying visual cues to highlight performance trends.
- **Comparative Analysis**: Year-over-Year comparisons to measure growth or decline.
- **Visualization**: Using Power BI to create dynamic and interactive reports.

## Usage

This Power BI project provides a robust framework for analyzing food sales data, making it an invaluable tool for business intelligence. Users can leverage the insights to identify trends, monitor performance, and make informed decisions.

## Conclusion

This Food Sales Analysis project exemplifies how Power BI can be utilized to transform raw data into meaningful insights. By focusing on essential KPIs and leveraging advanced visualization techniques, the project offers a comprehensive overview of sales performance across multiple dimensions.

---

Feel free to explore the Power BI report to uncover more insights and understand the intricate details of food sales analysis.

---

**Note:** Ensure you have the necessary data access permissions and Power BI installed to view the report.

---

For more information and updates, visit our [GitHub repository](https://github.com/PrinceRajyaguru/Data-Analysis).

---

**Contact Information:**
- **Email:** princerajyaguru1111@gmail.com
- **GitHub:** [Prince Rajyaguru](https://github.com/PrinceRajyaguru)

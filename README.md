# Data Transformation and Data Modeling

## 📌 Project Overview

This project focuses on **E-Commerce Sales Analysis** using Microsoft Power BI. The objective is to import, clean, transform, merge, and model sales-related datasets to prepare the data for analysis.

The assignment uses three CSV files and demonstrates essential data preparation techniques using Power Query Editor and Power BI's data modeling features.

## 🎯 Objectives

- Import CSV files into Power BI.
- Transform and clean data using Power Query Editor.
- Restrict the `List of Orders` table to the first 500 rows.
- Set appropriate data types for dates and monetary values.
- Convert customer names to proper case.
- Create a combined `Location` column using City and State.
- Calculate Profit Margin and categorize Profit Status.
- Merge `List of Orders` and `Order Details` using `Order ID`.
- Identify missing values and handle duplicate records appropriately.
- Sort and filter orders for analysis.
- Group and aggregate data to calculate order counts, average profit, total amounts, and monthly sales targets.
- Establish relationships between tables in the Power BI data model.

## 📂 Files in the Repository

| File | Description |
|---|---|
| `List of Orders.csv` | Contains order-related information. |
| `Order Details.csv` | Contains order details, including amount, profit, category, and sub-category where available. |
| `Sales target.csv` | Contains sales target information. |
| `Power_BI_Assignment.pdf` | Assignment instructions. |
| `Power_BI_Project.pbix` | Power BI project file. |
| `Power_BI_Assignment_Steps_Guide.docx` | Detailed instructions explaining how to complete each assignment task. |


## 🛠️ Tools and Technologies

- **Microsoft Power BI Desktop** – Data modeling and analysis.
- **Power Query Editor** – Data cleaning and transformation.
- **CSV files** – Source datasets.
- **GitHub** – Project documentation and version control.

## 🔄 Tasks Performed

### 1. Data Import
Imported the three CSV files into Power BI and opened them in Power Query Editor for transformation.

### 2. Data Transformation
- Kept the first 500 rows of `List of Orders`.
- Changed `Order Date` to the Date data type.
- Changed `Amount` and `Target` to Fixed Decimal Number.
- Converted `CustomerName` to proper case.
- Created a `Location` column in the format `City, State`.
- Created a `Profit Margin` column using Profit divided by Amount.
- Created a `Profit Status` column with the labels `Loss`, `Break-Even`, and `Profit`.

### 3. Data Merging
Merged `List of Orders` and `Order Details` using the `Order ID` column to create a combined table named `Orders Data`.

### 4. Missing Values and Duplicates
Inspected the data for missing values and duplicate records. Appropriate handling strategies were considered to maintain data quality without removing legitimate order-detail records.

### 5. Sorting and Filtering
- Sorted `Order Date` in descending order to examine recent orders.
- Filtered orders by State, including Tamil Nadu, for regional analysis.

### 6. Grouping and Aggregation
Created summary tables to:
- Count detail rows for each Order ID.
- Calculate average Profit by Category.
- Calculate total Amount by Sub-Category.
- Calculate total Sales Target by month.

### 7. Data Modeling
Established relationships using:
- `Order ID` between `List of Orders` and `Order Details`.
- `Category` between `Order Details` and `Sales target`.

Relationships were checked for appropriate cardinality and active status based on the data.

## 📊 Expected Outcomes

After completing the assignment, the project should contain:
- Cleaned and transformed datasets.
- A merged `Orders Data` table.
- Summary tables for order counts, profit, amounts, and sales targets.
- A Power BI data model with the required relationships.
- Documentation describing the assignment steps.

## ▶️ How to Use This Project

1. Download or clone this repository.
2. Open the Power BI `.pbix` file in Microsoft Power BI Desktop.
3. If prompted, update the source file paths for the CSV files.
4. Review the transformations in **Home → Transform Data**.
5. Open **Model view** to inspect the table relationships.
6. Refer to the Word step-by-step guide for the procedure followed in the assignment.

## 📚 Learning Outcomes

This assignment provides practical experience in:
- Data cleaning and preparation.
- Power Query transformations.
- Custom and conditional columns.
- Table merging and joins.
- Handling missing and duplicate data.
- Grouping and aggregation.
- Relationship creation and data modeling in Power BI.

## 📝 Conclusion

This project demonstrates the use of Microsoft Power BI to prepare e-commerce sales data for analysis. By applying data transformation, merging, aggregation, and modeling techniques, the assignment builds a foundation for reliable sales reporting and further business intelligence analysis.


# BI Report/Dashboard Project Module 2

## Table of Contents
- [Project Overview](#project-overview)
- [Original Dataset](#original-dataset)
- [Final Data Model](#final-data-model)
- [Steps Taken](#steps-taken)
- [Tools Used](#tools-used)
- [Installation](#Installation)
- [Folder Structure](#folder-structure)

## Project Overview
This project is developed as part of the final project for Module 1 of the Ironhack Data Analytics Bootcamp. Focusing on creating an interactive and insightful BI Report/Dashboard.

---

## Original Dataset
The original dataset consisted of 10 CSV files representing various business entities:

1. **Clients** - Tracks information about clients purchasing gasoline.
2. **Suppliers** - Tracks information about suppliers providing gasoline.
3. **Products** - Tracks details about the types of gasoline or related products.
4. **Contracts** - Captures agreements with clients and suppliers.
5. **Orders** - Tracks gasoline orders placed by clients.
6. **Sales** - Tracks completed sales transactions.
7. **Commissions** - Tracks sales commissions for agents or employees.
8. **Transport** - Tracks logistics and delivery of gasoline.
9. **Payments** - Tracks payments made for sales.
10. **Locations** - Tracks delivery and pickup locations for orders.

For reference, the original data model can be found in the repository under `data_model/OriginalDataModel.jpg`.

---

## Final Data Model
From the original dataset, five key tables were selected to create the final Star Schema:

- **Clients**
- **Orders**
- **Sales**
- **Commissions**
- **Products**

These tables were transformed and connected to form a Star Schema, enabling efficient analysis and reporting. The final Star Schema is available in the repository under `data_model/StarSchema.jpg`.

---

## Steps Taken
1. **Data Import**: Imported the required tables into Power BI.
2. **Data Transformation**:
   - Cleaned and transformed the data to fit the reporting needs.
   - Established relationships between tables to create the Star Schema.
3. **Modeling**:
   - Created necessary measures and calculated columns.
4. **Visualization**:
   - Designed an interactive dashboard in Power BI with three tabs:
     1. **General Overview**: Displays key sales metrics and company-wide performance.
     2. **Product Analysis**: Compares each product type against the average across metrics such as sales, revenue, quantity sold, and number of orders.
     3. **Employee Performance**: Focuses on worker performance metrics.

---

## 💻 Tools Used
- **Power BI**: For data transformation, modeling, and visualization.
- **CSV Files**: Original data source.

---

## ⚙️ Installation
1. Clone this repository to your local machine.
2. Open the `powerbi_dashboard.pbix` file in Power BI Desktop.
3. Explore the three dashboard tabs to gain insights into sales, product performance, and employee metrics.

---

## 📁 Folder Structure
```
├── data_model
│   ├── OriginalDataModel.jpg  
│   └── StarSchema.jpg 
├── data
│   ├── Clients_Table.csv
│   ├── Commissions_Table.csv   
│   ├── Contracts_Table.csv 
│   ├── Locations_Table.csv   
│   ├── Orders_Table.csv 
│   ├── Payments_Table.csv
│   ├── Products_Table.csv
│   ├── Sales_Table.csv
│   ├── Suppliers_Table.csv
│   └── Transport_Table.csv 
├── .gitignore          
├── powerbi_dashboard.pbix     
└── README.md                 
```
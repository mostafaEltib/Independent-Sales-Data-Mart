# Independent-Sales-Data-Mart
 #### 🔍 Project Overview:<br />
designing a sales data mart based on AdventureWorks data base. The project's goal is to create a data mart from the Adventure Works database, including fact tables for sales data and dimension tables for products, customers, time, and territories. This project is based on the dimensional modeling approach, and it includes data extraction, transformation, and loading (ETL) processes.<br /><br />

#### Data Model(Star schema) :<br /><br />

 ◦ Fact Sales (fact table)<br />
 ◦ Dim Product : with SCD (reorder point transaction)<br />
 ◦ Dim Customer : with SCD (phone transaction)<br />
 ◦ Dim Date : calendar (Grain Dim)<br />
 ◦ Dim Territory<br />
<br /><br />
####  🛠 Process Highlights:<br /><br />
Carefully designed dimensions and the Fact Sales table.<br />
ETL with SQL scripts for data accuracy.<br />

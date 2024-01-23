# Independent-Sales-Data-Mart
 عباره عن Data repository بنحط فيها داتا خاصة باتجاه Business محدد زي sales مثلا 
والداتا بتيجي من   External source  زي OLTP Databaseبدل Data Warehouseوهنا استخدمت SSIS Tool عشان اعمل عملية ETL علي الداتا الجاية من   AdventureWorks2022 database

Data Model(Star schema) :

 ◦ Fact Sales (fact table)
 ◦ Dim Product : with SCD (reorder point transaction)
 ◦ Dim Customer : with SCD (phone transaction)
 ◦ Dim Date : calendar (Grain Dim)
 ◦ Dim Territory

 🛠 Process Highlights:
Carefully designed dimensions and the Fact Sales table.
ETL with SQL scripts for data accuracy.

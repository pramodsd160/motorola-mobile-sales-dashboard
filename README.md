
# 🔹 Motorola Mobile Sales Dashboard 📊 - PowerBI project.

This project focuses on analyzing mobile phone sales data to track brand performance and customer trends

**This dashboard provides a complete view of mobile sales performance with insights into:**

**The dashboard highlights KPIs:**

- Total Sales
- Total Quantity
- Total transation
- Average Transaction Value

**Key visuals include:**
- _Line chart_ for Total Quantity sold by Month
- _Bar charts_ for Top models sold, 
- _Map_ for City-wise performance, and 
- _Pie charts_ for Payment Method Analysis
- _Table_ for Brand Comparisons & Top Models Sold
- _Funnel Chart_ for Customer Ratings
- _Button Slicer_ for Month
- _Slicer_ for Mobile Model, Payment Method, Brands

**DAX used for KPIs**  
> `Average = AVERAGE(Sales_Data[Price Per Unit]) -- (avg sale price)`
 
> `Total Quantity = SUM(Sales_Data[Units Sold])`  
 
> `Total Sales = SUMX(Sales_Data,Sales_Data[Units Sold]*Sales_Data[Price Per Unit])`


> `Transactions = COUNTROWS(Sales_Data)`



_Note:   
Excel File is given in Dataset folder and no data cleaning needed.   
PowerBI Dashboard File provided in dashboard folder_
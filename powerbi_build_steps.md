Power BI build steps (beginner)
1. Import and check data
Get Data → Text/CSV → sales_data.csv → Transform Data.
Set OrderDate to Date.
Set Quantity to Whole Number.
Set UnitPrice, DiscountPct, Sales, Cost, and Profit to Decimal Number.
Check for blank rows and errors, then Close & Apply.
2. Add measures
Use the formulas in DAX_measures.txt. Create one measure at a time using Modeling → New measure.
3. Page 1 — Overview
Add four Card visuals: Total Sales, Total Profit, Total Quantity, Total Orders.
Add a Line chart: Axis = OrderDate (Month); Values = Total Sales.
Add a Clustered bar chart: Axis = Region; Values = Total Sales.
Add a Donut chart: Legend = Category; Values = Total Sales.
Add slicers for Region, Category, and OrderDate.
4. Page 2 — Product Analysis
Add a bar chart: Axis = Product; Values = Total Sales.
Add a bar chart: Axis = Category; Values = Total Profit.
Sort products by Total Sales descending. Use a Top N filter (Top 10 by Total Sales) if available.
Add a table with Product, Total Sales, Total Profit, Total Quantity.
5. Page 3 — Customer & Payment
Bar chart: Customer by Total Sales; apply Top 10 filter.
Donut chart: PaymentMode by Total Sales.
Add cards for Total Customers and Average Order Value.
Add slicers that match the other pages if desired.
6. Format and validate
Format Sales and Profit as currency (₹ or your preferred currency).
Format Profit Margin % and Average Discount % as percentages.
Give the report a clear title: Sales Performance Dashboard.
Test slicers and confirm that visuals update together.
Write 3–5 findings based on what your visuals actually show. Do not invent conclusions before checking your results.
7. Save and submit
Save as DPBA_Sales_Analytics.pbix.
Take screenshots of each report page for your report.
Upload the project files and screenshots to GitHub. If your teacher needs to open the interactive dashboard, include the PBIX file too.
☕ Coffee Sales Dashboard
An interactive Excel dashboard analyzing coffee sales data across multiple years, countries, and product types.
📊 Overview
This workbook tracks end-to-end coffee sales operations — from individual customer orders to aggregated annual performance — and visualizes key metrics through a dynamic dashboard.
📁 File Structure
SheetDescriptionorder_dataRaw transaction records including order ID, date, customer, product, quantity, and sales amountcustomer_dataCustomer profiles with contact details, location, and loyalty card statusTotalSalesPivot summary of sales by year, month, and coffee typeDashboardVisual dashboard with yearly performance breakdowns (see screenshots below)
🗂️ Dataset Details
Orders include:

Order ID, Date, Customer ID, Product ID
Quantity, Unit Price, Total Sales
Coffee Type, Roast Type, Size

Customers span three countries:

🇺🇸 United States
🇮🇪 Ireland
🇬🇧 United Kingdom

Coffee Types Tracked:

Arabica
Excelsa
Liberica
Robusta

Roast Types: Light · Medium · Dark
Sizes: 0.2 kg · 0.5 kg · 1 kg · 2.5 kg

📸 Dashboard Screenshots

Screenshots of each year's sales record:

--> <img width="2560" height="1441" alt="MixCollage-25-May-2026-01-16-PM-5883" src="https://github.com/user-attachments/assets/f84e0ec2-e561-439e-a21f-6111b48fd618" />

Tools Used:

Microsoft Excel — data modeling, pivot tables, and dashboard design


🔍 Data Processing & Excel Techniques

The project uses advanced Excel functions and data modeling techniques to automate data retrieval and analysis.

Key Excel Functions Used:

✅ XLOOKUP

Used to retrieve customer information dynamically from the customer_data table into the order dataset.


✅ INDEX + MATCH

Used for dynamic product lookups such as:
Coffee Type,Roast Type,Size, Unit Price



✅ Pivot Tables & Date Grouping

PivotTables were used to:

summarize yearly/monthly sales
compare coffee types
analyze product performance trends

Order dates were grouped into years for cleaner trend visualization.

✅ Revenue Calculation

Sales revenue was calculated using: Quantity * Unit Price
This allowed : monthly sales analysis, yearly comparisons, dashboard KPI reporting

How to Use

Open Book_3.xlsx in Microsoft Excel
Navigate to the Dashboard sheet for the visual overview
Use the year/filter controls to explore individual year records
Raw data is available in order_data and customer_data for further analysis

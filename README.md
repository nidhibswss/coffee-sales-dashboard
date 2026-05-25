# Coffee Sales Dashboard

This workbook contains 1,000+ real coffee sales orders from 2019 to 2022, spanning customers across the US, Ireland, and the UK. It tracks everything from individual transactions and customer profiles to monthly revenue trends — all visualized through a dynamic Excel dashboard.

## 📁 File Structure

| Sheet | Description |
|---|---|
| `order_data` | Raw transaction records including order ID, date, customer, product, quantity, and sales amount |
| `customer_data` | Customer profiles with contact details and location|
| `TotalSales` | Pivot summary of sales by year, month, and coffee type |
| `Dashboard` | Visual dashboard with yearly performance breakdowns (see screenshots below) |

## Dataset Details

**Orders include:** Order ID, Date, Customer ID, Product ID, Quantity, Unit Price, Total Sales, Coffee Type, Roast Type, Size
**Customers span three countries:**  United States,  Ireland, United Kingdom
**Coffee Types Tracked:** Arabica, Excelsa, Liberica, Robusta
**Roast Types:** Light · Medium · Dark


## Dashboard Screenshots

Screenshots of each year's sales record:

<img width="2560" height="1441" alt="Dashboard" src="https://github.com/user-attachments/assets/f84e0ec2-e561-439e-a21f-6111b48fd618" />


 ###Key Insights
 
- 2021 showed the most consistent sales performance, with revenue recorded across all 12 months.
- Liberica generated the highest sales peaks, although purchases occurred less frequently compared to other coffee types.
- Robusta recorded the single highest monthly sales spike in April 2020, reaching approximately $195 CAD.
- Excelsa consistently underperformed relative to other coffee categories across all analyzed years.
- Sales patterns suggest a bulk-purchase or occasional ordering behavior rather than stable recurring monthly revenue.

### Tools Used

- **Microsoft Excel** — data modeling, pivot tables, and dashboard design

### Data Processing & Excel Techniques

This project uses advanced Excel formulas, PivotTables, and dashboarding techniques to automate data retrieval, transform raw datasets, and generate business insights from coffee sales transactions.

---

#### Key Excel Functions Used

#### XLOOKUP
- Used to dynamically retrieve customer information from the `customer_data` table into the `order_data` dataset.
- Applications : Customer Name lookup, Email retrieval, Country identification, Loyalty Card status mapping

---

### INDEX + MATCH
- Used for flexible two-way product lookups from the `Product_data` table.
- Retrieved Fields : Coffee Type, Roast Type, Product Size, Unit Price
- Allowed dynamic column/row matching, provided better flexibility than `VLOOKUP`

---
### Pivot Tables & Date Grouping
- PivotTables were created to summarize and analyze: yearly sales performance, yearly revenue trends,coffee type comparisons, product-level sales activity
- Date Grouping : Order dates were grouped into Years, Months to improve trend visualization and reporting clarity.

---

### Revenue Calculation
Sales revenue was calculated using: =Quantity * Unit Price
This allowed:
- Monthly sales analysis
- Yearly comparisons
- Dashboard KPI reporting

### How to Use

 1. Open `Book_3.xlsx` in Microsoft Excel
 2. Navigate to the **Dashboard** sheet for the visual overview
 3. Use the year/filter controls to explore individual year records
 4. Raw data is available in `order_data` and `customer_data` for further analysis

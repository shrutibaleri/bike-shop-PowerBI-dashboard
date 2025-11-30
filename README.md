# Bike Shop Power BI Analysis:

This is a Power BI project analysing sales, revenue, customer and product data for a fictional Bike Shop.  
Built using Power BI Desktop, Power Query, DAX, and structured for a professional GitHub portfolio.

---

## Project Overview:

This project demonstrates BI skills that are commonly used in Data Analyst and Business Analyst roles such as:

- Cleaning and transforming raw CSV files  
- Building a star-schema data model  
- Writing calculated columns and DAX measures  
- Creating interactive visuals for business insights  
- Designing a clear project repo with PBIX + data + images  

The dataset includes:

- Sales data (2020–2022)  
- Returns data  
- Customer details  
- Product, subcategory, and category metadata  
- Calendar and territory lookup tables  

All data is sourced from the Microsoft AdventureWorks Bike Shop dataset.

---

## Project Structure:
```
bike-shop-powerbi-analysis/
│
├── pbix/ <- Power BI dashboard file
│ └── BikeShop_Dashboard.pbix
│
├── data/ <- CSV files loaded into Power BI
│ └── raw/
│ ├── AdventureWorks Calendar Lookup.csv
│ ├── AdventureWorks Customer Lookup.csv
│ ├── AdventureWorks Product Categories Lookup.csv
│ ├── AdventureWorks Product Lookup.csv
│ ├── AdventureWorks Product Subcategories Lookup.csv
│ ├── AdventureWorks Returns Data.csv
│ ├── AdventureWorks Sales Data 2020.csv
│ ├── AdventureWorks Sales Data 2021.csv
│ ├── AdventureWorks Sales Data 2022.csv
│ └── AdventureWorks Territory Lookup.csv
| ├── Product Category Sales (Unpivot Demo).csv
│
├── images/ <- Dashboard screenshots
│ ├── Customer Detail.png
│ ├── Executive Dashboard.png
│ ├── Map of Customers.png
│ ├── Product Detail.png
│
└── README.md <- Project documentation
```

---

## Data Model (Star Schema):

Tables created:

- **Sales Data**  
- **Returns Data**  
- **Product Lookup**  
- **Product Subcategory Lookup**  
- **Product Category Lookup**  
- **Customer Lookup**  
- **Calendar Lookup**  
- **Territory Lookup**

Each table is linked using appropriate one-to-many relationships.

---

## Key Business Insights (KPIs):

### Total revenue:
$24.9M

### Total orders:
25.2K

### Total Profit:
$10.5M

### Return Rate:
2.2%

### Monthly Revenue:
$1.83M

### Monthly Orders:
2,146

### Monthly Returns:
166

### Top Products by Revenue:
- Fender Set (Mountain)
- Sport-100 Helmet (Red) 
- Sport-100 Helmet (Blue)

### Most Ordered Product Type:
Tires and Tubes

### Most Returned Product Type:
Shorts

### Unique Customers:
17.4K

### Revenue per Customer:
$1,431

### Top customers:
- Mr. Maurice Shan
- Mrs. Janet Munoz
- Mrs. Lisa Cai

### Countries with Most Orders:
- United States
- Australia
- Canada

---

## Power BI Techniques Used:

- Power Query transformations  
- Data type cleaning and standardisation  
- Merging and appending queries  
- Star schema modelling  
- DAX measures (SUM, COUNT, CALCULATE)  
- Time intelligence (YTD, MTD, YoY)  
- Using relationships and hierarchies  
- Creating KPIs, line charts, bar charts, maps, matrices  
- Interactive filtering using slicers and drillthrough  

---

## Future Improvements:

- Profit margin and cost analysis  
- Forecasting sales trends using more analytics tools   
- Live data refresh via Power BI Service  
- More drillthrough pages for product managers  

---

## Author:

**Shruti Baleri**  
BSc. Economics student and aspiring Data Analyst



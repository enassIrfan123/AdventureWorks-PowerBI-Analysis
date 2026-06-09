# AdventureWorks Sales Performance Dashboard

## Project Overview
An end-to-end business intelligence solution engineered in Power BI Desktop to transform raw, fragmented sales data into an interactive, executive-ready asset.

## Data Architecture
* **Schema:** Star Schema design optimized for filter propagation.
* **Tables:** 1 central Fact table (`Fact_Sales`) linked to 5 multi-level Dimension tables (`Calendar`, `Customer`, `Product`, `Product Subcategory`, `Product Category`, `Territory`).

## Key Technical Implementations
* **Power Query:** Cleansed data types, resolved missing records, and appended historical datasets.
* **DAX Formulas:** Developed specialized metrics including `Total Revenue`, `Total Orders`, and `Unique Customers` using advanced iteration functions (`SUMX`, `RELATED`, `DISTINCTCOUNT`).

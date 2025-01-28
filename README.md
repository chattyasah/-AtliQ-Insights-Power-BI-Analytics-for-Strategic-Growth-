# AtliQ Insights: Power BI Analytics for Strategic Growth
## **Project Overview**  

AtliQ Hardware has rapidly expanded its global presence, selling computers and accessories through three channels: Retailers, Direct, and Distributors. However, a recent misstep in opening a store in America, driven by intuition and limited analysis, resulted in unforeseen losses. Meanwhile, competitors leverage advanced analytics to make data-driven decisions, putting AtliQ at a disadvantage.

To stay competitive and thrive, AtliQ is building an analytics team to harness the power of data for strategic decision-making.  

This project delivers comprehensive analytics across core business functions, including:  
- **Finance**: Monitoring revenue, expenses, and profitability trends.  
- **Sales**: Evaluating regional performance, and product success.  
- **Marketing**: Measuring marketing effectiveness.  
- **Supply Chain**: Assessing forecast accuracy for inventory management.  

With these interactive dashboards, AtliQ Hardware is poised to surpass its competitors and set a new standard in leveraging analytics for strategic growth.  

## **Key Features**
- Finance, Sales, Marketing, and Supply Chain dashboards designed for actionable insights.  
- User-friendly visuals built using Power BI for clear and interactive analysis.  
- Real-world business metrics and KPIs to aid decision-making.

## **Technologies Used**  
- **Power BI**: For data visualization and dashboard creation.  
- **SQL**: For data extraction.  
- **Excel/CSV**: For initial data cleaning and preprocessing.  
- **DAX**: To create custom measures and calculations in Power BI
- **Dax Studio**: For optimising Power BI performance

## **Dataset Understanding**  

A clear understanding of the dataset is crucial for effective analysis. This project leverages both dimension and fact tables:  

### **Dataset Source**  
The dataset used in this project is provided by **[Codebasics](https://codebasics.io/)** and is designed to simulate real-world business scenarios, making it ideal for analytics and decision-making purposes.

### **Dimension Tables**  
- **dim_customer**:  
  - 27 markets (e.g., India, USA, Spain).  
  - 75 customers across two platforms:  
    - **Brick & Mortar**: Physical stores.  
    - **E-commerce**: Online platforms (e.g., Amazon, Flipkart).  
  - Sales via three channels: Retailers, Direct, and Distributors.  

- **dim_market**:  
  - 27 markets grouped into:  
    - 7 sub-zones.  
    - 4 regions: **APAC**, **EU**, **LATAM**, **NAN**.  

- **dim_product**:  
  - Product divisions:  
    - **P&A**: Peripherals, Accessories, PC (Notebook, Desktop).  
    - **N&S**: Networking, Storage.  
  - 14 product categories (e.g., Internal HDD, Keyboards).  
  - Variants available for each product.  

### **Fact Tables**  
- **fact_forecast_monthly**:  
  - Forecasted customer demand by month.  
  - Helps improve customer satisfaction and reduce warehouse costs.  
  - Denormalized table optimized for analytics.  
  - Date column replaced with the month's start date.  

- **fact_sales_monthly**:  
  - Similar to `fact_forecast_monthly` but records actual sold quantities instead of forecasts.  

### **Supplementary Tables** (`gdb056`)  
- **freight_cost**: Travel and logistics costs by market and fiscal year.  
- **gross_price**: Gross prices by product code.  
- **manufacturing_cost**: Manufacturing costs by product code and year.  
- **pre_invoice_deductions**: Pre-invoice deduction percentages by customer and year.  
- **post_invoice_deductions**: Post-invoice and other deductions details.

## **Data Model**  

Data modeling is the foundation of effective reporting, as all visuals rely on a well-structured model.  

For this project, we used the **Snowflake Schema** method, ensuring a clean, efficient, and scalable model for analysis and reporting.  

![Screenshot (3)](https://github.com/user-attachments/assets/39e0ff95-5916-4395-ae42-3efe622cd669)

## **Dashboard Showcase**
Below are the interactive Power BI dashboards designed to provide actionable insights across key business areas. Each dashboard presents a visual representation of critical metrics, enabling data-driven decision-making for AtliQ Hardware.  
### **Homescreen Dashboard

![homescreen](https://github.com/user-attachments/assets/b9c1d311-4bad-43b6-844b-47ae2492419d)

### **Finance Dashboard**  
- Tracks revenue, expenses, and profitability trends.  
- Helps identify cost-saving opportunities and financial performance.
  
![Finance view](https://github.com/user-attachments/assets/0caef7ea-2791-49a3-a7fc-3777c9769b85)

### **Sales Dashboard**  
- Analyzes regional and customer-wise sales performance.  
- Highlights top-performing products and sales trends.

![sales view](https://github.com/user-attachments/assets/c950030b-48b8-4b0a-822b-510244ac0254)

### **Marketing Dashboard**  
- Measures campaign effectiveness and ROI.  
- Provides insights into customer engagement and market reach.

![marketing view](https://github.com/user-attachments/assets/bfe3582c-a801-412d-ac3a-c950e0a2b35b)

### **Supply Chain Dashboard**  
- Monitors inventory levels, logistics, and supplier performance.  
- Helps optimize operations and minimize bottlenecks.

![supply chain view](https://github.com/user-attachments/assets/8c272908-535a-4219-9b8d-90a9f330067a)

### **Executive View**
- Summarizes the entirety of the report in one dashboard
  
![executive view](https://github.com/user-attachments/assets/27372935-5820-4a8f-8173-d9117b4891e2)






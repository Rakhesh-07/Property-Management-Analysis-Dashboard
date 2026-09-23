### **🏢 Property Management Analytics Dashboard (Power BI)**



An interactive Power BI dashboard built to analyze real-estate sales, revenue, expenses, and client performance across a multi-year property portfolio (2022–2024).

This project was designed to simulate the type of portfolio-level reporting used by real-estate brokerage and property management firms to support investment, sales, and operational decisions.



### **📌 Business Objective**



Real estate firms need fast answers to questions such as:



Which markets and property types generate the most revenue?



How much profit is made after expenses?



Which clients and brokers drive the most value?



Where are payments still pending?



How is performance changing year over year?



This dashboard converts raw property and transaction data into a single executive view that enables leadership to evaluate financial performance, sales efficiency, and geographic exposure in seconds.





### **📂 Data Model**



The dashboard was built using four structured tables:



Table	Description

Sales Table	Property sales transactions, dates, prices, and sales channels

Property Table	Property type, size, location, and listing attributes

Client Table	Buyer information, client ID, and occupation

Expense Table	Operating and transaction-related costs



All preprocessing, cleaning, and transformations were performed using Power BI Power Query (Transform Data).





### **🛠 Data Preparation (Power Query)**



**Key transformation steps included:**



* Removing invalid or incomplete transactions



* Standardizing country and city names



* Creating clean date, year, and month fields for time-series analysis



* Categorizing properties (Apartment, Condo, Single-Family, Townhouse)



* Preparing payment status flags (Paid vs Pending)



* Validating price and expense fields for accurate profit calculation



This ensured the analytical layer was reliable and ready for DAX calculations.





### **📊 Key KPIs (DAX)**



**Custom measures were created to track:**



* Total Revenue



* Total Expenses



* Net Income (Revenue – Expense)



* Properties Sold



* Revenue by Property Type



* Revenue by Sales Channel



* Revenue by Country



* Client-level Revenue Contribution



These measures allow the dashboard to update dynamically when users filter by year, country, client, or property type.





### **📈 Dashboard Features**



**The report includes:**



1. Executive KPIs
   
2. Revenue, Expense, Income, and Properties Sold
   
3. Year-over-Year performance (2022–2024)
   
4. Sales \& Revenue Analysis
   
5. Monthly revenue trends
   
6. Sales by Broker, Online, and Direct channels
   
7. Revenue by Apartment, Condo, Single-Family, and Townhouse
   
8. Geographic Insights
   
9. Revenue by country displayed on an interactive world map
   
10. Ranked list of top-performing markets
    
11. Client Intelligence
    
12. Top clients by total revenue
    
13. Client occupation breakdown
    
14. Transaction counts per client
    
15. Operations View
    
16. Sold properties with payment status (Paid vs Pending)
    
17. Helps simulate collections and deal-closing workflows
    
18. Property Spotlight
    
19. Most expensive property with image and property attributes (beds, baths, size, price)





### **📅 Multi-Year Analysis**



**Users can switch between:**



* 2022



* 2023



* 2024



**This allows leadership to track:**



* Portfolio growth and contraction



* Shifts in country performance



* Changes in client concentration



* Sales channel trends over time





### **🎯 Why This Project Matters**



**This dashboard mirrors how real-estate firms monitor:**



* Portfolio profitability



* Market exposure



* Sales efficiency



* Client concentration risk



* Cash-flow health



* It demonstrates the ability to convert raw transaction data into decision-ready intelligence for property managers, brokers, and executives.





### **📊 Business Insights Summary**

* 2023 delivered the strongest overall performance, driven by higher
  broker‑led and condo sales.



* Revenue is concentrated in a limited set of countries, highlighting
  both growth opportunities and geographic risk.



* Pending payments represent meaningful cash‑flow exposure, making
  collections tracking operationally critical.



* Property‑type mix shifts year‑over‑year, supporting data‑driven
  pricing and inventory strategy.



* A small group of high‑value clients contributes a disproportionate
  share of revenue, enabling targeted relationship management.



### **🧰 Tools Used**



* Power BI



* Power Query (ETL \& Data Cleaning)



* DAX (Measures \& KPIs)



* Data Modeling \& Relationships



* Interactive Visual Design



### **👤 Author**



**Rakhesh Varshan Dhamodaran**

**Data \& Analytics Portfolio Project**


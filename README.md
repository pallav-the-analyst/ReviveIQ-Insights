
# 📊 ReviveIQ Insights – Power BI Project  

🔗 **Live Dashboard:** [Click here](https://app.powerbi.com/view?r=eyJrIjoiOGRiMDhlMmMtMDA4My00MWU3LWJlY2MtZTg4MWM0NDI1OWM5IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

---

## 🌟 Project Overview  
Marriott Bonvoy, a leading brand in the hospitality industry, operates in a highly competitive environment where maintaining occupancy, revenue growth, and guest satisfaction is critical.  
To support data-driven decision-making, this project leverages **Power BI** to build an interactive dashboard that provides deep visibility into booking behavior, hotel performance, and revenue trends.
**ReviveIQ Insights** transforms raw hospitality data into meaningful business intelligence, enabling stakeholders to identify opportunities, reduce cancellations, and improve overall performance.

This project, part of the **Codebasics Bootcamp**, focuses on building an **interactive dashboard** that answers key stakeholder questions across:  
- Booking & Cancellation  
- Hotel Performance  
- Executive Decision Support     

---

## 💻 Tech Stack  
- SQL  
- Power BI Desktop  
- Excel  
- DAX  
- Power Query  

---

## 🛠️ Power BI Features  
- Data cleaning and transformation using **Power Query**  
- Interactive **data modeling** with optimized relationships  
- Creation of **KPIs and measures** using DAX  
- **Dynamic titles** based on filters  
- **Conditional formatting** for quick insights  
- **Bookmarks & navigation buttons** for smooth user experience  
- **Drill-through** functionality for detailed analysis  
- Custom **tooltips** for deeper context  
- **Data validation** to ensure reporting accuracy  

---

## 🏢 Company Background  
Marriott Bonvoy drives bookings through three primary channels:
- 🏨 Direct (Website & Mobile App)  
- 🌐 Online Travel Agencies (OTAs)  
- 🧳 Corporate & Travel Partners    

Recently, the company experienced pressure on occupancy and revenue amid rising competition and siloed reporting practices. This exposed the need for a robust analytics platform to minimize guesswork and support faster, data-driven business decisions. 

## 📂 Dataset Details  

The project uses two databases provided in the Bootcamp: **gdb041** and **gdb056**.  
Together, they cover customers, products, markets, sales, forecasts, and associated costs.  

---

### 🗄️ gdb041  

- **dim_customer**  
  - 27 markets (e.g., India, USA, Spain)  
  - 75 unique customers  
  - Platforms: *Brick & Mortar* (offline), *E-commerce* (Amazon, Flipkart, etc.)  
  - Channels: Retailer, Direct, Distributor  

- **dim_market**  
  - Market details grouped into **7 sub-zones** and **4 regions** (APAC, EU, NAN, LATAM)  

- **dim_product**  
  - Divisions: P&A (Peripherals & Accessories), PC (Notebooks & Desktops), N&S (Networking & Storage)  
  - 14 product categories (e.g., Internal HDD, Keyboard) with multiple variants  

- **fact_forecast_monthly**  
  - Monthly demand forecasts by customer  
  - Used to compare forecast vs. actual sales for inventory planning  

- **fact_sales_monthly**  
  - Monthly actual sales quantities  
  - Helps track performance against forecast  

---

### 🗄️ gdb056  

- **freight_cost** – Logistics and freight expenses by market & fiscal year  
- **gross_price** – Gross product prices by product code  
- **manufacturing_cost** – Yearly manufacturing costs per product  
- **pre_invoice_deductions** – Trade discounts applied before invoicing (customer & year level)  
- **post_invoice_deductions** – Discounts and claims applied after invoicing  


## 💡 Dashboard Overview  

The dashboard provides a 360° view of AtliQ Hardware’s business operations across multiple domains:  

- ✅ **Home View** – Navigate seamlessly with a central landing page  
- ✅ **Finance View** – Analyze P&L statements, Net Sales trends, and top/bottom customers & products  
- ✅ **Sales View** – Explore customer and product performance with Net Sales, Gross Margin %, unit economics, and deductions  
- ✅ **Marketing View** – Gain insights by market, region, product, and customer, tracking GM% and NP% across segments  
- ✅ **Supply Chain View** – Track Forecast Accuracy, Net Error, and Absolute Error with trend analysis for optimization  
- ✅ **Executive View** – Monitor performance at a glance with revenue by division, customer, product, and channel  



## 🏠 Home Page
Central navigation hub with buttons to access each domain view.  

![Home Page](https://github.com/pallav-the-analyst/BI_360/blob/main/images/bi360_page-0001.jpg)

---

## 📅 Booking Insights
Analyze booking sources, cancellation trends, and guest patterns to optimize occupancy and marketing focus.  

![Finance View](https://github.com/pallav-the-analyst/BI_360/blob/main/images/bi360_page-0002.jpg)

---

## 📈 Performance Overview 
Customer and product performance with insights into Net Sales, Gross Margin %, and unit economics.  

![Sales View](https://github.com/pallav-the-analyst/BI_360/blob/main/images/bi360_page-0003.jpg)

---

## 👔 Executive View 
High-level business snapshot enabling leadership to monitor performance and make faster strategic decisions.  

![Marketing View](https://github.com/pallav-the-analyst/BI_360/blob/main/images/bi360_page-0004.jpg)



## 🚀 Project Outcome  

This project demonstrates how **1.5M+ rows of raw data** were transformed into an **interactive, decision-focused dashboard**.  

It enables:  
- **Revenue Teams** → Improve booking efficiency and reduce cancellations  
- **Operations Teams** → Optimize room allocation and hotel performance
- **Marketing Teams** → Identify high-performing booking channels  
- **Executives** → Make faster, data-backed strategic decisions    

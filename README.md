#  The Pizza Hub: Sales & Trends Tracker

This project is a comprehensive **Sales & Trends Dashboard** designed to analyze customer behavior, operational efficiency, and financial health for a pizza business.

### Data Source Information
* **Dataset**: Pizza Place Sales url: https://mavenanalytics.io/data-playground/pizza-place-sales
* **Volume**: Processed transactional data consisting of **499 records** and **25 fields**.
* **Scope**: A year's worth of sales data including date, time, pizza types, sizes, quantities, and prices.

##  Live Interactive Dashboard
I've published the interactive version of this report to the Power BI Cloud. You can explore the data and filters here:

👉 [**View Live Project on Power BI Service**](https://app.powerbi.com/view?r=eyJrIjoiOGE3ZDliNjQtMjZjZC00MzkwLTg4MWYtYjhhYmQxZTk5OThmIiwidCI6Ijg2Yzk5YjhjLTc1MzMtNDVlMC1hYmUxLWFmZDE2NTBiYzdjOCIsImMiOjEwfQ%3D%3D)

---

###  Project Overview
This dashboard was developed to answer critical business questions:
* **Customer Traffic:** How many customers visit daily, and when are the peak hours?
* **Order Patterns:** How many pizzas are typically purchased, and what are the bestsellers?
* **Financial Health:** What is the total revenue for the year, and is there any seasonality in sales?
* **Strategic Optimization:** Which pizzas should be removed from the menu or given a promotion?

---

###  Key Business Insights
* **Peak Performance:** Identified peak sales hours, which is vital for effective staff scheduling.
* **Product Mix:** Quickly visualize which category occupies the largest share of total revenue.
* **Inventory Focus:** Using the **"Least Selling" bookmark**, items that need promotion or replacement are easily identified.

**Recommended Analysis (Answering Key Questions):**  
1. **Daily Customers & Peak Hours:**  
   - Aggregated sales by date to determine daily customer counts.  
   - Identified peak hours during **lunch (11AM–1PM)** and **dinner (6PM–8PM)** periods.  

2. **Pizzas per Order & Bestsellers:**  
   - Calculated average pizzas per transaction to understand ordering behavior.  
   - Top-selling pizzas identified using total quantity sold, e.g., *Pepperoni*, *Margherita*, and *Hawaiian*.  

3. **Revenue & Seasonality:**  
   - Total revenue computed for the year using `Quantity * Price`.  
   - Observed seasonal trends with higher sales during **weekends** and **holiday months**.  

4. **Menu Optimization & Promotions:**  
   - Identified underperforming pizzas for potential removal or promotion using the **Least Selling Pizza** view.  
   - Items with consistent low sales highlighted opportunities for targeted promotions.

---

###  Technical Process (The Workflow)

#### 1. Data Preparation & ETL
* **Data Profiling:** Utilized *Column Profile* and *Column Distribution* in Power Query to ensure data integrity and eliminate anomalies.
* **Time Intelligence:** Developed a custom **Date Table** to ensure accurate computation for *Hourly Trends* and seasonal analysis.

#### 2. Data Analysis Expressions (DAX)
* **Financials:** `Total Sales`, `Monthly Revenue`.
* **Operational:** `Average Pizza per Day`, `Peak Sales Every Hour`.
* **Product Performance:** `Top and Least Selling Pizzas`, `Size Popularity`.

#### 3. Effective Visualization & UI/UX
* **Interactivity:** Implemented **Slicers** for *Size* and *Category* filtering.
* **Navigation:** Leveraged **Bookmarks and Buttons** for seamless switching between *Best* and *Least Selling Pizzas* views.

---

###  Design & Branding
* **Color Palette:** Used warm tones (Yellow, Orange, Deep Orange) to align with the "Pizza" theme.
* **Finesse:** Adjusted shaded area transparency to **60%** for a cleaner and more readable data presentation.

---

### 📸 Dashboard Screenshot

<img width="900" alt="Pizza Sales Dashboard" src="https://github.com/user-attachments/assets/ce687226-5b66-469f-8838-6339b1fce610" />

---

###  Contact Me
* **LinkedIn:** [Jemico Dalangin](https://www.linkedin.com/in/jemico-dalangin-955b60288)
* **Email:** jemico.dalangin@gmail.com
* **GitHub Portfolio:** [JCoquillaD](https://github.com/JCoquillaD)

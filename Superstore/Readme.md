# 📊 Superstore.USA Sales Performance Dashboard

A comprehensive and interactive **business intelligence dashboard** created in **Tableau** to analyze **Sales**, **Profit**, and **Order** data for *Superstore.USA*.  
This dashboard provides **dynamic visualizations** and **key performance indicators (KPIs)** to help users explore performance across **Category**, **Region**, and **Time**.

---

## 🎯 Features

This dashboard is designed to be highly interactive and insightful. Key features include:

### ⚡ Dynamic Metrics
A parameter allows users to switch between three key metrics: **Sales**, **Profit**, and **No. of Orders**.  
All charts and KPIs dynamically update to reflect the selected metric.

### 🧭 Dual-Plane Layout
A clean, organized layout with **interaction controls on the left** and **dynamic visualizations on the right**.

### 🎛️ Interactive Filters
Users can filter data by **Region** and **Year**.  
A **toggle button** allows hiding or displaying these filters for a cleaner view.

### 🏆 Consistent Top 5 Products
A dedicated chart always displays the **Top 5 products** based on the selected metric, regardless of other filter selections.

### 🔄 Filter Actions
Clicking on a category in the **Sales by Category** chart filters all other charts and KPIs for detailed drill-down analysis.

### 💡 Key Performance Indicators (KPIs)
Three KPI cards display:
- 💰 **Sales:** Total sales for the selected period.  
- 📈 **Profit Margin:** Total profit as a percentage of total sales.  
- 🔁 **Return Rate:** Total quantity returned as a percentage of total quantity ordered.

### 📊 Trend Analysis
A **time-series chart** with a trend line shows performance over time to identify patterns and seasonality.

### 🔗 Logo Redirection
Clicking the **Superstore logo** redirects users to the live dashboard on **Tableau Public**.

---

## ⚙️ Technical Details

This project was developed using **Tableau Desktop**.  
Core functionalities are implemented through **calculated fields**, **parameters**, and **dashboard actions**.

### 🧩 Parameters
- **Metric Parameter:** A string parameter with values: *Sales*, *Profit*, and *No. of Orders*.

### 🧮 Calculated Fields
- **Profit Margin:**  
  `SUM([Profit]) / SUM([Sales])`

- **Return Rate:**  
  `SUM(IF [Order ID] = [Returned Order ID] THEN [Quantity] END) / SUM([Quantity])`

- **Dynamic Values:**  
  A CASE statement using the Metric Parameter to select the appropriate measure for each chart.

### 🧭 Dashboard Actions
- **Filter Action:**  
  - Source: *Sales by Category* chart  
  - Targets: *All other charts and KPI cards*

- **URL Action:**  
  - Source: *Superstore logo image*  
  - Target: *Live Tableau Public dashboard URL*


## 🧠 About This Project

This Tableau dashboard was built to demonstrate:
- Dynamic parameter-driven analysis  
- Interactive filtering and drill-downs  
- KPI visualization with trend insights  
- Dashboard design best practices  

---

## 🛠️ Tools Used
- **Tableau Desktop / Tableau Public**
- **Calculated Fields**
- **Parameters & Filter Actions**
- **Dynamic Titles**
- **Trend Lines & Average Lines**

---

### 👩‍💻 Connect with Me
- **LinkedIn**- www.linkedin.com/in/sai-subhashree-14681520b 
- **EmailID** -saidalal02@gmail.com

<img width="1886" height="734" alt="image" src="https://github.com/user-attachments/assets/13808ab4-3139-4b29-bef7-d3d0a213a57f" />


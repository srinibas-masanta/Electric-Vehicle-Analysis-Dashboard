# 🚗⚡ Electric Vehicle Analysis Dashboard  

## 📌 Project Overview  
This project focuses on analyzing electric vehicle (EV) adoption trends using a **Tableau dashboard**. The dataset contains records of EVs registered in the United States, and the analysis aims to uncover insights into market growth, vehicle types, manufacturer dominance, and regional distribution.  

The **interactive dashboard** presents key performance indicators (KPIs), charts, and filters to provide a **comprehensive overview of EV trends**.  

## 🎯 Objectives  
- **Analyze the adoption trends** of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs).  
- **Determine the average electric range** of EVs to assess technological advancements.  
- **Identify top EV manufacturers** and models based on adoption.  
- **Explore the geographical distribution** of EVs across states.  
- **Assess the impact of Clean Alternative Fuel Vehicle (CAFV) incentives** on EV adoption.  

## 📊 Dashboard Overview  
### **Key Performance Indicators (KPIs)**  
✔ **Total Vehicles:** 150,413  
✔ **Average Electric Range:** 67.83 miles  
✔ **Total BEV Vehicles:** 116,745 (**77.6% of total**)  
✔ **Total PHEV Vehicles:** 33,668 (**22.4% of total**)  

### **Visualizations & Insights**  
📈 **Total Vehicles by Model Year (2011+)** - Displays EV growth trends over time.  
🗺 **Total Vehicles by State** - Shows geographic distribution of EV adoption.  
🏭 **Top 10 EV Manufacturers** - Highlights the most dominant brands.  
🛠 **Total Vehicles by CAFV Eligibility** - Assesses policy influence on EV adoption.  
🚘 **Top EV Models** - Lists the most popular EV models with adoption percentages.  

### **Filters Used in the Dashboard**  
- **EV Type:** Filter between BEV and PHEV.  
- **State:** Select specific regions to analyze adoption patterns.  
- **Model:** View specific EV models.  
- **CAFV Eligibility:** Assess vehicles qualifying for incentives.  

## 🔄 Data Processing & Pre-Analysis Steps  
- **Filtered out unnecessary columns:** Excluded non-essential data like VIN, county, and MSRP.  
- **Applied a filter for Model Year (2011+):** Focused on recent EV adoption trends.  
- **Removed Alaska & Hawaii:** Due to their insignificant vehicle count.  
- **Created calculated fields in Tableau:**  
  - **Total Vehicles:** `COUNTD([DOL Vehicle ID])`  
  - **Average Electric Range:** `AVG([Electric Range])`  
  - **Total BEV Vehicles:** Filtered count of BEVs.  
  - **Total PHEV Vehicles:** Filtered count of PHEVs.  

## 🛠 Tools & Technologies Used  
- **Tableau** - Data visualization & dashboard creation.  
- **Excel/CSV Processing** - Data cleaning and pre-processing.  

## 📌 How to Use  
1. Download the **Tableau workbook (`.twbx` file)** from the repository.  
2. Open the workbook in **Tableau Desktop** (or Tableau Public).  
3. Interact with the dashboard using **filters** to explore different insights.  

## 📸 Dashboard Preview  
![image alt](https://github.com/srinibas-masanta/Electric-Vehicle-Analysis-Dashboard/blob/25694183579e553e7f8f4d856c45f2b9b3cff76f/Dashboard%201.png)  

## 📥 Dataset  
The dataset used in this project is sourced from **official EV registration records**. You can access it on **Kaggle** using the link below:  

📌 **[Electric Vehicle Population Data](https://www.kaggle.com/datasets/ratikkakkar/electric-vehicle-population-data)**  

## 🚀 Future Enhancements  
🔹 **Real-time data integration** for live EV adoption updates.  
🔹 **Predictive modeling** to forecast future EV adoption trends.  
🔹 **Comparison with gas-powered vehicles** to assess market shifts.  

## ✨ Conclusion  
This project provides **valuable insights into the adoption trends of electric vehicles** across the U.S. The dashboard helps stakeholders, policymakers, and enthusiasts understand EV market growth, regional preferences, and the impact of incentives.

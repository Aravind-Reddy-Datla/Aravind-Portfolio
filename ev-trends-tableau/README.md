# 🚗 Electric Vehicle Trends Dashboard (Tableau)

## 🎯 Objective
This project aims to analyze electric vehicle (EV) adoption and performance trends using a predominantly U.S.-based dataset. The goal is to provide stakeholders with actionable insights by visualizing key factors such as model year, make, EV type, and Clean Alternative Fuel Vehicle (CAFV) eligibility, thereby supporting data-driven decisions on customer behavior and long-term vehicle value.

## 📊 Tools & Techniques
- **Tableau Desktop/Tableau Public**: For creating interactive, dynamic dashboards.
- **MS Office/Excel: For initial data preparation and quality checks.
- **Calculated Fields**: To derive KPIs like Total Vehicles, Average Electric Range, Total BEV (Battery Electric Vehicles), and Total PHEV (Plug-in Hybrid Electric Vehicles) counts with percentages.
- **Parameters**: Enabling dynamic selections (e.g., "Top N" vehicle manufacturers and dynamic chart titles).
- **Filters & Context Filters**: To restrict data (e.g., model year from 2011 onwards) and maintain proper filter hierarchy.
- **Action Filters**: Allowing users to drill through aggregated data to view detailed, row-level information.
- **Dual Axis Charts**: Combining multiple visualization types (such as line and area charts) to display trends concurrently.

## 💡 Dashboard Highlights

### High-Level Dashboard
- **KPI Cards**: Present summary metrics including:
  - *Total Vehicles*: Overall count.
  - *Average Electric Range*: Mean range per charge (in miles).
  - *Total BEV Vehicles & Percentage*: Count and share of Battery Electric Vehicles.
  - *Total PHEV Vehicles & Percentage*: Count and share of Plug-in Hybrid Vehicles.
  
- **Time-Series Trends**:
  - An area and line chart visualizes the exponential growth in EV adoption from 2011 onwards.
  
- **Geographical Distribution**:
  - A shape map (choropleth) displays total EVs by state using color saturation to indicate vehicle density.
  
- **Manufacturer Performance**:
  - A bar chart shows the top-performing vehicle makes, with a dynamic parameter to select the 'Top N' makers.
  
- **Fuel Type Eligibility**:
  - A donut chart visualizes vehicles categorized by CAFV eligibility (eligible, not eligible, unknown).

### Detailed Drill-Through Tab
- **Model-Level Analysis**:
  - A grid view provides comprehensive details on total vehicles by model, make, and EV type.
  
- **Interactive Filters**:
  - Dynamic filter panels allow filtering by CAFV eligibility, EV type, model, and state.
  - Visuals interact as action filters for seamless data exploration.

## 🔍 Key Insights
- **Exponential Growth**: EV adoption has been rising exponentially, with 2023 noted as a peak year, while 2024 data is pending.
- **Dominant Manufacturer**: Tesla leads the market, contributing between 52-57% of EVs in the dataset—all categorized as BEV.
- **Vehicle Mix**: Approximately 78% of the vehicles are BEV, with the remaining 22% being PHEV.
- **CAFV Eligibility**: About 46% of vehicles have unknown eligibility, 41% are eligible, and 12% are not—highlighting areas for further investigation.
- **Manufacturer-Specific Trends**: 
  - BMW shows a higher ratio of hybrid vehicles (72%) relative to fully electric ones (28%).
  - Chevrolet offers a mix of both BEV and PHEV models.
- **Top Tesla Models**: Model Y (41%) and Model 3 (40%) dominate Tesla’s EV offerings.
- **Geographical Concentration**: The dataset is heavily skewed towards Washington state, which accounts for approximately 99% of the vehicles.

## 📎 Note
This project utilizes a raw CSV file from Kaggle, containing roughly 150,000 rows and 17 fields. To ensure data relevance, a source filter was applied to include only model years from 2011 onward. The analysis is based on a sample dataset that is predominantly from Washington state.

# Mangalore-Agricultural-Data
🌾 Mangalore Agricultural Dashboard (2004–2019)
📘 Overview
This project analyzes agricultural data from Mangalore, Karnataka, spanning 2004–2019, to explore how environmental, geographical, and seasonal factors affect crop yields and revenue generation.
The analysis aims to derive insights into how soil types, humidity, and seasons influence productivity while identifying top-performing crops by revenue.
📊 Dataset Features
Feature Description
Year: Year of production (2004–2019)
Location: Mangalore, Karnataka
Rainfall (mm): Average rainfall during crop cycle
Temperature (°C)	: Average temperature recorded
Relative Humidity (%): Average humidity percentage
Soil Type: Type of soil (e.g., sandy, clay, laterite)
Irrigation Method: Type of irrigation (e.g., canal, drip, rain-fed)
Crop Type: Type of crop grown
Season: Kharif, Rabi, or Zaid
Yield (tonnes/ha): Crop output per hectare
Market Price (₹): Market value per tonne
🎯 Objectives of the Analysis
	Assess the impact of environmental factors (humidity etc) on crop yield.
	Identify which soil type produced the highest yield.
	Examine the relationship between relative humidity and yield across seasons.
	Determine the top 5 crops by total revenue.
	Evaluate yield trends across years and seasons.
 
⚙️ Data Cleaning and Preparation Steps
Data Importation
The dataset was imported into Excel and cleaned using Power Query.
Data Cleaning
Removed empty and duplicate records.
Checked for data consistency in numerical and categorical fields.
Detected anomalies in temperature values, which showed irregular or unrealistic readings.
→ These values were excluded from further analysis due to suspected data input errors.
 
Statistical Review Sheet
A statistical sheet was developed to determine appropriate aggregation methods (Sum, Mean, or Average).
Numerical figures (except Relative Humidity) were found to be unevenly distributed, justifying the use of SUM for most aggregate KPIs.
Feature Aggregation
Computed total yields, revenues, and seasonal humidity levels using Pivot Tables.
Created separate pivot tables for:
Yields across seasons
Soil type and yield comparison
Humidity per season
Top 5 crops by revenue
 
Dashboard Development
Designed an interactive Excel dashboard using pivot charts, slicers, and KPIs to visualize insights.
📈 Dashboard Summary (Key Insights)
🌾 Total Overview
Total Yield: 7,029,169 tonnes
Total Revenue: ₹14,436,109
Total Area Covered: 3,625,920 hectares
🧑‍🌾 Yields Across Seasons
Season	Total Yield (tonnes)	Observation
Kharif : 1,970,707	Moderate yield during monsoon
Rabi:2,221,903	Strong yield after monsoon
Zaid: 2,835,559	Highest yield among all seasons
💡 Zaid season recorded the highest overall yield.
🌦️ Total Humidity Across Seasons
Season: Humidity Level
Rabi:8,959
Zaid:5,226
Kharif : 4,815
💧 Rabi season experienced the highest relative humidity, which correlated with higher yields.
 
🧱 Top 3 Soils by Yield
Soil Type Yield 
Clay:1,561,901 t/ha
Laterite:1,251,428 t/ha
Sandy	:1,049,839 t/ha
🪴 Clay soil was the most productive soil type overall.
💰 Top 5 Crops by Revenue
Crop	Revenue (₹)
Coconut : 14,436,109
Coffee : 3,417,833
Cashew : 2,804,230
Cardamom: 1,804,554
Groundnut: 1,417,974
🌴 Coconut generated the highest revenue, far exceeding other crops.
🧭 Tools and Techniques Used
Power Query (Excel): Data cleaning and transformation
Statistical Analysis: Aggregation method selection (SUM used for even distributions)
Pivot Tables & Charts: Data summarization and visualization
Slicers: Interactive filtering by year, soil, and season
🪴 Conclusion
	Temperature data was excluded due to inconsistencies.
	Sum aggregation was best suited since most numeric data was not evenly distributed.
	Zaid season gave the highest yield, while Rabi season recorded the highest humidity.
	Clay soil outperformed others in yield.
	Coconut was the top-performing crop in terms of revenue generation.


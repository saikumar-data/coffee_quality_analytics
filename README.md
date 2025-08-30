# coffee_quality_analytics
An end-to-end analysis of Arabica coffee quality data from the Coffee Quality Institute (CQI).
 Coffee Quality Analysis (Power BI Capstone Project)

📖 Overview
This project explores **Arabica coffee quality data** from the Coffee Quality Institute (CQI).  
The dataset includes information on **coffee origins, processing methods, varieties, sensory scores, and defects**.  
The primary objective is to analyze **factors influencing coffee quality**, detect **patterns in defects**, and visualize **regional and temporal trends** using **Power BI**.

 🎯 Objectives
1. Identify key sensory attributes (Aroma, Flavor, Aftertaste, Acidity, Body, Balance, etc.) that determine coffee quality.
2. Explore the relationship between **processing methods, origin regions, and total cup points**.
3. Analyze **defect categories (Category One & Two)** and their impact on coffee quality.
4. Visualize **temporal trends** in harvest year, grading date, and expiration.
5. Provide **actionable insights** for coffee producers, graders, and researchers.

 📂 Dataset Description
- **Source**: Coffee Quality Institute (CQI) Arabica dataset  
- **Rows**: 207 | **Columns**: 31  

 🔑 Key Columns
- **Geographic Info**: `Country of Origin`, `Region`, `Altitude`, `Harvest Year`, `In-Country Partner`
- **Variety & Processing**: `Variety`, `Processing Method`
- **Logistics**: `Number of Bags`, `Bag Weight`
- **Sensory Attributes**: `Aroma`, `Flavor`, `Aftertaste`, `Acidity`, `Body`, `Balance`, `Uniformity`, `Clean Cup`, `Sweetness`, `Overall`
- **Final Score**: `Total Cup Points` (sum of sensory attributes)
- **Defects**: `Category One Defects`, `Category Two Defects`, `Quakers`
- **Other**: `Moisture Percentage`, `Color`, `Grading Date`, `Expiration`

> Specialty coffees typically score **≥80 points**. Most samples in this dataset fall between 80–89.

## 📊 Power BI Report Pages
1. **Regional & Variety Exploration**  
   - Distribution of varieties and bag counts by country.  
   - Contribution of in-country partners.  
   - Harvest year trends.

2. **Quality & Defects Overview**  
   - KPIs: Avg Cup Points, Avg Moisture, Max Score.  
   - Cup points by processing method.  
   - Defects vs harvest years.  
   - Bags vs Total Points by origin.

3. **Defect & Drill-Down Beans**  
   - Defect counts by processing method.  
   - Color distribution of beans by defect category.  
   - Drill-down table with variety, grading, expiration, and defect status.

4. **Time and Trends**  
   - Defect counts over expiration timeline.  
   - Category One & Two defects over grading dates.

---

⚙️ Tools & Technologies
- **Power BI Desktop** → Data cleaning, transformation, and visualization  
- **Power Query (M)** → Handling missing data, transformations  
- **DAX (Data Analysis Expressions)** → Creating measures and What-If analysis    


🚀 Key Insights
- **Top sensory drivers  of Total Cup Points: Flavor, Aftertaste, Balance, Acidity.  
- **Washed/Wet processing** yields consistently high-quality scores.  
- **Defects reduce total cup points**, though the effect is smaller in this dataset.  
- **Taiwan, Guatemala, and Colombia** are top contributors in sample volume.  
- Seasonal/temporal patterns exist in defect occurrences.

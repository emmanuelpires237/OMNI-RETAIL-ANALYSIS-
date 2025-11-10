# OMNI RETAIL ANALYSIS
**1.Project Overview**

The Customer Satisfaction and Loyalty Analytics Dashboard was designed to uncover insights into what drives customer satisfaction, loyalty, and repeat purchasing behavior.
In a competitive market, understanding the why behind customer attitudes is crucial. This dashboard serves as a data-driven decision-support tool, helping businesses identify:
•	Which factors contribute most to customer happiness
•	How loyalty levels vary across demographics and regions
•	Whether contact with support teams impacts satisfaction
•	The behavioral differences between one-time and repeat buyers
By visualizing and analyzing these patterns, this project bridges the gap between raw feedback data and strategic customer experience management.
________________________________________
**2.Project Scope**

**The project aimed to:**
* Analyze and visualize customer satisfaction and loyalty patterns
* Measure the impact of key factors such as support interaction, purchase history, and demographics
* Identify regional and segment-based differences
* Build an interactive Power BI dashboard to enable data exploration by stakeholders
Core questions addressed:
1.	What factors contribute to high or low satisfaction scores?
2.	Are certain customer segments more loyal than others?
3.	How does customer support interaction affect satisfaction?
4.	Do repeat buyers show higher satisfaction than one-time buyers?
5.	Which regions report the most loyal or dissatisfied customers?

**3.Methodology**

**A structured data analytics life cycle was followed:**

**Step 1: Data Collection & Cleaning**

* Imported the dataset into Power BI and reviewed for missing values or inconsistencies.
* Cleaned data fields for clarity (e.g., separating Location into City and State).
* Verified numeric formats for satisfaction scores, age, and geolocation.

**Step 2: Data Modeling**

* Created relationships between fields where necessary.
* Added calculated columns:
o	Age_Group (using DAX to categorize ages into 18–25, 26–40, 41–60, 60+)
o	Numeric loyalty levels for easier analysis.
* Built DAX measures for KPIs such as average satisfaction, high loyalty percentage, and support contact rate.

**Step 3: Visualization**

Designed a multi-section dashboard combining KPIs, demographic visuals, behavioral analysis, and geographical insights.
Used slicers and interactive filters (Location, Age, Satisfaction Factor) for flexible exploration.

**Step 4: Analysis & Insight Extraction**

* Interpreted trends and patterns using descriptive analytics and comparative visual storytelling.
* Highlighted actionable insights for business decision-making.
________________________________________
**4.Data Source**

* Dataset: DataDNA Dataset Challenge - Customer Satisfaction Data
* Records: 120 customers
* Fields included:
o	Demographics: Age, Gender, Location (City/State)
o	Behavioral: Purchase History, Support Contacted
o	Attitudinal: Satisfaction Score, Loyalty Level, Satisfaction Factors
o	Geographic: Latitude & Longitude

**5.Tools Used**

**Tool and	Purpose**

Microsoft Power BI Desktop	Main platform for data visualization and dashboard creation
Microsoft Excel	Initial data review, cleaning, and transformation
DAX (Data Analysis Expressions)	Used for calculated KPIs, measures, and dynamic insights
Power Query Editor	Data shaping and preprocessing
Map Visuals (ArcGIS / Filled Map)	Regional satisfaction mapping
________________________________________
**6.Results and Key Findings (with KPIs)**

**Key KPIs Developed**

* Average Satisfaction Rate with Dax Measure of 5.35 and value insight of overall satisfaction level
* High Loyalty level of 31% and value insight of Share of customers marked as highly loyal
* Support Contact Rate of 47%	and value insight of Proportion of customers who reached support
* Total Customers	120	Size of customer dataset
* High Satisfaction % (≥8)	~25%	Customers with strong satisfaction ratings
* Repeat Buyers %	~57%	Customers with multiple purchases

  

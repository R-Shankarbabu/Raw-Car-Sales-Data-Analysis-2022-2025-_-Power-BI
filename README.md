# Raw-Car-Sales-Data-Analysis-2022-2025-_-Power-BI
Power BI project analyzing Raw Car Sales Data Analysis (US) 2022-2025 _ Power BI
Car Sales Analysis - 2022 - 2025

Project Overview:

	This project analysing car sales data in US from 2022 to 2025. 

	The original dataset was obtained from the URL below. 
	Unprocessed car sales data set.
	Raw Car sales Data set

	Three tables in  CSV file with 10,000 rows and 22 columns comprise the original data.

Data Pre-processing using Excel:

               1. Duplicates were found in the Sales ID and eliminated.

2.Customer names are identified and converted to suitable case after arriving in proper case.

3.The customer's name appears in different columns; the concatenate function converts it to a 	single column as the full name; the trim function eliminates non-printable values from the name.

4.Used a nested IF function to generate a new column for the adult category based on age.

5.The Vlookup function is used to transfer necessary data from one table to another.

6.Use Replace Values to eliminate superfluous symbols.



Visualization Using Power BI:

	
1. A line chart and an inbuilt matrix table chart are created to display the overall sales performance from 2022 to 2025; the matrix table specifically describes the percentage growth ratio from year to year. 

2. To show the total sales for each state compared to the average, a line and stacked column chart is made. 

3. A matrix table chart was made to show the overall sales of each car model by year. Using conditional formatting, the bar icon in the cell indicates the amount of sales for that certain year.

4. An explanation of adult versus senior preferences for car models in terms of sales is provided by a clustered column chart.

5. A funnel chart shows sales by automobile segment. Prior to that, cars are divided into four categories based on their pricing. 

6. An eye-catching dash board that displays dynamic sales analysis. Overall sales, average sales, sales by car brand, sales by month, average sales by month, car transmission preferences by gender, top 10 car sales, and sales of gear transmissions by state and amount are all displayed in a map chart with a clear year and month-wise slicer. 

Summary and Insights:

 	The company experienced hyper-growth in 2023, sustaining momentum into 2024.
 	The YoY growth percentages are unusually high, likely due to the sharp jump from 2022 to 2023, which skews later comparisons.
 	Mississippi recorded the highest overall sales, standing out as the top-performing state.
 	Some mid-tier states show higher average sales despite lower overall totals, indicating fewer but larger transactions.
 	West Virginia had the lowest overall sales, marking it as the weakest region.
 	Adults consistently outnumber Seniors across all brands, indicating stronger purchasing power or preference.
 	Toyota and Hyundai stand out as brands with higher Senior engagement, suggesting broader appeal across age groups.
 	Tesla, BMW, and Nissan are more Adult-driven brands, with limited Senior adoption.
 	The market is dominated by Premium cars, suggesting customers lean toward higher-end models.
 	Luxury and Compact segments are competitive, with similar volumes, showing balanced demand.
 	Economy cars underperform, possibly due to shifting consumer focus toward value-added or feature-rich vehicles.
📈 Highest-Selling Models (Total Sales)
	Camry: 73.6M — top performer overall
	Sunny: 73.4M — nearly tied with Camry
	Sportage: 71.8M — strong and consistent growth
	Model X: 64.8M — Tesla’s best-selling model
	GLA: 64.6M — Mercedes’ standout SUV
📉 Lowest-Selling Models
	Seltos: 32.3M — lowest among all listed
	Qashqai & Corolla:  45M each — modest performers
Strategic Observations
•	SUVs dominate the top ranks (Sportage, Sunny, GLA, Model X)
•	Sedans like Camry and C-Class still hold strong market share
•	Sales dip in 2025 may signal market saturation or shifting consumer preferences.


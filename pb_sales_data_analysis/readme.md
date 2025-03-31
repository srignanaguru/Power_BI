# Sales Performance Report - Power BI
##Overview
This project demonstrates data transformation, modeling, visualization, and DAX calculations in Power BI to generate a sales performance report. The key aspects covered include data cleaning, interactive visualizations, trend analysis, and calculated measures.

Steps Performed
1.**Data Cleanup with Power Query**

- Used Power Query to transform the sales table data.
- The Country/Geography column contained unwanted spaces, which were removed using the Trim function.
- Loaded the cleaned data back into Power BI.

2. **Handling Null Values**
- The People Table had null values in the Salesperson column.
- Created a separate reference table to identify the salesperson associated with the null values.
- Null values were replaced with "Special" in the Salesperson column.

3. **Interactive Visualizations**
- Created an interactive dashboard where all visuals respond dynamically to user selections.
- Used filters and slicers to limit data visibility and improve insights.

4. **Sales Performance Analysis**
- Created a Total Sales Amount measure using DAX.
- This measure is represented with a calculator icon in the dataset.
- Applied conditional formatting to highlight key sales values.
- Created additional measures such as:
- Total Boxes Sold
- Amount Per Box

5. **Data Modeling & Relationships**
- Added a new column table representing Total Amount by Category.
- Edited visual interactions to ensure filtered values impact only relevant visuals.
- Added a Geographical vs. Total Amount column visualization with highlighting.

6. **Trend Analysis**
- Created a Line Chart to visualize Total Customers vs. Year for trend analysis.
- Performed forecasting for the next three months based on past sales trends.
- Applied the same trend analysis for Total Amount vs. Year.

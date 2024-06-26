# Govind-stores-ecommerce-sales-dashboard

Overview
This guide provides a step-by-step approach to creating an insightful sales dashboard for Govind's E-Commerce store using Power BI. The dashboard will display key metrics and visualizations, such as profit by month, profit by sub-category, and orders by category. By following these steps, you will be able to transform raw Excel data into an interactive and visually appealing Power BI dashboard.

###Step

#### 1. ###SetUpYourExcelData
- Ensure your Excel data is clean and organized. Common columns might include `Order ID`, `Order Date`, `Category`, `Sub-Category`, `Amount`, `Profit`, `Quantity`, and `Payment Mode`.

#### 2. ###LoadDataintoPowerBI
- Open Power BI Desktop.
- Click on `Home` -> `Get Data` -> `Excel`.
- Select your Excel file and load the data.

#### 3. ###CreatingtheDashboardHeading
- Go to the `Insert` tab.
- Click on `Text box`.
- Enter the text, e.g., "Govind's E-Commerce Sales Dashboard".
- Format the text by making it bold, center-aligned, and resize as needed.

#### 4. ###InsertYourFirstChart: Profit by Month
- On the right side, under `Visualizations`, select a `Column chart`.
- Drag `Order Date` to the X-axis and `Profit` to the Y-axis.
- If the `Order Date` isn't recognized as a date, go to `Data view`, select `Order Date`, and change its data type to `Date`.
- Format the chart:
  - Go to `Format` pane -> `Title`, and enter "Profit by Month".
  - Customize axis titles and data colors as needed.
  
#### 5. ###FiltertoDisplayDailyData
- To filter by daily data, click on the `Order Date` dropdown in the `Fields` pane.
- Select the desired date granularity (e.g., daily).
- To return to the default view, select "All" in the filter options.

#### 6. ###CreateaStackedBarChart: Profit by Sub-Category
- Select a `Stacked bar chart` from `Visualizations`.
- Drag `Sub-Category` to the Y-axis and `Profit` to the X-axis.
- Apply a Top N filter:
  - Click on the chart, go to `Filters on this visual`.
  - Select `Sub-Category`, choose `Top N`, and enter the number (e.g., 5).
  - Drag `Profit` to `By value`.

#### 7. ###InsertaPieChart: Orders by Category
- Select a `Pie chart` or `Donut chart` from `Visualizations`.
- Drag `Category` to `Legend` and `Quantity` to `Values`.
- Format the chart by adjusting legend position, colors, and data labels.

#### 8. ###AddCardsforKeyMetrics
- Select the `Card` visual from `Visualizations`.
- Drag `Amount` to the `Fields` pane of the card to display total sales.
- Format using the `Format Painter` tool to match styles.
- Copy and paste the card to display different metrics (e.g., `Profit`, `Quantity`):
  - Adjust the field in each card to reflect the correct metric.

#### 9. ###CustomizeBackgroundandFormatting
- Click outside any chart to access `Page Background` under `Format`.
- Change the background color or add an image.
- Adjust transparency to ensure the background image is visible.
  
#### 10. ###FinalAdjustmentsandPolishing
- For each chart, right-click and go to `Format visual`.
- Adjust borders, titles, and data colors to ensure consistency.
- Apply conditional formatting rules where necessary (e.g., different colors for positive and negative values).

#### 11. ###SaveandPublish
- Save your Power BI dashboard.
- To share, click on `File` -> `Publish` -> `Publish to Power BI`.

This guide walks through setting up a comprehensive dashboard in Power BI using Excel data, focusing on various visualizations and customization techniques to enhance readability and functionality.

summary
By following this guide, you will be able to create a comprehensive and visually appealing sales dashboard for Govind's E-Commerce store. This dashboard will help you track performance, identify trends, and make informed business decisions. Save your work regularly and share your insights with stakeholders by publishing the dashboard to Power BI. Happy analyzing!

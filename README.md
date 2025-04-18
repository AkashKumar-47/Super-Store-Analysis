# Super-Store-Analysis
The goal of this project is to provide an interactive dashboard that gives comprehensive insights into the sales performance of the SuperStore. The dashboard helps in understanding: Sales trends over time, Performance across different categories and shipping modes.


## Project Objective
The goal of this project is to provide an interactive dashboard that gives comprehensive insights into the SuperStore Sales dataset and offers a short‐term sales forecast to guide business planning. The dashboard helps in understanding:

- Sales trends over time.
- Performance across different categories, sub-categories, and shipping modes.
- Geographic distribution of sales using interactive maps.
- Detailed KPI cards displaying sales, orders, profit, and average shipping days.
- Comparative analysis based on segments, regions, and payment modes.
- Short‐term 15‐day forecast to estimate upcoming sales volume and potential demand.

## Key Questions & KPIs
The dashboard is built around answering the following strategic questions:
- **Sales by Category and Sub-Category:**  
  How do different product categories perform in terms of overall sales and profit?
- **Shipping Modes:**  
  Which shipping modes are most frequently used, and how do they influence delivery times?
- **Geographic Insights:**  
  Which states have higher sales volumes and how is the geographical spread?
- **Time-Series Analysis:**  
  What are the monthly sales and profit trends over the years?
- **Customer Segmentation:**  
  How do sales vary across different segments and regions?

## Key Performance Indicators include:
- **Total Sales:** Overall revenue from the dataset.
- **Total Orders:** Count of orders placed.
- **Profit:** Net profit after accounting for returns and expenses.
- **Average Shipping Days:** Efficiency in the shipping process.

## Process of the Project
The project followed these steps:

1. **Data Collection & Preprocessing:**  
   - Imported the <a href="https://github.com/AkashKumar-47/Super-Store-Analysis/blob/main/SuperStore_Sales_Dataset.csv">SuperStore Sales Dataset</a> into Power BI.
   - Cleaned data to handle missing values, data type conversions, and outliers.
2. **Exploratory Analysis:**
   - Identified high‐level trends in sales, profit, and quantity.
   - Segmented data by region, category, sub‐category, and shipping mode.
3. **Dashboard Development in Power BI:**  
   - Visualizations:
       - **Sales by Category & Sub‐Category:** Compare performance across product lines.
       - **Map Visualization:** Illustrates state‐level sales with bubble sizes representing sales volume.
       - **Monthly Sales & Profit:** Displays year‐over‐year performance.
       - **Sales by Segment, Region, Payment Mode:** Quickly assess relative contribution of each slice.
       - **KPI Cards:** Show top metrics like total sales, orders, profit, and average shipping days.
       - **15‐Day Sales Forecast:** Uses built‐in Power BI forecasting to predict short‐term sales.
    - Filters and Slicers:
       - Region slicer for geographic focus.
       - Year & Quarter slicer for time‐based analysis.
       - A bookmark button to Clear All Filters and return to default view.
4. **Forecasting**
    - Leveraged Power BI’s built‐in forecasting feature on the Sales by Order Date measure.
    - Produced a 15‐day forecast to anticipate near‐future sales.
    - Visualized forecast intervals (confidence bands) to understand upper and lower bounds.
5. **Analysis & Refinement:**  
   - Iteratively refined the dashboard based on testing, feedback, and exploratory data analysis.
   - Validated insights through cross-checking with the raw dataset.

## Dashboard Image
![Screenshot 2025-04-09 131140](https://github.com/user-attachments/assets/959749e1-2bf0-4917-88b7-fb5777a4790b)

## Project Insights
Key insights derived from the analysis include:
- **Category Performance:**  
  Certain product categories and sub-categories drove higher sales, indicating a focus area for marketing and inventory decisions. This underscores the importance of targeting products with higher profit margins or consistent demand.
- **Shipping Efficiency:**  
  Shipping mode analysis indicates which methods are popular and how they correlate with average shipping days, helping optimize logistics.
- **Geographical Trends:**  
  Some states consistently have higher sales volumes, suggesting expansion or marketing campaigns may be beneficial there.
- **Temporal Trends:**  
  Monthly sales and profit trends reveal seasonality and growth patterns. These can be tied into promotional schedules.
- **Short‐Term Forecast**
  The 15‐day sales forecast offers actionable insights for inventory planning, staffing needs, and marketing pushes. By understanding the upper and lower confidence limits, businesses can mitigate risk and be       prepared for demand surges.
- **Customer Segmentation:**  
  Analyzing sales by segment and region sheds light on priority demographics and regional preferences.

## Final Conclusion
The Power BI dashboard comprehensively visualizes the SuperStore dataset and extends its utility by providing a 15‐day sales forecast. The forecasting feature helps in strategic planning and resource allocation. In summary:
- **Data‐Driven Decisions:** Implementing real data insights can drive improved sales strategies and operational efficiencies.
- **Forecasting Value:** Short‐term forecasts serve as an early alert system for demand fluctuations.

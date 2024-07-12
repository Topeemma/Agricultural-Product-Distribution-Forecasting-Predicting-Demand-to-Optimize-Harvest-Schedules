 Project Description

This project aims to predict the demand for various agricultural products to optimize harvest schedules. By using machine learning models, the project provides insights into demand patterns, key influencers, and product variability. The goal is to help agricultural businesses adjust their harvest schedules, diversify their product offerings, and enhance data collection methods for more accurate forecasting.


Tech Stack
 

✓ Pandas
✓ NumPy
✓ SciPy
✓ Matplotlib
✓ Seaborn
✓ Statsmodels
✓ Prophet
✓ Scikit-learn
✓ ARIMA

 Findings

1. Demand Patterns:

  - Seasonality significantly influences demand, with certain months showing peaks.



2. Key Influencers:

  - Weather conditions, particularly temperature and rainfall, have a strong correlation with demand.



3. Product Variability:

  - Different products exhibit varied demand patterns and seasonal peaks.



Recommendations

1. Adjust Harvest Schedules:

  - Use demand forecasts to align harvest schedules with market demand.



2. Diversify Product Offering:

  - Diversify the product range to stabilize revenue throughout the year.



3. Enhance Data Collection:

  - Improve data collection methods for more accurate and comprehensive forecasting.



4. Leverage the Best Performing Model:

  - Utilize the RandomForestRegressor for demand forecasting due to its superior performance.



5. Tailor Strategies to Product-Specific Insights:

  - Strawberries: Focus on refining the model to maintain accuracy.

  - Apples: Explore additional features to improve the model further.

  - Tomatoes, Carrots, and Lettuce: Improve data quality and add specific features to reduce errors.



6. Model Improvement and Maintenance:

  - Regularly monitor and retrain the model with new data to adapt to changing market conditions.



7. Data Collection Enhancements:

  - Collect higher quality and more granular data, especially for products with higher prediction errors.



8. Hybrid Models:

  - Consider using hybrid models for short-term and long-term predictions.



 Future Work

1. Incorporate More Variables:

  - Include additional factors like market trends and competitor data.



2. Continuous Model Improvement:

  - Regularly update and refine models to adapt to changing market conditions.



3. Real-time Forecasting:

  - Implement real-time data processing and forecasting for responsive decision-making.



 Data Dictionary

- Date: The date of data recording.

- Product: The type of agricultural product.

- Location: The location where the product is harvested or sold.

- Customer: The customer purchasing the product.

- Quantity_Sold: The quantity of product sold.

- Revenue: The revenue generated from sales.

- Temperature_Celsius: The temperature at the time of harvest/sale.

- Rainfall_mm: The rainfall measured at the time of harvest/sale.

- Transportation_Cost: The cost of transporting the product.

- Labor_Cost: The cost of labor for harvesting/processing.

- Quality_Score: The quality score of the product.

- Inventory_Level: The level of inventory at the time of data recording.



 Model Performance Summary

- Strawberries:

 - RandomForestRegressor: 5.482484

 - ARIMA: 8.252509

 - Prophet: 8.665478



- Apples:

 - RandomForestRegressor: 3.627103

 - ARIMA: 7.672138

 - Prophet: 10.521305



- Tomatoes:

 - RandomForestRegressor: 6.526076

 - ARIMA: 11.009154

 - Prophet: 12.012712



- Carrots:

 - RandomForestRegressor: 4.069554

 - ARIMA: 11.643805

 - Prophet: 18.719716



- Lettuce:

 - RandomForestRegressor: 6.312475

 - ARIMA: 11.280264

 - Prophet: 16.485064



- Average:

 - RandomForestRegressor: 5.203539

 - ARIMA: 9.971574

 - Prophet: 13.280855


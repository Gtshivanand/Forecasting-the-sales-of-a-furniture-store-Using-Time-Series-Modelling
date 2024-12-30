  # Forecasting-the-sales-of-a-furniture-store-Using-Time-Series-Modelling
  
   This project focuses on forecasting the sales of a furniture store utilizing Time Series Modeling techniques. The analysis involves data cleaning, visualization, and modeling of sales data to predict future trends, ultimately optimizing business decision-making.
 
  # Abstract:
  Effective sales and inventory management is crucial for any retail business. One of the most challenging aspects for retail stores is predicting future sales and the required inventory to maintain an optimal stock level. By forecasting sales, businesses can avoid overstocking and under-stocking, ensuring an enhanced customer experience while minimizing losses. This project aims to predict future sales trends for a furniture store, supporting better business planning and sustainable operations.
  The goal of this project is to forecast the future sales of a furniture store using time series modeling techniques. By analyzing historical sales data, identifying trends and seasonality, and building a predictive model, this project aims to help the store optimize inventory, plan marketing strategies, and improve overall business performance.
  
  # Problem Statement:
  The objective is to read sales data from a furniture store and forecast sales for the next year, helping the business anticipate demand and optimize operational strategies.
  
  # Dataset  Overview:
  The dataset provides detailed information about sales, products, and customer interactions within the furniture store. This data can be leveraged to uncover insights and identify opportunities for improvement in sales and inventory management.

  The dataset includes the folowing features:
  
  1. Row ID: Unique identifier for each record.
  
  2. Order ID: Unique identifier for each order.
  
  3. Order Date: Date the order was placed.
  
  4. Ship Date: Date the order was shipped.
  
  5. Ship Mode: The shipping method used (e.g., Standard, Express).
  
  6. Customer ID: Unique identifier for each customer.
  
  7. Customer Name: Name of the customer.
 
  8. Segment: The business segment the customer belongs to (e.g., Consumer, Corporate, Home Office).
  
  9. Country, City, State, Postal Code, Region: Location details of the customer or shipping address.
  
  10. Product ID: Unique identifier for each product.
  
  11. Category: The broad category the product belongs to (e.g., Office Supplies, Furniture).
  
  12. Sub-Category: More specific classification within the category (e.g., Chairs, Binders).
 
  13. Product Name: The name of the product.
  
  14. Sales: The total sales value of the product for the order.
  
  15. Quantity: The number of units ordered.
  
  16. Discount: Any discount applied to the order.
  
  17. Profit: The profit earned from the order.
  
  # Scope:
  ●	Understanding time series data
  
  ●	Checking components of time series 
  
  ●	Forecasting using various time series techniques
 
  ●	Understanding the visualization involved in time series

  # Content:
  
  1. **[Import packages](#import_packages)**
  2. **[Load data](#load_data)**
  3. **[Data preparation](#data_preparation)**
      - 3.1 - [Dimensions of Dataset](#data_dimension)
      - 3.2 - [Statistical Summary](#Stat_sum)
      - 3.3 - [Checking Data Type and Missing Values](#check_data_type)
      - 3.4 - [Indexing with Date](#Indexing_with_Date)
  4. **[Time Series Analysis](#Time_Series_Analysis)**
      - 4.1 - [Visualizing data](#Visualizing_data)
      - 4.2 - [Sampling](#Sampling)
      - 4.3 - [Checking Stationarity](#Checking_Stationarity)
      - 4.4 - [Decomposing](#Decomposing)
  5. **[Time Series Forcasting using ARIMA](#Time_Series_Forcasting_using_ARIMA)**
      - 5.1 - [Parameter Selection](#Parameter_Selection)
      - 5.2 - [Fitting the ARIMA model](#Fitting_the_ARIMA)
      - 5.3 - [Validating Forecasts](#Validating_Forecasts)
      - 5.4 - [Calculating MSE and RMSE](#Calculating_MSE_and_RMSE)
      - 5.5 - [Visualizing the Forecast](#Visualizing_the_Forecast)
  6. **[Conclusion](#Conclusion)**

  # Contact: 
  
  For any inquiries or suggestions, feel free to reach out:
  
  - *Email:* [shivanandnashi97@gmail.com](mailto:shivanandnashi97@gmail.com)
  - *LinkedIn:* [Shivanand Nashi](https://www.linkedin.com/in/shivanand-s-nashi-79579821a)
  
      
    

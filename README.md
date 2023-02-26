# Regression-Project
Regression Analysis on the Demand of Corporation Favorita Products

Corporation Favorita, a retail company, seeks to optimize its stock management system by accurately predicting the demand for its products. To achieve this, they have collected several datasets containing historical sales data, store locations, holidays, and oil prices. The company hopes to use this data to develop a machine learning model that can accurately forecast future demand and inform purchasing and stocking decisions.

To begin, we checked if the training dataset contains any missing values or duplicate dates. If either of these conditions was met, the dataset would not be complete, and it would not be possible to develop an accurate machine learning model. Fortunately, the dataset was complete, which means we can proceed to the next step.

Next, we conducted exploratory data analysis (EDA) to gain insights into the data and answer some of the questions posed by Corporation Favorita. We explored the data to determine which dates had the lowest and highest sales for each year. We also looked for trends in sales over time and identified any correlations between oil prices, promotions, and holidays, and sales.

We also investigated whether certain groups of stores were selling more products than others. We clustered the stores by city, state, and type to identify any patterns in sales by store group. We also explored the relationship between individual products and sales to determine which products were selling the most and which products had the highest demand during holidays and promotions.

To prepare the data for machine learning modeling, we performed feature processing and engineering. We transformed the date column into a datetime object to create new features such as the year, month, and day of the week. We also created features for holidays, promotions, and oil prices, which we believed could influence demand.

Finally, we developed a machine learning model using regression analysis to predict future demand accurately. We used past sales data to identify patterns in demand and develop a model that could forecast future demand. This model would then be used to inform purchasing and stocking decisions, reducing the likelihood of stockouts and overstocking.

In conclusion, using machine learning to forecast demand can significantly improve stock management for corporations like Favorita. By leveraging historical sales data, store locations, holidays, and oil prices, companies can develop accurate forecasting models that can inform purchasing and stocking decisions. By reducing stockouts and overstocking, companies can optimize their operations and maximize profits.

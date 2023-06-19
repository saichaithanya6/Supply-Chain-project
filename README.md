## About the company
The project is about an unknown homebody furniture sales forcasting and evaluation. Below is a brief of homebody furniture and assumptions made for the project.
Homebody is a furniture company that focuses on providing high-quality, stylish, and comfortable furniture for customers who want to create a cozy and welcoming home. The company was founded by a group of friends who shared a passion for interior design and a belief that furniture should be both functional and elegant.
One of the unique features of Homebody is their "white glove delivery" service, which means that their furniture is delivered directly to the customer's home, unpacked, and assembled by a team of professional delivery drivers cum assemblers. This ensures that the furniture is delivered in perfect condition and that customers can start enjoying it right away.

Homebody furniture shop could use a forecasting technique such as the ARIMA model to predict sales for the upcoming year. By using historical sales data, the model could be trained to forecast 
sales for each month, considering the seasonality and trend. Sales forecasting is an essential aspect of any business strategy. Using the forecasted sales, the Homebody furniture shop could make better decisions about inventory management, production planning, and marketing campaigns. For example, the shop could increase production of sofas during the holiday season when the sales are typically high. 
By predicting the future demand for a product, Homebody furniture can make informed decisions about how much inventory they need to stock, how much to produce, and how to promote their products to maximize sales. Additionally, the shop could launch targeted marketing campaigns to promote sofas during the months where sales are typically low, such as in the middle of the year.
By using a forecasting technique to predict sales, the furniture shop can improve their ability to meet customer demand, reduce costs associated with excess inventory or shortages, and increase overall profitability.

## Forecasting furniture sales
Based on the plots given below, it is evident that the sales of furniture in the Homebody furniture shop exhibit a clear seasonality pattern, with sales being low at the beginning of the year and high at the end of the year. Additionally, there is an upward trend within each year, with a few low months in the middle of the year. To take advantage of this seasonality pattern and trend, the Homebody furniture shop could use a forecasting technique such as the ARIMA model to predict sales for the upcoming year. By using historical sales data, the model could be trained to forecast 
sales for each month, considering the seasonality and trend. Sales forecasting is an essential aspect of any business strategy. Using the forecasted sales, the Homebody furniture shop could make better decisions about inventory management, production planning, and marketing campaigns. For example, the shop could increase production of sofas during the holiday season when the sales are typically high. 
By predicting the future demand for a product, Homebody furniture can make informed decisions about how much inventory they need to stock, how much to produce, and how to promote their products to maximize sales. Additionally, the shop could launch targeted marketing campaigns to promote sofas during the months where sales are typically low, such as in the middle of the year.
By using a forecasting technique to predict sales, the furniture shop can improve their ability to meet customer demand, reduce costs associated with excess inventory or shortages, and increase overall profitability.

![image](https://github.com/saichaithanya6/Supply-Chain-project/assets/111531760/8f133c4b-0e9e-4ff6-8689-f774b2afbc07)


## Building the Model
Having a comprehensive sales pattern for a workshop is crucial to ensuring efficient inventory management, production planning, and successful marketing campaigns. Analyzing historical sales data is a critical component in identifying trends and seasonality patterns that help to accurately forecast future sales. The ARIMA model is a commonly used statistical technique that leverages historical sales data analysis to forecast future sales. By examining past sales data patterns and relationships, the ARIMA model enables businesses to develop an equation that predicts future sales figures. The use of this model allows furniture shops to optimize sales and inventory management, allocate resources effectively, and make informed business decisions that lead to profitability and growth. Overall, having a deep understanding of sales patterns and utilizing the ARIMA model is essential for any workshop looking to succeed in the furniture industry.
To start, we selected furniture sales data from January 2017 to August 2017 and cleaned the dataset by removing null values. Below gives a glimpse of the data.

![image](https://github.com/saichaithanya6/Supply-Chain-project/assets/111531760/af1d5e10-e24f-42ab-a295-2142929ce789) ![image](https://github.com/saichaithanya6/Supply-Chain-project/assets/111531760/9a1af02a-c864-4f79-aef7-7a08b45c3341)


We then tested if the data was stationary or non-stationary using the Augmented Dickey-Fuller (ADF) test. The ADF test result indicated that the furniture sales data was stationary, meaning that it lacked any time-dependent structure

![image](https://github.com/saichaithanya6/Supply-Chain-project/assets/111531760/4e7e3ced-03e5-45d9-b1fa-b71f4382017f)

Next, we decomposed the time series data into three distinct components - trend, seasonality, and noise - to better understand the sales patterns. The visualization of the decomposition components showed that the sales of furniture were unstable and required an ARIMA(p,d,q) model.

![image](https://github.com/saichaithanya6/Supply-Chain-project/assets/111531760/344b1092-5bc2-452c-ae07-7b2d4309d080)                ![image](https://github.com/saichaithanya6/Supply-Chain-project/assets/111531760/a72bce0e-03e4-41eb-a980-77f155d97b56)


We then used the ARIMA model to forecast future furniture sales, taking into account the identified seasonality and trend.
![image](https://github.com/saichaithanya6/Supply-Chain-project/assets/111531760/f9ef6135-57cf-4f64-8bb3-a6305bedcb00)


The Root Mean Square Error (RMSE) showed that the model could forecast average daily furniture sales in the test set with an error margin of 151.64 units from the actual sales. The range of daily furniture sales varied between 400 and over 1200 units, indicating that the model performed well.

![image](https://github.com/saichaithanya6/Supply-Chain-project/assets/111531760/3fc1d591-8148-468e-80b7-f20fea0688c8)

Additionally, the shop could launch targeted marketing campaigns to promote sofas during the months where sales are typically low, such as in the middle of the year.
As discussed, ARIMA model is the most popular techniques for sales forecasting. This model uses statistical analysis to identify trends and patterns in past sales data, which can then be used to predict future sales. The ARIMA model is particularly useful for businesses that have seasonal fluctuations in demand, as it can capture these 
patterns and adjust its forecasts accordingly.

![image](https://github.com/saichaithanya6/Supply-Chain-project/assets/111531760/d37ed984-6247-4a43-bc2a-978341cc898b)


By using a forecasting technique such as the ARIMA model to predict furniture sales, we can improve our ability to meet customer demand, reduce costs associated with excess inventory or shortages, and increase overall profitability.











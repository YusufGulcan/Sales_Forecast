# Sales_Forecast
This repository includes an example for predicting sales using the darts library in Python.
Libraries:
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- holidays
- statsmodels
- scipy.stats
- datetime
- darts
- sklearn

Title: Time Series Analysis and Forecasting for Store Products

Introduction:
In this repository, we present a comprehensive exploratory time series data analysis for a collection of store products. We dive into the intricacies of processing time series data, demonstrate techniques like grouping, filtering, and looping, and create machine learning models to forecast sales for different product-store clusters. Throughout the article, we outline the thought processes behind feature engineering, cluster creation, and statistical tests to compare sales during regular and promotion days.

1. Exploratory Time Series Data Analysis:
We begin by conducting a thorough exploratory analysis of the time series data. Utilizing graphical presentations, we visually investigate trends, seasonality, and other patterns in the sales data. The graphical representations provide valuable insights into the behavior of the products over time, helping us understand the temporal dependencies and identify potential issues.

![ReturnvsSales](https://github.com/YusufGulcan/Sales_Forecast/assets/105684729/08ca0b96-2981-4aca-9837-c5dc2f928290)

3. Time Series Data Processing:
The repository showcases various time series data processing techniques. We group the data based on specific criteria, filter relevant data subsets, and leverage looping techniques to perform calculations across multiple time series. These methods are essential for preparing the data for further analysis and modeling.

4. Cluster Creation for Products and Stores:
To better understand the sales patterns, we create three clusters from a vast collection of over 300 products and 300 stores. Clustering allows us to identify distinct groups with similar sales behaviors, enabling targeted analysis and forecasting for each cluster.

5. Feature Engineering:
Feature engineering plays a pivotal role in developing accurate time series models. We provide an in-depth explanation of our thought processes while creating new features from the available data. These engineered features capture important temporal relationships, seasonal effects, and other relevant information, enhancing the predictive power of our models.


![Distributionpng](https://github.com/YusufGulcan/Sales_Forecast/assets/105684729/2499ae3a-f46f-4f38-aa00-3afc525056ab)

7. Machine Learning Models for Product-Store Clusters:
We build machine learning models to forecast sales for each product-store cluster. Nine models are developed, each tailored to a specific cluster, ensuring accurate and granular predictions. By customizing the models to the unique characteristics of each cluster, we optimize their performance and forecast reliability.

8. Forecasting the Future:
Using data from 212 days, we demonstrate how our models can accurately forecast the next 40 days of sales for each product-store combination. The forecasting results offer valuable insights for inventory management, production planning, and sales optimization.

9. Comparing Sales on Regular and Promotion Days:
To assess the impact of promotions, we perform statistical tests to compare the sales during regular and promotion days. This analysis helps us understand the effectiveness of marketing strategies and informs future promotional campaigns.

Conclusion:
This repository provides a comprehensive guide to performing exploratory time series data analysis, developing customized machine learning models, and forecasting sales for a diverse range of store products. By showcasing the application of various data processing techniques, feature engineering, and statistical tests, we offer valuable insights for optimizing sales strategies and improving business decision-making. Through this article, readers gain a deeper understanding of time series analysis and its significance in extracting meaningful information from temporal data.




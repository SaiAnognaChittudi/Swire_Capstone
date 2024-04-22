# Swire_Capstone
![Swire-Coca-Cola](https://github.com/SaiAnognaChittudi/Swire_Capstone/assets/144569057/9566787a-4ef1-4556-beaf-407d5d7346bf)

## Introduction

Swire Coca-Cola consistently brings fresh, inventive products to market, diversifying its offerings to align with shifting consumer trends. This strategy, marked by unique products and premium pricing, expands market reach and attracts new customers. So, Swire Coca-Cola wants to optimize its production planning and inventory management for these Innovation Products.

The focus of the capstone project involves crafting a comprehensive forecasting model. This model seeks to address key questions regarding optimal timing and geographic regions for the launch of upcoming innovation products, as well as predicting the volume of units likely to be sold within the suggested timeframe.


## Project Objectives

The main Project objectives are listed as below:

1. Predicting the anticipated sales volume for the innovation products prior to their launch.
   
2. Conducting forecasting for the innovation products to address Swire's inquiries regarding the optimal timing and regional-based approach of product launches.

3. Ensure the model's capability to update forecasts based on new innovation products data, ensuring a continuous improvement in forecast accuracy.

## Group's solution to the business problem

The Solution provided by our group is implementing the Prophet model as the optimal solution, primarily due to its ability to yield the lowest Mean Absolute Percentage Error (MAPE) value compared to other models. With this model, we can generate comprehensive forecasts for product demand, encompassing trends, seasonality, and holiday effects specific to each country. Additionally, we have developed a custom function to refine the trend and seasonality components further, tailoring them to suit the unique parameters of each product model.

Utilizing this machine learning model enables us to continually update the sales forecast for upcoming weeks. This allows Swire to make informed decisions regarding the product's continuation or discontinuation in the market. Moreover, our model effectively addresses queries regarding the ideal 13-week period and optimal holiday season for launching that particular product in the market.

## My Contribution to the Project

1. Extracting datasets from BigQuery to Python files according to the features of each new innovation product.
2. Crafting the introduction for the notebook and formulating initial questions for the exploratory data analysis (EDA), aiding group members in their EDA process.
3. Incorporating bar charts for the Category and Manufacturer fields to gain a holistic understanding of category positions across all years, rather than segmenting by year.
4. Consolidating all individual EDA analyses, comprising both Python notebooks and Tableau graphs, into a single Python Notebook for group submission.
5. Initiating data checks in BigQuery to ensure alignment of attributes with the New Innovation products for each question, thereby optimizing forecast accuracy.
6. Developing Prophet models for the innovation products alongside visualizations and hyperparameter tuning for each dataset individually.
7. Integrating models contributed by team members and synthesizing findings to present conclusions that reflect the outcomes derived from the models.

## Business Value of Solution

The prophet model has provided significant results for the innovation products that are being planned. With the MAPE value as less as 9.38 percent we can see that the forecasted values have the true positive value more than 90% of times. 

For the 1st innovation product with the flavor plum, we find that the MAPE is around 29, which means that Forecasting is correct 70% of the time. For the 2nd innovation product with the flavor Avacado, the Forecast is corect 90% of the times as the MAPE value is only 10, which is similar to the 3rd innovation product with the flavor kiwano as well.

Apart from the percentage of forecast, we had found answers for the Questions asked like which 13 weeks is best for the Products and how the sales for Avacado product during the time of Easter which is found to have the demand of around 7000-9000 units each week. This provides the Swire the correct estimate for each week and thus reducing the cost of underproduction and overproduction for these products.

## Difficulties faced by the Group during project

The primary challenge lies in handling the massive volume of data, which poses difficulties in reading and processing within Python notebooks due to substantial computing requirements. As a solution, our group opted to retrieve only the necessary data from BigQuery, leveraging SQL coding to make the required modifications to the data.

Following this, another challenge emerges in evaluating data quality, comprehending column distributions, and addressing missing values. These obstacles are effectively managed within the EDA notebook. Subsequently, comprehending the intricate time-series patterns encompassing holidays and seasonality variations posed a significant challenge during model development.

The final challenge entails selecting and refining forecasting models, such as XGBoost, ARIMA, SARIMA, Random Forest, and Prophet. Achieving optimal performance necessitated iterative experimentation, given the complexity of sales data for innovation products, where direct historical data is unavailable.


## Learnings from the project

The project provided valuable learning experiences and insights, contributing to both technical and collaborative skills. Here are some key takeaways:

### 1. Data Handling and Preprocessing: 
Dealing with real-world datasets involved mastering techniques for data cleaning, handling missing values, and preprocessing to ensure the quality and integrity of the data.

### 2. Time Series Forecasting: 
Acquiring a deep understanding of time series forecasting techniques, including the implementation of XGBoost,ARIMA,SARIMA and Prophet models, enriched our knowledge in effectively capturing and predicting complex patterns within sequential data.

### 3. Collaborative Teamwork: 
Working within a team taught the importance of effective collaboration, clear communication, and coordinating individual contributions to ensure a cohesive and comprehensive project outcome.

### 4. Problem-Solving and Adaptability: 
Overcoming challenges, such as data integration complexities and model selection, enhanced problem-solving skills. Adaptability to evolving requirements and continuous refinement of approaches were crucial.

### 5. Presentation and Communication Skills: 
Preparing and presenting results to stakeholders improved our ability to convey technical concepts in a clear and concise manner, fostering effective communication with both technical and non-technical audiences.

### Overall, the project provided a holistic learning experience that transcended technical aspects, emphasizing the importance of collaboration, adaptability, and a business-oriented mindset in the field of data analytics.







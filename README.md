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

1. Extracting datasets from BigQuery to Python files.
2. Crafting the introduction for the notebook and formulating initial questions for the exploratory data analysis (EDA), aiding group members in their EDA process.
3. Incorporating bar charts for the Category and Manufacturer fields to gain a holistic understanding of category positions across all years, rather than segmenting by year.
4. Consolidating all individual EDA analyses, comprising both Python notebooks and Tableau graphs, into a single Python Notebook for group submission.
5. Initiating data checks in BigQuery to ensure alignment of attributes with the New Innovation products for each question, thereby optimizing forecast accuracy.
6. Developing Prophet models for the innovation products alongside visualizations and hyperparameter tuning for each dataset individually.
7. Integrating models contributed by team members and synthesizing findings to present conclusions that reflect the outcomes derived from the models.

##







# Price Elasticity Model

| Model Information | Description |
| --- | --- |
|Language| Python|
|Libraries Used| Numpy, Pandas, sklearn, statsmodels, re(Regex), matplotlib, seaborn|
| Dataset | [Electronic_Pricedataset](https://www.kaggle.com/datafiniti/electronic-products-prices)|


**About Portfolio** -Product Price and Cross- Price Elasticities of Advertisment demand, Feature engineering for machine learning (Product Category Labelling) with natural language processing , A/B Player Retention Testing and  games played probability, Price Exploratory Analysis

# 1. Applying Econometrics for Pricing Strategies using Linear Modeling #

- ### [Price Elasticity of Ad Impression Demand]
In following analysis, we would select Best Buy products as main data sample for our price elasticity analysis. For future reference,this model can be implemented in every kind of vendors by e-commerce or brick and mortar by measuring sales demand

 **Hypothesis Proposed**

From Bestbuy laptop sample data in 2017. Is ad impression demand sensitive to its own product price changes? If yes, by how much ad impression demand is sensitive to price change?
 
#### Statistical Model

- Linear Regression

 #### Libraries
 
- **statsmodels, NumPy, Pandas, Matplotlib**

Laptop, Desktop Price Elasticity     |
:-------------------------:|
![](https://github.com/Ankit-Sharma1404/Price-Elasticity-Model/blob/main/Images/1.png)


- ### [Cross-Price Elasticity of Ad Impression Demand]

 **Hypothesis Proposed**

 How much is ad impression demand influenced by main competitors when they change their prices?
 This model help us to know the naturality of competition between prices of our own price product advertised against main competitors price product changes

#### Statistical Model

- Multi Linear Regression

 #### Libraries
 
- **statsmodels, NumPy, Pandas, Matplotlib**

Cross-Price Elasticity of 12 Mac Book     |
:-------------------------:|
![](https://github.com/Ankit-Sharma1404/Price-Elasticity-Model/blob/main/Images/2.png)

# 2. Exploratory Data Analysis EDA #
 
- ### [Price Exploratory Data Analysis]

For further calculation of price elasticities with multilinear regression model. This price exploratory analysis was executed for following reasons:

- Product Condition Selection
- Price Outlier Detection
- Price Distribution Analysis
- Discount Price Correlation with Impression Total Count per Category
- Merchant (e-commerce) Impression Time Analysis

#### Libraries 

- **seaborn, Matplotlib, Pandas and Numpy**  

Price Distribution Plot     | Price Discount Correlation Heatmap
:-------------------------:|:-------------------------:
![](https://github.com/Ankit-Sharma1404/Price-Elasticity-Model/blob/main/Images/3.png)  |  ![](https://github.com/Ankit-Sharma1404/Price-Elasticity-Model/blob/main/Images/4.png)


# 3. Data Cleaning and Preprocessing #


 - ### [E-commerce Product Data Cleaning]
 managing null values, dropping of unused features, text normalization 

#### Libraries 
- **RE(Regex), Matplotlib, Pandas and Numpy**  

Null, Unique and Datatype column values table    |
:-------------------------:|
![](https://github.com/Ankit-Sharma1404/Price-Elasticity-Model/blob/main/Images/5.png)

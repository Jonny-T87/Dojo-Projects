# Item Outlet Sales Influenced by Unique Factors
## The analysis of Item Outlet Sales to Item Type, Item MRP, Item Visibility and Many Others

**Jonny Tesfahun**: 

### Business problem:

How many Items does an Outlet sell based on Item MRPs?\
What are the # of Outlets based on Size?\
What is the Avg. Item MRP and Item weight?\
What are Item Outlet Sales based on Outlet Size?\
What are the Avg. Item Sales based on Outlet Types?\
What is Item MRP for different Item Fat Content?\
What are the Outlet Sales compared to Outlet Tier Locations?\
What are the Item MRP and Outlet Sales based on Outlet Store Type?

### Data:
Source of file is included below,\
https://github.com/Jonny-T87/Dojo-Projects/blob/main/Predict_Sales_ML_Project_1__Final.ipynb \
It is a deep data analysis into sales prediction for food items sold at various outlet stores.


## Methods
- Cleaned the data for any Errors and or Inconsistencies
- Used Histogram, Boxplot, Heatmap, and Pairplot for Visual Exploratory Data Analysis
- Incorporated Interactive Visual Plots for closer analysis of data
- Utilized Machine Learning - Analytics 
- Adopting LinearRegression and RandomForestRegressor models to data
- Evaluated performance of the models based on R2 score, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE)

## Results

The RMSE or Root Mean Squared Error had the least error difference in dollars. An RMSE of 1094, tells us that our model is making an average error of 1,094 dollars on the test data. While, the Random Forest model had an average error of 1,122 dollars on the test data.

#### Visual 1 - Outlet Sales by Outlet Locations
![My Image](https://github.com/Jonny-T87/Dojo-Projects/blob/main/OutletSales_OutletLocation.png)

> Sentence about visualization.
> 
#### Visual 2 - Item Store Sales and Price by Outlet Type
![My Image](https://github.com/Jonny-T87/Dojo-Projects/blob/main/OutletSales_ItemMRP.png)

## Model

Based on the 2 different models (linear & Random Forest) tested on the data set. I determined the best model to implement would be the linear regression model. 

The most important metrics for this model included the R2 or the coefficient score and RMSE or Root Mean Squared Error.

This model and metrics together would solve many complex business problems, such as increasing the price of one item can decrease sales in another item.

## Recommendations:

I would recommend more features be included to the model so that test data predictions can be a little more accurate. This would also avoid a high bias and underfitting of the data. 


### For further information


For any additional questions, please contact **jonnymtesfahun@gmail.com**

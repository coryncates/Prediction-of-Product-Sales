
# Project 1 Revisited - Supermarket Sales Prediction

## Overview
This project aims to predict supermarket sales, focusing on enhancing predictive models and providing detailed interpretations of the results. Two main models, Linear Regression and Random Forest, are employed to understand the significant features impacting sales.

## Stakeholder Observations
Detailed observations and insights are crucial for stakeholders to comprehend the model's predictions and make informed decisions. The observations are based on extensive analysis and visualizations, providing a comprehensive understanding of the supermarket sales data and model outcomes.



## Linear Regression Coefficients

### Linear Regression Coefficients Interpretation
![Linear Regression Plot](https://github.com/coryncates/Prediction-of-Product-Sales/blob/main/Lin.png?raw=true)

The Linear Regression coefficients plot reveals the influence of each feature on the predicted supermarket sales. Each coefficient represents the change in sales for a one-unit change in the respective feature, assuming other features remain constant.

1. **Item_MRP:** A positive and high coefficient suggests that the Maximum Retail Price (Item_MRP) has a significant positive impact on sales, indicating that items with higher prices tend to have higher sales.
2. **Outlet_Type_Supermarket Type3:** The positive coefficient for this feature suggests that being of 'Supermarket Type3' type is associated with increased sales, implying that outlets of this type generally experience higher sales.
3. **Outlet_Type_Supermarket Type1:** This feature also has a positive coefficient, indicating that 'Supermarket Type1' outlets tend to have higher sales, but the impact is less compared to 'Supermarket Type3' outlets.


## Random Forest Feature Importances

### Random Forest Feature Importances Interpretation
![Random Forest Importances Plot](https://github.com/coryncates/Prediction-of-Product-Sales/blob/main/Reg.png?raw=true)

The Random Forest feature importances plot illustrates the significance of each feature in predicting supermarket sales. Features with higher importance values have a greater impact on the model's predictions.

1. **Item_MRP:** This feature has the highest importance, indicating that the Maximum Retail Price (Item_MRP) is a critical factor influencing sales predictions, reaffirming its pivotal role observed in Linear Regression analysis.
2. **Outlet_Type_Supermarket Type3:** This feature also has high importance, suggesting that the 'Supermarket Type3' outlets play a crucial role in sales predictions, likely due to their distinct operational characteristics leading to higher sales.
3. **Outlet_Identifier_OUT027:** The importance of this feature implies that the outlet identified as 'OUT027' has unique attributes or operational strategies contributing significantly to sales predictions.


## Note
For detailed insights and accurate interpretations, please refer to the actual results and outputs in the [Project 1 Revisited Notebook](Project_1_Revisited.ipynb).

### Additional Details
- Linear Regression Coefficients Plot: ![Linear Regression Plot](https://github.com/coryncates/Prediction-of-Product-Sales/blob/main/Lin.png?raw=true)
- Random Forest Feature Importances Plot: ![Random Forest Importances Plot](https://github.com/coryncates/Prediction-of-Product-Sales/blob/main/Reg.png?raw=true)




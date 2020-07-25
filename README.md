# King-County-House-Price-Analysis

#### Introduction
This is the second capstone project for Springboard's Data Analysis Career Track Certification.

This dataset contains house sale prices for King County, which includes Seattle, and homes sold between May 2014 and May 2015. https://www.kaggle.com/harlfoxem/housesalesprediction

#### Objective
Management from a real estate agency has asked the analytics team to initiate further research on the current housing market, looking into features such as housing prices, geographic location, grade and condition ratings, and property age. Additionally, a customer has recently put their waterfront property on the market. Management has asked the analytics team to predict the price of this property based on previous housing data. 

#### Tools Used
The data was cleaned through Excel and Python. Further exploratory and predictive analysis was created through Python and Tableau. 


#### Key Findings

1.  **66%** of predictions can be made through this statistical model, with **R^2 (coefficient of determination) regression score of 0.66**
2. The multivarient regression equation was applied to predict the future price of a house, located in Lake Forest Park, WA. The house price was predicted to be **2,028,860**

##### Conclusion

1.  This model was a fairly good prediction. However, a more accurate model would have been possible with more data and higher correlated attributes.
2.  Attributes such as number of garages, waterfront size (water_depth and water_width), and bike trail access, are consideration factors when pricing a waterfront house but were not available for this model. More data on the waterfront property would improve the price prediction of waterfront houses. 
3.  Next time, I will split the test into two separate regression equation by classifying houses into waterfront (Yes/No) and compare the accuracies of each model. More attributes for each classified group would be required to generate an high quality prediction. 

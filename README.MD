### Problem Statement:

### Real Estate Firm located in Ames, IA wants to know what are the most important factors that are affecting the housing saleprice in Ames, that should help them in budget estimations for their future real estate projects

#### [Data Dictionary](https://www.kaggle.com/competitions/project-2-regression-challenge-123/data)

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**overall_qual**|*integer*|Ames,IA Houseprices|The Overall material and finish quality ranges from 1to 10.| 
|**gr_liv_area**|*float*|Ames,IA Houseprices|Above Ground living area in Square Feet |
|**garage_area**|*float*|Ames,IA Houseprices|Size of the Garage in Square Feet|
|**1st_flr_sf**|*float'*|AMes,IA Houseprices|First Floor Square Feet|
|**neighborhood**|*category*|Ames,IA Houseprices|Physical locations within Ames City Limits|
|**ms_zoning**|*category*|Ames,IA Houseprices|Identifies the general zoning classification of the sale|
|**exter_qual**|*category*|Ames,IA Houseprices|Exterior Material Quality|
|**kitchen_qual**|*category*|Ames,IA Houseprices|Kitchen Quality|
|**garage_type**|*category*|Ames,IA Houseprices|Builtin Garage or Attached or Detached Garage|
|**saleprice**|*float*|Ames,IA Houseprices|The property's Saleprice in Dollars|


#### Imported Dataset and performed data cleaning, missing value imputations and outlier checks
#### Data contains about 81 columns and 2051 rows
#### Checked correlation wiith heatmaps
#### Performed Linear Regression using four numerical variables that are highly correlated and achieved an rsquared score of 73 on train and 77 on test data
#### Compared model with the baseline model
#### Performed dummy encoding using onehot encoder and pipelines
#### Introduced categorical variables into the model and removed one numeric variable
#### Tried and tested various models using column transformers and pipelines 
#### Generated MSE, RMSE and MAE
#### Checked interactions between numeric varaiables and scaled the variables
#### Finally achieved rsquared score of 83.9% using 9 variables out of 81 variables

**Baseline MSE: 5983691627.56332**
**Test MSE: 938053042.9447733**

==========

**Baseline RMSE: 77354.3252026887**
**Test RMSE: 30627.651606755182**

==========

**Baseline MAE: 58082.873996560935**
**Test MAE: 21629.8337939106**



### Conclusion:

#### The most important factors that are determining the saleprice in Ames, IA are Overall quality of the house, Ground Living area, Garage area, Kitchen Quality, which are explaining about 78% varaiability in saleprice, other factors like Kitchen Quality, Neighborhood, External Quality, MS Zoning that is zoning classification are also important for people purchasing a house in Ames. For instance if the house falls under Floating village residential zoning the average sale price is about 200,000USD and the neighborhood Stonebrook looks to be in high demand and neighborhoods like Meadow village and Briardale have an average saleprice of 100,000 USD.

### Next steps 

#### There may be other factors influencing house prices like interest rates, Government subsidies and inflation. We may need to include these factors as well for accurate predictions as real estate prices have high association with interest rates along with the factors that were mentioned in conclusion

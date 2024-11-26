# Bike-Sharing-Casestudy

# BoomBikes Bike Sharing Assignment

[](https://github.com/bramhanayaghea/Bike-Sharing-Casestudy/blob/main/README.md#Bike-Sharing-Casestudy)

## **Problem Statement**

[](https://github.com/bramhanayaghea/Bike-Sharing-Casestudy/blob/main/README.md#problem-statement)

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein
 the user enters the payment information, and the system unlocks it. 


This bike can then be returned to another dock belonging to the same 
system. A US bike-sharing provider **BoomBikes** has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up 
with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes 
among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which
 the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

**Business Goal**:

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Table of Contents

[](https://github.com/bramhanayaghea/Bike-Sharing-Casestudy/blob/main/README.md#table-of-contents)

- [General Info](https://github.com/bramhanayaghea/Bike-Sharing-Casestudy/blob/main/README.md#general-information)
- [Technologies Used](https://github.com/bramhanayaghea/Bike-Sharing-Casestudy/blob/main/README.md#technologies-used)
- [Conclusions](https://github.com/bramhanayaghea/Bike-Sharing-Casestudy/blob/main/README.md#conclusions)
- [Recommendations](https://github.com/bramhanayaghea/Bike-Sharing-Casestudy/blob/main/README.md#recommendations)
- [Acknowledgements](https://github.com/bramhanayaghea/Bike-Sharing-Casestudy/blob/main/README.md#acknowledgements)

## General Information

[](https://github.com/bramhanayaghea/Bike-Sharing-Casestudy/blob/main/README.md#general-information)

**Issues to Address:**

1. **Revenue Decline:** BoomBikes faces substantial revenue declines due to the ongoing pandemic, necessitating a strategic solution.
2. **Market Sustainability:** The company struggles to sustain itself in the current market scenario, demanding a mindful business plan.
3. **Post-Lockdown Strategy:** BoomBikes aims to accelerate revenue post-lockdown, requiring an understanding of post-quarantine bike demand.

**Objectives:** The objectives include predicting significant variables influencing 
American market shared bike demand, determining the crucial predictors, 
developing a model to understand demand variations, facilitating 
adaptive business strategies, and exploring demand dynamics for 
effective decision-making. This case study aims to achieve this goal by 
building a multivariate linear regression model using the provided [dataset](https://github.com/akashkriplani/bike-sharing-assigment/blob/main/day.csv).

The primary objective is to identify the key variables 
that significantly influence the prediction of shared bike demand and 
assess how effectively these variables describe the patterns in bike 
demands.

## Conclusions

[](https://github.com/bramhanayaghea/Bike-Sharing-Casestudy/blob/main/README.md#conclusions)

**The equation of the best fit line is given by:**

****cnt = 2589.97 + 2020.62 x yr + 3520.22 x temp - 
1247.89 x windspeed - 1254.90 x season_spring + 658.27 x season_winter -
 2414.30 x weathersit_light_snow_rain - 624.95 x mnth_dec - 541.96 x 
mnth_jul - 705.06 x mnth_nov - 595.20 x holiday - 638.64 x 
weathersit_mist****

1) The close alignment of R² values between training (0.8211) and 
   test (0.8296) sets with a small difference of 0.0085 indicates excellent
   generalization and no overfitting. The adjusted R² of 0.8176 confirms 
   the model's accuracy

2) Bike demand is primarily influenced by:
   
   Positive factors: temperature, yearly trend, winter season
   
   Negative factors: adverse weather conditions, windspeed, specific months (November, December, July)
   
   3. Key Features Impact:
   - Temperature (3520.22): Strongest positive influence
   
   - Year (2020.62): Shows significant growth trend
   
   - Weather conditions (-2414.30): Major negative impact during adverse conditions
   4) The RMSE values (Training: 826.32, Testing: 763.76) and MAE values (Training: 617.31, Testing: 614.12) indicate consistent model performance across both datasets.
   
   

## Recommendations

[](https://github.com/bramhanayaghea/Bike-Sharing-Casestudy/blob/main/README.md#recommendations)

- 1. Temperature-Based Strategy: Maximize operations during optimal temperature conditions
  
  2. Weather Planning: Develop contingency plans for adverse weather conditions
  
  3. Seasonal market Demand Captialization:
  - Capitalize on winter popularity
  
  - Address spring season challenges
  4. Growth Planning: Leverage strong yearly growth trend for expansion
  
  5. Operational Efficiency: Plan maintenance during predicted low-demand periods
  
  6. Marketing Strategy:
  - Weather-based promotions
  - Season-specific campaigns

## Technologies Used

[](https://github.com/bramhanayaghea/Bike-Sharing-Casestudy/blob/main/README.md#technologies-used)

- Python
- Matplotlib
- Numpy
- Pndas
- Seaborn
- Statsmodels
- Sikit-Learn

## Acknowledgements
[](https://github.com/bramhanayaghea/Bike-Sharing-Casestudy/blob/main/README.md#acknowledgements)
Dataset used

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

@article{
    year={2013},
    issn={2192-6352},
    journal={Progress in Artificial Intelligence},
    doi={10.1007/s13748-013-0040-3},
    title={Event labeling combining ensemble detectors and background knowledge},
    url={http://dx.doi.org/10.1007/s13748-013-0040-3},
    publisher={Springer Berlin Heidelberg},
    keywords={Event labeling; Event detection; Ensemble learning; Background knowledge},
    author={Fanaee-T, Hadi and Gama, Joao},
    pages={1-15}
}

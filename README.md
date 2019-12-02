## Prediction of Nitrogen Oxides level in Air Quality

There are many poisonus gases such as CO, NOx, titania, sulfur dioxide, nitrous oxides, methane etc in the polluted air which is harmful not to only humans but also animals and plan lives based on this refereces [Air Pollution Effects on health](https://www.mfe.govt.nz/air/specific-air-pollutants/nitrogen-dioxide).  

This project aims to predict the level of Nitrogen Oxides in Air. The data was acquired from the UCI Machine Learning Repository. You can find all the information about Dataset from here [Air Quality Dataset](http://archive.ics.uci.edu/ml/datasets/air+quality). It's hourly data.

Created a prediction model using linear regression with data cleaning, and exploratory data analysis with visualization.

**Data Cleaning**: There were some values -200 which means the machine didn't dictate for some reason. Thus, it was replaced with average values. There were very few missing values, remove it.

**Data Analysis**:
The below statements are from the EDA part in the jupyter notebook.
* Gases like CO, NOx, titania, and Benzene are increased in the air over time
* The frequency of Oxides in Nitrogen is increasing 
* During the day Nitrogen Oxides' level is high compared to night

# Bike Sharing Assignment
> A multiple linear regression model for the prediction of demand for shared bikes


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic
- You are required to model the demand for shared bikes with the available independent variable
- Bike Sharing dataset and Data dictionary are provided.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Effect of Categorical Variables on the Dependent Variable: ​
	The demand for bikes has increased from year to year. ​
	Non-holiday days have a higher demand for bikes compared to holidays. ​
	Among seasons, fall has the highest demand, and spring has the least demand for bikes. ​
	On rainy days and during hail storms, the demand for bikes is very low compared to cloudy or partially cloudy days.
- Importance of Using drop_first=True During Dummy Variable Creation: ​
	To represent a variable with n categories, only n-1 dummy variables are needed. ​ Dropping the first dummy variable avoids multicollinearity. 
- Correlation of Numerical Variables with the Target Variable: ​
	Temperature (temp) has the highest correlation with the target variable (cnt). 
- Validation of Linear Regression Assumptions: ​
	The model is validated by checking R-squared and Adjusted R-squared values, P-values of features, and Variance Inflation Factor (VIF). ​ Features with high P-values and high VIF are dropped iteratively to improve the model
- Top 3 Features Contributing to Bike Demand: ​
	The top 3 features are:
		Atemp (feels-like temperature) ​
		Year (yr) ​
		Winter (season)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- **Python Libraries**:
  - **pandas** - version 2.2.2: For data manipulation and analysis.
  - **numpy** - version 1.26.4: For numerical computations.
  - **matplotlib** - version 3.8.4: For creating visual plots and visualizations.
  - **seaborn** - version 0.13.2: For enhanced statistical data visualization.
  - **scikit-learn** - version 1.2.0: For machine learning and model evaluation, including tools like `train_test_split`.
  - **scikit-learn** - version 1.2.0: For machine learning and model evaluation (including r2_score).
  - **statsmodels** - version 0.13.2: For statistical modeling and analysis.


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Inspiration: The analysis was inspired by the need of A US bike-sharing provider BoomBikes aspiration to understand demand for shared bikes.
Data Source: The dataset was sourced from Upgrad.
References: This project was supported by insights from data science tutorials and industry-standard practices.


## Contact
Created by [NamrathaGrandhi](https://github.com/NamrathaGrandhi/bikesharing)
For questions or feedback, feel free to reach out!


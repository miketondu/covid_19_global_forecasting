# covid_19_global_forecasting
This project is a part of the Kaggle competition to predict the cumulative number of confirmed COVID19 cases in various locations across the world, as well as the number of resulting fatalities, for future dates.

The project consists of using the provided Kaggle dataset with fatalities and confirmed cases of COVID-19 for the month of April, then merging it a UN dataset sourced from the UN website in order to have more complete information on each country's total population. 

After performing EDA and Feature Engineering, an XGBoost Regressor is used to create a forecast of Confirmed Cases and Fatalities for the rest of the month.  

The notebook and prediction csv were submitted to the KAGGLE competition link below.


https://www.kaggle.com/c/covid19-global-forecasting-week-3/data

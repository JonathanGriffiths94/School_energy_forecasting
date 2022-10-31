# School_energy_forecasting

Energy forecasting of UK school using AI modelling. Feasibility study, part of FLEXISApp project to find baseline forecasting accuracy for site to be used as a potential use case for participation in flexible power contracts. 

The original dataset contained 3 years of data ranging from June 2016 to February 2021.  A time series analysis was performed on the dataset and the data was then trained with models using traditional, ML and DL forecasting techniques. 

Covariate data including weather forecast data, seasonal features as well as school closure information was added to the dataset to improve model performance.  

All models were trained using default hyper parameters with no hyper parameter tuning. 

The model performance was assessed using the RMSE error metric. The random forest regression model was found to be the best model.

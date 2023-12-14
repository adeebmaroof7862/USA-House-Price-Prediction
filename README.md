# USA-House-Price-Prediction
This project is based on USA House Price Prediction for last 20 years.
I took csv data file of "Demand" and "Supply" and merged them and stored them in "df3" dataframe for better understganding. "df3" condains numerical data having variables as,                                                                                                        
- DATE	                                                                            
- UNEM_RATE                                                                           
- MORTGAGE 	                                                                   
- GDPC1	                                                                               
- FORECLOSURES                                                                                        
- Permit_Number                                                                               
- construction                                                                 
- Homes_Sold	                                                                                            
- Housing_Starts
- HPI  ,
where HPI is dependent variable and other 9 are dependent variables.
I converted "DATE" variable's datatype to "DateTime" using "pandas" function and did necessary data cleaning.
I created many graphical representation for data visualization using "seaborn" and "matplotlib".
I assigned independent variables to "X" and dependent variable to"y" and then i split data into training and testing part as 70% and 30%  respectively using "scikit-learn".
For model building i used three of the regression models "Linear regression model","RandomForest Regressor model","GradientBoosting Regressor model" using "scikit-learn" library from which "GradientBoosting Regressor model" is giving highest accuracy score and hence it is considered as the best model.

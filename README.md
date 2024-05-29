### Household Power Consumption throughout a year

**Akhilesh Varigonda**

#### Executive summary
This is a data analysis for the household power consumption with the daily average usage of global power consumption over a time for two calander years from December 2006 to December 2008. Here there is a testing and train data split with a 50% test size and using Grid Search hyperparameter with values appropriate for Random Forest Regression in analysising this data. There is the comparision using Random Forest Regression and multiple regression with several independent variable to see the difference with actual and prediction. Then a pairplot with a graphes that compares all the hyperparemeters. It is also important to see the correlation with the other variables with global active power so their is a heatmap that shows the correlations, and this will be important for the next steps in the analysis report along with other in depth analysis.  

#### Rationale
Anyone should care because we need to know the way how the power is exactly used for electric, gas and oil companies to have a better picuture and understanding of how households consume electricity throughout a year and here they data shows two years so we can see if the second year follows the consistancy of the first year. 

#### Research Question
How the power consumption in households is used throughout the year along with what factors are contributed to that and how can we make sure this data is useful for energy companies?

#### Data Sources
This is the website link to kaggle that shows the household power consumption data and what the data is about. This data shows the power consumption between December 2006 and December 2008. This data was provided by Jonathan Ortiz. 
[Household Power consumption data](https://www.kaggle.com/datasets/imtkaggleteam/household-power-consumption)

#### Methodology
The methods I am using is the RandomForestRegression with multiple regression along with gridsearchCV to see the errors. This will show how the data tests and train, showing the actual and prediction of the usage of global active power. And since the data shows every minute of every day used daily average of the all the variables excluding time to make assessments on this. 

#### Results
The research found that with RandomForestRegression using mutliple independent variable the power consumption is used more in the beginning and ending of the calender which indicates that it is based on the season and the predicted values does factor that. 

#### Next steps
It is the investigate more with the accuraty, testing, and training this data does and show how it can be useful for energy conpanies to process global active power consumption for a household data. And also investigation the other components of the data to see how it factors with global active power consumption. This would be neccessary since we used multiple regression to figure out the prediction of the global active power consumption comparing with the actual power consumption. This is also useful to see other factors for the household power consumption throughtout the two years of the data. Also there will be more in depth analysis for the other vizualizations found in this analysis. 

#### Outline of project

- [Capstone Project](Capstone_project.ipynb)
- [Household Power Consumption csv file](household_power_consumption.csv)


##### Contact and Further Information# 
Phone Number: (510)-246-2350
Email: varigonda8@gmail.com 
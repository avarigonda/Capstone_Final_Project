# Household Power Consumption Capstone project

**Akhilesh Varigonda**

#### Executive summary
This is a data analysis for the household power consumption with the daily average usage of global power consumption over a time for two calander years from December 2006 to December 2008. Here there is a testing and train data split with a 50% test size and using Grid Search hyperparameter with values appropriate for Random Forest Regression in analysing this data. There is the comparision using Random Forest Regression and multiple regression with several independent variable to see the difference with actual and prediction. Then a pairplot with a graphes that compares all the hyperparemeters. Based on the correlation matrix heatmap global active power, global intensity and submetering 3 are the importance variables that were analysed. It showed that the household power consumption is used more during the winter and during the summer it is used the least.

#### Rationale
Anyone should care because we need to know the way how the power is exactly used for energy companies to have a better picuture and understanding of how households consume electricity throughout the two year and the seasonal impact it has for household consumption. It also important to understand how the predictions can be useful for energy companies to make household energy consumption sustainable.  

#### Research Question
How the power consumption in households is used throughout the year along with what factors are contributed to that and how can we make sure this data is useful for energy companies?

#### Data Sources
This is the website link to kaggle that shows the household power consumption data and what the data is about. This data shows the power consumption between December 2006 and December 2008. This data was provided by Jonathan Ortiz. 
[Household Power consumption data](https://www.kaggle.com/datasets/imtkaggleteam/household-power-consumption)

#### Methodology
The methods I am used is a correlation matrix and it shows global active power has a perfect correlation with global intensity and sub metering 3. And global intensity and sub metering 3 has a strong correlation. With also these three variables I used  the random forest regression with multiple regression along with random forest regression gridsearchCV to see the errors. This will show how the data tests and train, showing the actual and prediction of the usage of global active power. And since the data shows every minute of every day used daily average of the all the variables since it shows a better analysis throughout the two years. I also showed a histogram that compares both the actual and prediction just to see for each of those three variable at what point of every of those variables it is used the highest. I also used seasonal decomposition with a period of thrity throughout the two years to see how seasonal these variables are since the data of household power consumption is based on seasonal usage. 

#### Findings
I did a matrix correlation heatmap and looked at a combinations that have strong correlations and they are global active power, global intensity and sub metering 3. These are all small errors when it is compared with actual and prediction. When looking at the relative imporatance it shows global intensity and sub metering as the highest relative importance which  has a strong correlation, so it shows relavence regarding the seasonal impact with global active power. That is also why I did a season decompositon for global active power, global intestity and sub metering 3 with additive with a period of 30 they all show they are seasonal. The graphs did show that the household power was consumed the highest during the winter and the least during the summer, which does show how energy is consumed throughout the year. 

#### Reccomendations to Energy Companies 
The energy companies can use prediction and the correlation of the global intensity and sub metering 3 the see how throughout the season the global active power is consumed, and take measures from this data that would be useful to find ways to make the usage of energy more sustainable and make energy cost effective for the household based on the seasons. In order the  encourage energy sustanablity make the energy costs high in the summer and low during the winter, since it would be more helpful and effective both for the energy companies and they way households consume their power daily based on the seasons throughout the year. 

#### Outline of project

- [Capstone Project](Capstone_Final_Project.ipynb)
- [Household Power Consumption csv file](household_power_consumption.csv)


##### Contact and Further Information# 
Phone Number: (510)-246-2350
Email: varigonda8@gmail.com 

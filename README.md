# Household Power Consumption Capstone project

**Akhilesh Varigonda**

#### Executive summary
This is a data analysis for household power consumption with the daily average usage of global power consumption over two calendar years from December 2006 to December 2008. Here, there is a testing and training data split with a 50% test size, and the Grid Search hyperparameter with values appropriate for Random Forest Regression is used to analyze this data. The comparison is made using random forest regression and multiple regression with several independent variables to see the difference between actual and prediction. Then, a pair plot with a graph that compares all the hyperparameters. The critical variables analyzed are based on the correlation matrix heatmap, global active power, global intensity, and submetering 3. It showed that household power consumption is used more during the winter and during the summer it is used the least.

#### Rationale
Anyone should care because we need to know how energy companies exactly use power to have a better picture and understanding of how households consume electricity throughout the two years and the seasonal impact it has on household consumption. It is also important to understand how predictions can be useful for energy companies to make household energy consumption sustainable.  

#### Research Question
How is power consumed in households throughout the year, and what factors contribute to that? How can we make sure this data is useful for energy companies?

#### Data Sources
This is the website link to Kaggle, which shows the household power consumption data and what the data is about. This data shows the power consumption between December 2006 and December 2008. Jonathan Ortiz provided this data. 
[Household Power consumption data](https://www.kaggle.com/datasets/imtkaggleteam/household-power-consumption)

#### Methodology
I use a correlation matrix showing global active power perfectly correlates with global intensity and sub-metering 3. Worldwide intensity and sub-metering 3 have a strong correlation. With these three variables, I also used  the random forest regression with multiple regression along with random forest regression gridsearchCV to see the errors. This will show how the data tests and trains, showing the actual and prediction of the usage of global active power. The data shows every minute of every day using a daily average of all the variables since it shows a better analysis throughout the two years. I also showed a histogram that compares the actual and prediction to see at what point every one of those variables is used the highest for each of them. I also used seasonal decomposition with a period of thirty throughout the two years to see how seasonal these variables are since the data on household power consumption is based on seasonal usage. 

#### Findings
I did a matrix correlation heatmap and looked at combinations with strong correlations: global active power, global intensity, and sub-metering 3. These are all minor errors when it is compared with actual and prediction. The relative importance shows global intensity and sub-metering as the highest relative importance, which has a strong correlation, so it shows relevance regarding the seasonal impact with global active power. I also did a season decomposition for global active power, global intensity, and sub-metering 3 with additive with a period of 30. They all show they are seasonal. The graphs show that household power was consumed the most during the winter and the least during the summer, which shows how energy is consumed throughout the year. 

#### Recommendations to Energy Companies 
The energy companies can use prediction and the correlation of the global intensity and sub-metering 3 to see how throughout the season the global active power is consumed and take measures from this data that would be useful to find ways to make the usage of energy more sustainable and make energy cost-effective for the household based on the seasons. To encourage energy sustainability, make the energy costs high in the summer and low during the winter since it would be more helpful and practical both for the energy companies and the way households consume their power daily based on the seasons throughout the year. 

#### Outline of project

- [Capstone Project](Capstone_Final_Project.ipynb)
- [Household Power Consumption csv file](household_power_consumption.csv)


##### Contact and Further Information# 
Phone Number: (510)-246-2350
Email: varigonda8@gmail.com 

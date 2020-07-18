# rainfall_in_Bangladesh

This dataset was taken from https://www.kaggle.com/redikod/historical-rainfall-data-in-bangladesh?select=data_monthly_rainfall.csv

## Context
Rainfall is very crucial things for any types of agricultural task. Climate related data is important to analyse agricultural and crop seeding related field, where those data can be used to show the predict the rainfall in different season also for different types of crops.
Developed application can be found from http://ml.bigalogy.com/
Paper: http://dspace.uiu.ac.bd/handle/52243/178

## Abstract
Mankind have been attempting to predict the weather from prehistory. For good reason for knowing when to plant crops, when to build and when to prepare for drought and flood. In a nation such as Bangladesh being able to predict the weather, especially rainfall has never been so vitally important.
The proposed research work pursues to produce prediction model on rainfall using the machine learning algorithms. The base data for this work has been collected from Bangladesh Meteorological Department. It is mainly focused on the development of models for long term rainfall prediction of Bangladesh divisions and districts (Weather Stations). Rainfall prediction is very important for the Bangladesh economy and day to day life. Scarcity or heavy - both rainfall effects rural and urban life to a great extent with the changing pattern of the climate. Unusual rainfall and long lasting rainy season is a great factor to take account into. We want to see whether too much unusual behavior is taking place another pattern resulting new clamatorial description. As agriculture is dependent on rain and heavy rainfall caused flood frequently leading to great loss to crops, rainfall is a very complex phenomenon which is dependent on various atmospheric, oceanic and geographical parameters. The relationship between these parameters and rainfall is unstable. Beside this changing behavior of clamatorial facts making the existing meteorological forecasting less usable to the users.

Initially linear regression models were developed for monthly rainfall prediction of station and national level as per day month year. Here humidity, temperatures & wind parameters are used as predictors. The study is further extended by developing another popular regression analysis algorithm named Random Forest Regression. After then, few other classification algorithms have been used for model building, training and prediction. Those are Naive Bayes Classification, Decision Tree Classification (Entropy and Gini) and Random Forest Classification. In all model building and training predictor parameters were Station, Year, Month and Day. As the effect of rainfall affecting parameters is embedded in rainfall, rainfall was the label or dependent variable in these models. The developed and trained model is capable of predicting rainfall in advance for a month of a given year for a given area (for area we used here are the stations (weather parameters values are measured by Bangladesh Meteorological Department). The accuracy of rainfall estimation is above 65%. Accuracy percentage varies from algorithm to algorithm.
Two regression analysis and three classification analysis models has been developed for rainfall prediction of 33 Bangladeshi weather station. Apache Spark library has been used for machine library in Scala programming language. The main idea behind the use of classification and regression analysis is to see the comparative difference between types of algorithms prediction output and the predictability along with usability.
This thesis is a contribution to the effort of rainfall prediction within Bangladesh. It takes the strategy of applying machine learning models to historical weather data gathered in Bangladesh. As part of this work, a web-based software application was written using Apache Spark, Scala and HighCharts to demonstrate rainfall prediction using multiple machine learning models. Models are successively improved with the rainfall prediction accuracy.

## Content
The given data has weather station and year wise monthly rainfall data of Bangladesh.

Data is two format - 46 year (33 Weather Station) : From 1970 to 2016

- Daily Rainfall Data
- Monthly Rainfall Data
## Columns:
- Station (Weather Station, along with Station Index)
- Year
- Month
- Day [For daily data file]
Acknowledgements
This thesis is the result of one year of work during which I (Yousuf Zaman) have been accompanied and supported by many people. I hereby express deep gratitude and thanks to, Dr. Mohammad Nurul Huda, Professor, United International University, Dhaka, whose continuous motivation, guidance, suggestions, crucial help and kind attention, enabled me to execute this research.

### What did I do?
I worked with the monthly dataset and divided it into test and train section. I tried to to visually represent the data regionwise but it was similar to one another. This is a numerical problem so we can use regression analysis. I tried to use gaussian function as a non-linear regression model but it did not work out.

### What is to be done in future?
- Several mathematical method can be applied to implement non-linear regression analysis.
- After training the method, we can apply on test data.
- Accuracy of different methods can be found out after comparing them.


Thank you for your kind attention.

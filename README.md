# group3_project4

Sam Song
Katie Bienek
Rachel Novak
Garrett Bradley
Jessica Van Dame


Day 1
Form groups.
Outline project ideas.
Perform an initial data exploration.
Begin research of datasets.
Submit a project proposal for approval.
Data Exploration – Data Categories; beauty

Day 2 - June 1st 

Day 3 - June 5th

Day 4 - June 6th
	Develop a project with your team.

Day 5 - June 8th
	Develop project presentation

Day 6 - June 12th 
	Present projects to class


Final Project Requirements: Demystifying ML
Find a problem worth solving, analyzing, or visualizing.
 Air Quality Data 
https://www.kaggle.com/datasets/hasibalmuzdadid/global-air-pollution-dataset
Air pollution is a significant environmental concern that affects the health and well-being of people worldwide. By developing a model to predict air quality, we can contribute to efforts aimed at monitoring and mitigating pollution levels.

Use machine learning (ML) with the technologies we’ve learned.

You must use Scikit-learn and/or another machine learning library.


You must use at least two of the following: 

Python Pandas
Python Matplotlib
Tableau



Here's an outline of how we will approach this problem:

We are using a dataset that includes historical air quality data from epa.gov. We will be narrowing down our data from 2018 - 2022 in North America; United States, this will be completed by using Python Pandas, Python Matplotlib, SQL Database. We will clean and preprocess the collected data by removing outliers and handling missing values. We will also use StandardScaler for the features to prepare them for machine learning algorithms.

The features we will use from the dataset can impact air quality, such as weather conditions (temperature, humidity, wind speed), geographical location, time of day, or pollutant levels from previous time periods. We will use the random forests using – feature importance. We have the potential to group by country; or year. 20. Supervised Learning: Day 2: Activity 5


6. Visualization and analysis: Visualize the predicted air quality levels alongside the actual measurements to compare the model's performance. You can create time series plots, heatmaps, or spatial visualizations to showcase the predicted pollution levels and identify patterns or trends.


By working on air quality prediction, you can gain practical experience in handling environmental data, feature engineering, regression modeling, and data visualization. Additionally, your project can contribute to raising awareness about air pollution and supporting initiatives to improve air quality monitoring and management.





Background Information on Data Set

Country : Name of the country
City : Name of the city
AQI Value : Overall AQI value of the city
AQI Category : Overall AQI category of the city
CO AQI Value : AQI value of Carbon Monoxide of the city
CO AQI Category : AQI category of Carbon Monoxide of the city
Ozone AQI Value : AQI value of Ozone of the city
Ozone AQI Category : AQI category of Ozone of the city
NO2 AQI Value : AQI value of Nitrogen Dioxide of the city
NO2 AQI Category : AQI category of Nitrogen Dioxide of the city
PM2.5 AQI Value : AQI value of Particulate Matter with a diameter of 2.5 micrometers or less of the city
PM2.5 AQI Category : AQI category of Particulate Matter with a diameter of 2.5 micrometers or less of the city

Steps:
Selected a data set; tried to plug in the data, realized needed more info
went back to Kaggle for another set that would help us with actual predictions.


We loaded data, selected certain features from the correlation matrix, used based of corMax to optimize after remove NO2
defined features, defined target vectors. 


Split and trained the data, as well as scaled the data
Fit Random Forest Regression to our model
Made predictions using random forest ** add image


Evaluated the model with a confusion matrix; went back and added a correlation matrix
Resulted in accuracy of 99%
analyzed featured importance ** add image


Removed the least important feature, NO2; received the same accuracy! 
We went back and added data visualizations; box & whisker, scatter, decision tree

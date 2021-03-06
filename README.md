# Appliances-Energy-Prediction

Problem statement of the Appliances Energy Prediction is to predict the appliance energy consumption for a house based on factors like temperature, humidity and pressure. In order to achieve this, we need to develop a supervised machine learning model using regression algorithms.
     
To begin with we imported some of the required libraries for data analysis and visualization. We loaded the data and go over the basic features, shape and datatypes of various variables. We observed the data contains duplicate records and null values. By using Panda’s library, we handled duplicate records and null values. By using box plots we found some outliers and manipulated those outliers with python conditional statements. We added new parameters based on the existing ones, for ease of analysis.
    
We proceeded with exploratory data analysis, where we found some important observations like energy consumption in house is higher between 5 pm to 7 pm. Similarly, we observed that energy consumption is higher on Monday in every week. We found that energy consumption was higher on Sunday in month of January and in the remaining months it was higher on Monday.
    
We identified correlation between dependent and independent variables with the help of heat map. We split data into training and testing set before implementing model on it. We used linear regression algorithm to build our model and applied on training and testing data.
    
We evaluated our model and got the accuracy of 93.31%. From exploratory data analysis, we drew following conclusions: Energy consumption in house is higher between 5 pm to 7 pm. Similarly, we observed that energy consumption is higher on Monday in every week. We found that energy consumption was higher on Sunday in month of January and in the remaining months it was higher on Monday.

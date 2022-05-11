# Bike Sharing Assignment
In this assignment, i have built a multiple regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
1. A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

2. We want to understand the factors affecting the demand for these shared bikes in the market. The client wants to know:
    - Which variables are significant in predicting the demand for shared bikes.
    - How well those variables describe the bike demands

3. Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Top 3 features contributing significantly towards explaining the demand of the shared bikes are :
  1. Temperature - Temperature with coefficient 0.6064, this means that if temperature is increased by 1 unit keeping another variable constant the dependent variable is going to increase by 0.6064.
  2. Year with coefficient 0.2289, this means that if Year is increased by 1 unit keeping another variable constant the dependent variable is going to increase by 1.2289.
  3. light_snow with coefficient -0.1902, this means that if light_snow is increased by 1 unit keeping another variable constant the dependent variable is going to decrease by 0.1902.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas library
- numpy library
- matplotlib
- seaborn
- sklearn
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
I thank Upgrad for providing the data set and guiding me through the process by providing necessary resources.




<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

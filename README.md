# Bike Sharing Assignment
> Outline a brief description of your project.
To find Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands Based on various weather condition and people's styles.


## Table of Contents
* [General-info](#general-information)
* [Technilogies used](#technologies-used)
* [Conclusion](#conclusions)
* [Acknowledge](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands.

- What is the background of your project?
bike sharing company have planned to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits after covid-19.

- What is the business probem that your project is trying to solve?
The buisness problem is to invest and maintain inventory of bike based on climatic and other condition, so finding out the best predictor variable to optimize the investment.
- What is the dataset that is being used?
 The dataset is the data of Bike sharing company which has records of there bike given to customer on rental basis  date, season, weekday,working, weeather condition and temperature  

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
As per our final Model, the top 3 predictor variables that influences the bike booking are:
- 'atemp': A coefficient value of ‘0.5779’ indicated that a unit increase in atemp variable, increases the bike hire numbers by 0.5779 units.
- 'weathersit_lightrain': A coefficient value of ‘-0.3070’ indicated that, w.r.t weathersit_lightrain, a unit increase in weathersit_lightrain variable, decreases the bike hire numbers by 0.3070 units.
- 'yr': A coefficient value of ‘0.2342’ indicated that a unit increase in yr variable, increases the bike hire numbers by 0.2342 units. So, it's suggested to consider these variables utmost importance while planning, to achive maximum Bookings¶

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - warnings
- library - numpy
- library - pandas
- library - matplotlib
- library - seaborn
- library - statsmodels
- library - LinearRegression
- library - RFE
- library - VIF

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [Linear Regression](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

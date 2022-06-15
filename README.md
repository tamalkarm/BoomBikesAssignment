# BoomBikes Bike- Sharing
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
-  Project Description :
    The company wants to know:
    * Which variables are significant in predicting the demand for shared bikes.
    * How well those variables describe the bike demands
- Project Background : 
    * A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.. 
- What is the business probem that your project is trying to solve?
    * Create a model which will able to predict based on certain factors when the bike rental would be more
- What is the dataset that is being used?
    * Bike-rental data for time period 2018 to 2019

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Bike rental   
    * will increase with increase in value of temperature and year
        *  atemp having highest coefficent of 0.4546, which means if all other independent varaible kept constant, and increase in temperature by one unit the number of bike renatal will increase by 0.4546 units.
    * Will decrease with increase in number of holidays, fall, spring and mist & light rain
- In Terms of buisness prespective
    * There may be offers provided for -ve coofiecnet values like holidays falls, spring. which may result in customer growth
    * The bike renting increases over the year which means, it increase from 2018 to 2019. this may follow the trend once people are back on streets.
    * People also not preffering to take bike on rent during mist, and light rain, the company should provide rain gears in nominal prices so bike will be attaractive to rider

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Matplotlib - v3.4.3
- Numpy   - v1.20.3
- Seaborn - v0.11.2
- Pandas  - v1.3.4
- sklearn
- statsmodels
- Python  - v3.9.7
- Excel
- Jupyter Notebook - v6.4.5
- IPython - v7.29.0
- Vscode - v1.67.0
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
### Contributer.
    * Tamal Karmakar

#### This project is created as part of IIITB and MultipleLinear regression assignment 


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
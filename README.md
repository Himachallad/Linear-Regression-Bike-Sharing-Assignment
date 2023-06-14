# Linear Regression - Bike Sharing

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
We have to create a linear model that describe the effect of various features on the demand of the bikes. It is to understand:
1. Which variables are significant in predicting the demand for shared bikes.
2. How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- People prefer to rent bike when temperatures are high. In our dataset temperature was generally in range of
11-30 degrees.
- Snowing, cloudy and high wind-speeds have negative impact on the rentals.
- From above points we can say that people like to rent bike, in clear weather conditions. Bad weather is bad for
the business
- Fewer people rent bike in Spring.
- 2019 has shown a good growth in terms of more rentals in comparison to the previous year. This is good for business.
- From EDA we noticed that:
	- Mid-year booking during May, June, Jul, Aug, Sept, and Oct are high. It increase from the start of the year,
and start decreasing post October, till the end of the year.
	- Nobody rents a bike on a heavy rain day.
	- More people rent bike on a working day.
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


### Training and Testing dataset comparision

&nbsp;&nbsp;Train data R-squared:    &nbsp;                   0.835<br>
&nbsp;&nbsp;Test data R-squared:       &nbsp;                 0.805<br><br>
&nbsp;&nbsp;Train data Adj. R-squared:     &nbsp;             0.831<br>
&nbsp;&nbsp;Test data Adj. R-squared:    &nbsp;               0.794<br>

*Demand of bikes depend on year, temp, light snow, windspeed, Spring, Cloudy, winter, Jul, Sept, Jan and Sun.*


## Acknowledgements
Give credit here.
- Concepts taught during Linear regression sessions came in handy for this real-world case study

## Contact
Created by [@himachallad] - feel free to contact me!

## License
This project is open source.

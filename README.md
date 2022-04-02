# PyBer_Analysis

## Overview / Purpose:
   * The purpose of this project was to give V. Isualize a written analysis of Pyber ride-sharing data and demonstrate how ride-sharing data differs by city type. In order to accomplish this, Python, Pandas, and Matplotlib were used to create a summary DataFrame and a multiple-line graph that shows the total weekly fares for each city type. 

## Analysis/Results:
  * Pyber Summary Data Frame:
    * As depicted in the table below, ride-sharing data such as the total fares and average fare per ride and driver are directly impacted by the amount of available drivers in each city type (Rural, Urban, Suburban). More specifically, as the amount of available drivers declines, the average fares per ride and driver increases. For instance, due to the low amount of drivers in rural cities where the population is likely to be lower, riders are expected to pay a higher fare and probably have to travel further to get to their destination. Converseley in urban cities, the high availability of drivers and an assumed larger population make it easy for rideshare access which in turn saves riders' money and increases the amount of total rides. 
        ![Pyber_Summary_DataFrame](analysis/Pyber_Summary_DataFrame.png)
  * Multiple-line Graph (Total Weekly Fares vs City Type)
    * The multiple-line chart below compares the sum of fares per week by each city type beginning from January to late April 2019. As mentioned above, urban cities have the highest amount of available drivers and total rides (and most certainly higher population) which, in turn, increases the amount of fares accrued per week. Despite having higher fare costs in rural cities, the low amount of rides directly impacted the weekly fares that were accrued in these cities. See below.
        ![Pyber_Fare_Summary](analysis/PyBer_Fare_Summary.png)

## Summary / Business Recommendations:
   * After analyzing the Pyber rideshare data, it is clear there is a significant difference in ride totals and total fares between city types likely due to amount of available drivers and fare costs. Therefore, below are three business recommendations to mitigate the disparities. 
    * Start a recruiting campaign for drivers in Rural Cities: 
      * The demand for rideshare in rural cities obviously exists; however, the number of rides in these cities (125) outnumber the amount of drivers (78). Putting more drivers on the road will likely increase the weekly amount of fares for these areas. 
    * Increase advertisement for Pyber rideshare in urban cities:
      * Traffic in urban cities is detrimental for all trying to make it to work on time. By placing advertisements in crowded areas with high traffic, we can motivate individuals to participate in Pyber rideshare and attract more customers and drivers.
    * Provide rideshare incentives for employees:
      *  Implementing corporate employee rideshare incentives will motivate employees to utilize rideshare. This will inherently increase rideshare drivers while also provide free advertisement and potentially increase employee retention.

## Below is the Pyber Pandas code for your reference
   * [PyBer_Challenge_Code](PyBer_Challenge.ipynb)

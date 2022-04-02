# PyBer_Analysis

## Overview / Purpose:
   * The purpose of this project was to give V. Isualize a written analysis of Pyber ride-sharing data and demonstrate how ride-sharing data differs by city type. In order to accomplish this, Python, Pandas, and Matplotlib were used to create a summary DataFrame and a multiple-line graph that shows the total weekly fares for each city type. 

## Analysis/Results:
  * Pyber Summary Data Frame:
    * As depicted in the table below, ride-sharing data such as the total fares and average fare per ride and driver are directly impacted by the amount of available drivers in each city type (Rural, Urban, Suburban). More specifically, as the amount of available drivers declines, the average fares per ride and driver increases. For instance, due to the limited amount of available drivers in rural cities where the population is likely to be lower, riders are expected to pay a higher fare and probably have to travel further to get to their destination. Converseley in urban cities, the high availability of drivers and an assumed larger population make it easy for rideshare access which in turn saves riders' money and increases the amount of total rides. 
        ![Pyber_Summary_DataFrame](analysis/Pyber_Summary_DataFrame.png)
  * Multiple-line Graph (Total Weekly Fares vs City Type)
    * The multiple-line chart below compares the sum of fares per week by each city type beginning from January to late April 2019. As mentioned above, urban cities have the highest amount of available drivers and total rides (and most certainly higher population) which, in turn, increases the amount of fares accrued per week. Despite having higher fare costs in rural cities, the low amount of rides and limited availability of drivers directly impacted the weekly fares that were accrued in these cities. See below.
        ![Pyber_Fare_Summary](analysis/PyBer_Fare_Summary.png)

## Summary / Business Recommendations:
   * After analyzing the Pyber rideshare data, it is clear there is a significant difference in ride totals between city types due to amount of available drivers and fare costs. There is a statement summarizing three business recommendations to the CEO for addressing any disparities among the city types.
   * [PyBer_Challenge_Code](PyBer_Challenge.ipynb)

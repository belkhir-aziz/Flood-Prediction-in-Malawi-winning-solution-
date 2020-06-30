# Flood-Prediction-in-Malawi-winning-solution

## Overview
In recent decades, countries across Africa have experienced an increase in the frequency and severity of floods. Malawi is particularly vulnerable to flooding. In March 2019, Cyclone Idai impacted more than 922,900 people, with 56 deaths, 577 injuries, and more than 82,700 people were displaced. Food insecurity also rose sharply due to the destruction of crops in a country that is highly dependent on rainfed agriculture.

## Key point
The most important thing that we have made is by selecting the weeks within the flood period. Which also have a important precipitation amount. It may seem like including all the week's precipitation seems to be helpful but it's not. For example, the model learns that having a huge amount of precipitation in week X affects the percentage of the flood and vice versa then a localization where it hadn't been rainy for the week X, but what it will have in the next week will not be well predicted (sort of overfitting). The problem is very serious due to the difference between the train and the test. That is why we choose to use just weeks 7, 8, and 9.
 
 At next we add features that descrivbe if the amount of precip is increasing or decreasing during the disccused period and the week with maximum of precip.
 Then we evaluate the maximum of precipitation within two weeks.
 
 And finnaly we do some outlier detection using EllipticEnvelope.
 
 ## final data
 
![data](https://user-images.githubusercontent.com/54355576/86121922-2afa4080-bad7-11ea-9dfd-4d54c98ccc14.png)


 

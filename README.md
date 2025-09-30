# TornadoDamage
Exploring the relationship between the year a tornado occurred and the average property loss it caused.

We are using data collected and compiled by the National Weather Service from their Severe Weather and Tornadoes reports. Each row is a different tornado that took place in the United States from 1950 to 2023. For our analysis we will be focusing on data from 1950 to 2023 due to changes in how the data was recorded

We will be focusing on the yr and loss variables.

    The yr variable is the year when the tornado took place (1950-1995)
    The loss variable represents the estimated property loss in dollars from the tornado. A higher value indicates more loss and we will be using this as our indicator for how severe a tornado is.

The representation of the loss variable changes throughout the dataset. From 1950 - 1995, the variable is represented by a categorization of tornado damage with each category being an order of magnitude larger than the previous. Starting in 1996, they instead recorded the variable in millions of dollars and in 2016 switched to whole dollar amounts. In order to keep the larger part of our data, we are focusing on 1950 - 1995 since there is not an accurate way to switch the values from categories to dollar amounts. This will also help reduce the affect inflation has on our analysis.

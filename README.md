# Illinois Sales Tax Calculator
The price of goods and services changes base on where you purchase it.  The cost of living is artificial/relative. Your goal is to create a little calculator widget that will compute the total cost depending on where you buy your good/service and the amount of course.

This [tax link](https://www.taxjar.com/states/illinois-sales-tax-online/#do-you-have-sales-tax-nexus-in-illinois) has the information on various cities shipping tax rates.  Here is a short list of useful statistics from the website.
-  Illinois Tax Rate: 6.25%
-  Minimum Shipping Rate: 7.50%
-  Maximum Shipping Rate: 10.25%

## Total cost
It should be noted that the total cost of the item is found by taking the price of the item and multiplying by the sales tax.  If there is shipping, which we will assume happens in all cases, then you need to add the cost of shipping and handling multiplied by the shipping tax from its location.

## Shipping
Your shipping should be a function of two variables: the type and the location.  You should use the radio input type for the type of shipping variable and a text input for location.
-  type of shipping: standard = $2.99; priority = $4.99; express = $8.99
-  location: choose the name of the city.
## Your Program Goals
-  Make sure your widget has the correct number of input and types of input fields to grab the necessary data.
-  In the javascript, use query selectors to store the information in variables
-  Do some math with the variables to calculate the total cost
-  display the answer to your selection in the span element.

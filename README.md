# 2017 & 2018 stock-analysis

## Overview
### Investing in stocks can be risky if one does not possess wide background on the specific market in which the assets considered for investing work. Eventhough, it's possible to choose certain criteria that give an overview of how specific assets perform, giving our decissions higher chances of success (getting high returns from our investment).

### The present file has exactly this objective, to provide information that, at a glance, can help potential investors how some assets behaived during 2017 and 2018. As an attempt to make it easier to understand the information displayed we used a color code that can be understood worldwide.


## Method

### We are given daily information for 12 stocks, having these variables to pay special attention to:
### * Ticker
### * Daily Volume
### * Close
### Thus, we create the following variables:

### ![Variables](https://user-images.githubusercontent.com/89816213/135195133-75859c97-21dd-43bd-888f-22be1829922a.PNG)

### Using these variables we can loop through the data using the right conditions. First, to define the ticker, by making sure it has the same value as the ticker specified by our needs; then we have to add the volume of the daily opperation to the total volume of the specific ticker that is being examined, and, finally, we need to find if the Close price is the starting or ending price, which we can find out by determining if the previous or the next row have the same ticker. 

### ![Conditions](https://user-images.githubusercontent.com/89816213/135195244-295fc963-ac6c-404e-9d8a-386094b1ead3.PNG)

### Finally, we have to determine the location where we want to display our results, which is done through the following code:

### ![display](https://user-images.githubusercontent.com/89816213/135195957-ce39c2b0-865e-4b60-94d4-59d06cba84d0.PNG)


## Results:

### ![2017](https://user-images.githubusercontent.com/89816213/135199364-14bb400f-97a5-4997-9b21-d67eae825961.PNG)
![2018](https://user-images.githubusercontent.com/89816213/135199365-1113f2b9-32ec-474b-9a0c-bd3ba1caf704.PNG)


### Before 
Summary: in a summary statement address the following questions: 1) what are the advantages or disadvantages of refactoring code? 2) How do the pros and cons apply to refactoring the original VBA Script 

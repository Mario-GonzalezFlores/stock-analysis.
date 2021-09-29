# 2017 & 2018 stock-analysis

## Overview
Investing in stocks can be risky if one does not possess wide background on the specific market in which the assets considered for investing work. Eventhough, it's possible to choose certain criteria that give an overview of how specific assets perform, giving our decissions higher chances of success (getting high returns from our investment).

The present file has exactly this objective, to provide information that, at a glance, can help potential investors how some assets behaived during 2017 and 2018. As an attempt to make it easier to understand the information displayed we used a color code that can be understood worldwide.


## Method

We are given daily information for 12 stocks, having these variables to pay special attention to:
* Ticker
* Daily Volume
* Close
Thus, we create the following variables:

![Variables](https://user-images.githubusercontent.com/89816213/135195133-75859c97-21dd-43bd-888f-22be1829922a.PNG)

Using these variables we can loop through the data using the right conditions. First, to define the ticker, by making sure it has the same value as the ticker specified by our needs; then we have to add the volume of the daily opperation to the total volume of the specific ticker that is being examined, and, finally, we need to find if the Close price is the starting or ending price, which we can find out by determining if the previous or the next row have the same ticker. 

![Conditions](https://user-images.githubusercontent.com/89816213/135195244-295fc963-ac6c-404e-9d8a-386094b1ead3.PNG)

Finally, we have to determine the location where we want to display our results, which is done through the following code:

![display](https://user-images.githubusercontent.com/89816213/135195957-ce39c2b0-865e-4b60-94d4-59d06cba84d0.PNG)


## Results:

![2017](https://user-images.githubusercontent.com/89816213/135199364-14bb400f-97a5-4997-9b21-d67eae825961.PNG)
![2018](https://user-images.githubusercontent.com/89816213/135199365-1113f2b9-32ec-474b-9a0c-bd3ba1caf704.PNG)

Given the results in the previous images, we can notice that in 2018 most stocks performed negatively, in opposite to 2017. This can lead us to think that it might be a risky moment to invest, since most stocks are loosing value (asuming we are using this analysis for 2019); but, if we pay close attention, most stocks are not loosing value when compared versus the starting point of 2017, since rises during 2017 were much higher than the losses seen in 2018. 

Now, it's not necessarily true that stocks are better possitioned now than they were at the begining of 2017, some have lost more than or nearly half their value over 2018, meaning that if they had won 100% during 2017, that proffit has already been lost.

We can also assuma that, given a higher volume of operations during 2018, it may be normal for stocks to adjust their price, and actually this can be very helpful for them to make some wins, since more traded stocks usually are more attractive to investors.

Lastly, considering that most stocks have lost value during the previous year, it could be advisable to invest in the ones that lost the least (less than 21%), fo they have not shown abrupt volatilty and may be now at disscount, having more chances to grow their value in the midterm.

## Summary 

### Refactoring 

Refactoring has as an advantage that we can change or remove instructions that are either too repetitive or innecesary, which allows our code to run more smoothly. One other advantage is that we can add or change the outputs, as in this case, where we changed the code so that it changes the format according to the results. 

Although it may be a good idea to refactor some codes, when working with an stablished code given by someone else it can be tricky understanding what was going through their mind, and small changes can cause a big tangle in the coding, so it may be more slow than just starting a new code.


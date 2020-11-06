# Project-1
First Project of Udacity's Data Science Nanodegree Program

## Motivation:

We will use the Seattle dataset available in https://www.kaggle.com/airbnb/seattle/data to understand the airbnb maket in that area answering three questions:<br>
<br>
1 - When is the most expensive season to rent a place in Seattle? Are the prices going up in general?<br>
2 - What are the characteristics of the room available in Seattle? <br>
3 - Can we predict the pricing oh the accommodation based on parameters that the user can input before looking at each listing?<br>

## Python packages used:

This project can be executed using the Anaconda distribution of Python 3.x and doesn't need any additional packages.

## Files contained in repository:
Readme.md <br>
project-1.ipynb<br>
calendar.csv - daily data on availability and pricing from kaggle (see link above)<br>
listings.csv - listing characteristics from kaggle (see link above)<br>

## Results
We have gained much more understanding of the Seattle market in 2016.
July to September are the most expensive months to rent a place. The prices peak considerably, going from 120 USD reaching more than 150 USD.
There is an upward trend in prices comparing the beginning of the year of 2017 and the begining of 2016. The prices gone up 12.5% comparing those periods.
As for the type os listing we saw that entire home/apt is much more common than the other modalities (private/shared room) and they are in mainly in Apartments or Houses.
Downtown and the southside of Seatle are the most expensive areas to rent. The north side is cheaper as so other far from downtown areas.
We have also build a model to predict pricing based on what a person would be looking for in a room. This model predicted the price with an R squared of 0.6 — witch is not so great, but is coherent with the few parameters used on this research.

More infomration can be found on my medium blog post avaliable in:
https://brunodovaljorge.medium.com/can-you-build-a-model-to-help-you-choose-an-airbnb-room-in-seattle-f70af9bd03cd

## Acknowledgment
I want to thank Udacity for the opportunity to work on such interesting project.

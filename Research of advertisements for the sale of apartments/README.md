Study of ads for the sale of apartments

At your disposal is the data of the Yandex.Realty service - an archive of ads for the sale of apartments in St. 
Petersburg and neighboring settlements for several years. You need to learn how to determine the market value of real estate. 
Your job is to set the parameters. This will allow to build an automated system: it will track anomalies and fraudulent activity.

Two types of data are available for each apartment for sale. 
The first ones are entered by the user, the second ones are obtained automatically on the basis of cartographic data. 
For example, the distance to the center, airport, nearest park and reservoir.

The purpose of the study is to study the cost of housing depending on various factors:

- total area, living area and kitchen area, number of rooms, floors, etc.
- day, month and year of the announcement
- cartographic location of the property

Research progress:

- get data from csv file
- we will pre-process the data, remove explicit and implicit duplicates, remove or change suspicious and frankly strange data
- we will conduct research on the dependence of the cost of housing on various factors

General conclusion

During the processing of the data array, missing values were removed or changed, and strong lunges were removed or changed. 
The following parameters were studied and described: total area, living area, kitchen area, object price, number of rooms, ceiling height, apartment floor; 
floor type of the apartment (“first”, “last”, “other”); the total number of floors in the house, the distance to the city center in meters, 
the distance to the nearest airport, the distance to the nearest park, the day and month the announcement was published. 
It was studied how quickly the apartments were sold, 
while it was hypothesized that the time of sale of an apartment equal to 0 most likely means that the apartment was withdrawn from sale immediately 
after being put up for one reason or another. Therefore, further studies on the timing of the sale were carried out without such apartments. 
It turned out that 75% of apartments are sold in 238 days. 
Further, it was revealed that the total area of the apartment has the greatest influence on the cost of an apartment, 
the living area and kitchen area, as well as the type of floor, have a slightly less influence. 
The day and month of the ad placement do not particularly affect the cost, but the year already has a stronger effect, 
since the housing market as a whole has a strong influence. The highest cost of apartments was in 2014, then it began to decline. 
Most likely this is due to the increase in the number of new buildings. More offers on the market - less price of one offer. 
It was concluded that from 2014 to 2018 the area of apartments for sale fell sharply, and with it, at first, the price also fell, 
but after 2016 the price per 1 m2 began to grow, despite the fact that the area of apartments for sale did not increase, 
hence and an increase in the total cost of apartments, since the cost of an apartment is equal to the product of the cost of 1 m2 
and the number of m2 in the apartment. In addition, it was revealed that out of 10 cities in which there are the most advertisements for the sale of apartments, 
the most expensive apartments are in St. Petersburg (average price - 114.2 thousand rubles per square meter of housing), 
and the cheapest - in Vsevolozhsk ( 65.7 thousand per square meter). 
And at the very end, a study was conducted of the dependence of the fall in the average cost of housing with a distance 
from the center of St. Petersburg for each km. Up to the first 10 km, the cost drops rapidly, 
most likely there are the most beautiful houses with the highest ceilings, and then the fall becomes not so fast. 
But at the end, after the 25th km, a jump is also visible, apparently due to the fact that at a distance of more than 25 km 
from the center of St. Petersburg there are many new tracks, the price of which is obviously higher than in the secondary.

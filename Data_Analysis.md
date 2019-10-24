#Data Analytical Observations - Python API Challenge

First, in terms of the plot regarding cloudiness in relation to latitude, while its easy to make assumptions, we need to consider that the data does not contain every city in the world.
We're simply picking up a random sample size. With this in mind, first off we can see that if a city is at the equator (lat 0), this does not mean less clouds.
In fact, there are other latitudes that have no 100% cloudiness both north and south of the equator. If i was a data analyst for a metorologist, I'd bring this data to them to see if they can provide any plausible theory that causes this phenomenon.

Second, the plot for latitude vs. humidity has a much more obvious trend. For cities across the equator, the sprawl or distance between points are far more spread out vs away from the equator.
What is more curious is that the latitude range between 40 to 80 feature an extreme concentration of cities that have very high amounts of humidity.

Lastly, the graph for max temperature has an even obvious trend than the first two scatter plots. Multiple observations can be made that are plausible:
cities closer to the equator have a higher max temperature,
cities farther away from the equator have a lower max temperature vs. cities near the equator,
and cities north of the equator seem to have overall less temperatures which may equate to how landmass of earth is typically more north biased.

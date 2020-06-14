# bikesharing3

# NYC Citi Bike Analysis

This is a summary of the analysis we did supporting a Citi Bike franchise is Des Moines.

## Hypothesis

We established a visual case that although New York City and Des Moines are very different there are several advantages Des Moines has that suggest a Citi Bike franchise would succeed.  The population of New York City is 8,300,000 and the population of Des Moines is 210,000.  It helps to keep the perspective that Des Moines is roughly one fourtieth the size of NYC.

### Questions

The questions we attempt to answer are:
What demographic details suggest that, given it's 1/40th scale, Des Moines can sustain a bike rental business?
Are there any clues in the data that lead us to conclude that Des Moines is at a disadvantage or at an advantage compared to NYC.

### Assumptuions

We are assuming that the NYC Citi Bike model is a profitable going concern.
We are assuming that there is no significant impact related to varations in weather between NYC and Des Moines.  Both cities have roughly the same weather at the same time of year.
The NYC usage data contained some suspect data centered around users with a stated year of birth in 1969.  We removed this data.  Additionaly some birth years were reported for the 1800s.  To be as accurate as possible we removed all data points with a birth year before 1940.

### Analysis

An additional assumption was made that bike commuting is becoming increasingly popular (up 62% since 2000 per bikeleague.org).  While we do not expect bike rentals to be used for commuting in any significant manner, the increased popularity of bike communting should likely be seen as a positive impact on bike rentals in that it serves as a ubiquitous advertisment for cycling.  The average commute time in NYC is 41 minutes, while it is 19 minutes in Des Moines.  As we'll see, how people commute is very different in Des Moines compared to New York City.

We took a deep dive into comparing public transportation options in both cities.  NYC has light rail, subways, busses, and ferries.  Combined, all public transportation options amounted a volume equal to 27% of the city's population each day of the year on average.  Des Moines only has a bussing system, whose average daily ridership represents less than 2% of the city's population.  Citations: Metroplotian Transit Authority, Annual Subway Ridership (2016), and Des Moines Area Reagional Transit Authority (RIDEDART.com)

We then took a look at population density.  New York City is the most densely populated city in the country.  Des Moines ranks 109th, however, it's density is in line with similar cities such as Cincinnati, Lincoln, Omaha, and Sioux Falls.

After analyzing the Citi Bike NYC data we saw that 90% of ridership fell in the 18 to 65 year old demographic.  This is the logical target demographic for this business.  Compared to NYC Des Moines has roughly the same proportions not fitting into the target age demographic (35% vs. 36.2%), however the Des Moines demogrphic skews younger, which is the more favorable of options.  The growth rate of Des Moines is almost 2.5 times that of NYC (4.9% vs. 2.0%).

Analysis of the Citi Bike NYC data showed that 19% of Citi Bike customers were not subscribers. Understanding that many of these non-subscribing renters are apt to be tourists we examined the tourism data for Des Moines.  Few American cities can compare to the volume of tourism that New York City enjoys, but the data showed that Des Moines had a respectable amount of tourists visit each year.  We discovered that Des Moines gets much more tourism than one might expect.  The Greater Des Moines Convention and Visitors Bureau estimates that Des Moines had 13.7 million tourists vistied the city in 2016 (https://www.catchdesmoines.com/articles/post/des-moines-draws-record-number-of-visitors-to-region). Per the source https://www.baruch.cuny.edu/nycdata/tourism/index.htm New York City saw a record 65.1 million tourists visit in 2018.  

Lastly, we wanted to single out college age renters because we were concerned that the fat tail in the NYC renter by age graph was indicative of a large college age population in New York City.  What we discovered, however, is that Des Moines actually has more college student than NYC on a per capita basis.

## Conclusion

It is our conclusion that a Citi Bike franchise in Des Moines can be as successful as the New York City franchise, if not more so.  We determined that the age demographic for Des Moines skews slightly younger and has more college students per capita than NYC.  We see the lack of any substantial public transit system as a key growth opportunity, and disproved our preconceived assumption that Des Moines lacked adequate tourism traffic.  Additionally, the popluation density of 210,000 people in 81 square miles, while not coming close to New York's density, is comparable with other Great Plains and Midwestern cities, and should not be viewed as a deterrent.  

### Citations

CitiBikeNYC.com
IowaBikeRoutes.com
https://www.governing.com/gov-data/population-density-land-area-cities-map
catchdesmoines.com
bikeleague.org

Tableau Public link: https://public.tableau.com/profile/paul.isenberg#!/vizhome/Challenge_15921229041440/ChallengeStory?publish=yes

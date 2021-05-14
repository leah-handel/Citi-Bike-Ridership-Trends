# Recreation is The New Rush Hour

This dashboard explores what rush hour looks like during the covid-19 pandemic. It (and the reverse geocoding behind the analysis below, described in the data cleaning notebook) was inspired by a similar project by Clif Kranish earlier this year on [Towards Data Science](https://towardsdatascience.com/reverse-geocoding-with-nyc-bike-share-data-cdef427987f8). However, Clif only looked at data from September 2020, when most New Yorkers were working from home and schools were shut down, to draw conclusions about citi bike ridership in general. I wanted to use his techniques to investigate how this pattern of ridership fits evolution of New Yorkers' work and school lives and represents a new direction, rather than a fixed truth, for citibike.

The initial line chart compares how many rides were taken in each hour of the day on weekdays in April 2019, 2020, and 2021. The maps below show the 20 most popular trips during the afternoon/evening peak usage for April 2019 (representing the pre-covid status quo) and April 2021. Rides of less than 3 minutes have been filtered out to account for riders re-docking bikes accidentally or because they changed their mind about riding, to prevent these from inflating the number of trips where bikes returned to the same station.

>As New Yorkers venture outside again, they're leaving the bike commute behind and instead using citi bikes for covid-safe outdoor recreation. April 2019 ridership showed two weekday peaks at rush hour and favored trips from midtown/downtown to other parts of the city. In April 2021, ridership peaks in the evening and favors loops that return to the same station or nearby, clustered around Central Park, Prospect Park, and Roosevelt Island.


# Uneven Recovery in Ridership

This dashboard explores the regrowth of overall ridership as covid restrictions loosen in the New York metro area. The initial line chart shows total ridership per borough and Jersey City in April 2019, 2020, and 2021. 

The bar chart shows the percent change in ridership between the 2019 pre-covid status quo and April 2021. The Bronx is not included because there were no stations in 2019.

The map shows the same percent change, calculated by zip code. Again, zip codes with no stations in 2019 are not shown.

>While New Yorkers have in general returned to pre-pandemic levels of citibike use, some areas still lag behind their 2019 ridership. Jersey City and downtown Manhattan are low, most likely due to the shift away from commuting via citibike. Citibike could capitalize on this trend and their existing infrastructure in these areas by marketing citibike as a covid safe activity to do in Washington Square Park, to and from the High Line, etc.

Citibike is actually advertising bike routes in parks in this area! Although it's not exactly accurate to imply that they're the most popular!

<img width="878" alt="Screenshot of advertised popular rides" src="https://user-images.githubusercontent.com/74382969/118316694-c19bda00-b4bc-11eb-94cc-09fdb5b08b72.png">
From the [Citibike website](https://www.citibikenyc.com/).


# Basic Map

This map shows every station from which a ride began in April 2021. The color indicates the number of rides starting at each station.

From this map we can see that the most rides are being taken in Manhattan, as well as in Brooklyn near the river and Prospect Park. We can also see that there are a lot of stations where almost no one is checking out a citi bike, like 9th Ave & W 219 Street, where only 5 bikes were checked out in April!


# Overview
Bikesharing project is a challenge to explore data visualizations of Citibike(bike sharing business in New York City) through Tableau. The idea is to explore the data and understand the details of such business so as to make a projection of a similar business in Des Moines, Iowa.

# Results
In order to make our research, we selected the month of August (2019). Being in Summer, August is normally busy and people tend to engage more in outdoor activities giving us the opportunity to analyse more data. In all, there were 2,344,224 in August 2019, being 81% of these rides taken by Subscribers of the service.

In a nutshell, it is easily observed that the busiest hours are the early hours in the morning and in the evening:

![Trip-distribution-through-the-day](Trip-distribution-through-the-day.jpg)

The following chart shows each of the bike of the system with its corresponding month riding hours (the larger the dot, the more it rode). This is important to think of maintenance program - the last we want is the bike to break while rented!

![Bike_utilization_through_the_month](Bike_utilization_through_the_month.jpg)

The three charts below show the trips by the hour by gender (Male, Female or Unknown when the gender information is not available). The Male and Female charts show some sort of similarity in pattern during weekdays while the "unknown" had the busies hours in the weekends.

![Count_trips_by_hour_male](Count_trips_by_hour_male.jpg)

![Count_trips_by_hour_female](Count_trips_by_hour_female.jpg)

![Count_trips_by_hour_unknown](Count_trips_by_hour_unknown.jpg)

The chart below shows the distributions by gender by weekdays. It is clear that the majority of riders are male!

![Count_trips_by_weekday_by_gender](Count_trips_by_weekday_by_gender.jpg)

The next two charts show trip duration - being the first the consolidation of all riders and the second one with gender breakdown. It is interesting to observe that the great majority of rides last up to 20 minutes, being somehow rare longer rides.

![Trip_duration](Trip_duration.jpg)

![Trip_duration_by_gender](Trip_duration_by_gender.jpg)



# Summary
The final tableau story can be found at: https://public.tableau.com/app/profile/ana.l.gajardoni/viz/Book1_16459145436010/CitibikingProject-Letsbegreen

It was a very interesting exercise to visualize data! I would propose making extra charts:
- to understand the "flow" of the bikes between stations: Start/Stop Locations.
- to correlate repeating trips (query above) with the time of the day - and then, the trip back if any - so as to predict the need of more bikes in each location at different times of the day.

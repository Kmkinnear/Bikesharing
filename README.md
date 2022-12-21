# Bikesharing

## Project Overview

In this project, we did an analysis on a dataset to use in our bike-sharing proposal for the city of Des Moines. The first deliverable in this challenge was to pull bike sharing data from the Citi Bike System website for August 2019. From there we used Jupyter Notebook to create a dataframe using Pandas. We then used Pandas to change the data type of our "Trip Duration" column from the "int64" data type to the "datetime64" data type. After that was completed, we exported our dataframe to a new .csv file that we would use in Tableau for Deliverable 2. We were able to use our new trip data .csv file to manipulate and create 5 different visualizations that we would be able to use in our proposal. The final deliverable involved creating a story in Tableau with our visualizations that we previously created.

## Results

### August Peak Hours
![August Peak Hours](https://user-images.githubusercontent.com/110848660/209014341-20aab0d5-be60-442e-b87d-a9c047c99412.png)

The bar chart above shows the peak usage hours for the bike sharing program. We can see that the busiest time for bike usage is around 17:00-18:00. We can also see that the lowest usage hours are from all hours before 5:00. That would be the ideal time to move bikes to more popular areas for the following day or to do maintenance. 


### Top Starting Locations
![Top Starting Locations](https://user-images.githubusercontent.com/110848660/209014794-3671309d-04a2-416a-b56e-d3dc779a091c.png)

The next visual that we have is a symbol map and we've used it to show the most popular places for bike usage. We can drill down to get exact coordinates on where the most popular spots are for bike rentals. We would expect to see hot spots around popular tourist destinations since many tourists can get around more easily in a larger city on a bicycle.


### Checkout Times for Users
![Checkout Times for Users](https://user-images.githubusercontent.com/110848660/209015759-09c3bf92-70f8-4f8b-8a66-b52b1e2b02e0.png)

The line chart shown above shows us the typical checkout times for the users. We can see that the highest percentage of riders are using their bikes for less than 20 minutes. There is also a big drop in the number of trips lasting longer than 40 minutes. It's clear that people do not mind a bicycle for a shorter trip, but prefer other means of transportation for any kind of longer trip.


### Checkout Times by Gender
![Checkout Times by Gender](https://user-images.githubusercontent.com/110848660/209016205-9d6dfe05-fe36-43e0-a0ef-5aa5e729de72.png)

We took our checkout time line chart a step further and broke it out by "gender". We see similar results where most of the rides are less than 20 minutes and trips after 40 minutes being almost nonexistent. This chart also shows us that the majority of bike-sharing usage is by males.


### Trips by Weekday for Each Hour
![Trips by Weekday for Each Hour](https://user-images.githubusercontent.com/110848660/209016666-edbf882d-0581-4636-8987-65c047c56909.png)

The next chart that we created was a heatmap that showed us the number of trips by weekday and then broken down by each hour. We can see in the chart that the busiest days for bike rental usage are Monday-Friday. We can also see that the busiest times for usage are between 6:00-9:00 and 17:00-18:00. We can assume here that not only are tourists using the bike sharing program, but commuters are too. On the weekends we can see that bike usage is constant between 9:00-19:00 without as many peak usage hours as during the week.


### Trips by Gender (Weekday per Hour)
![Trips by Gender (Weekday per Hour)](https://user-images.githubusercontent.com/110848660/209017614-6fdca5c9-6329-4288-a6d6-20a08877f12a.png)

In the next chart we took our heatmap a step further and separated it out by the number of trips per gender. We see similar results here as the combined chart with the busiest times being around rush hour (8:00 and 17:00-18:00). We also get similar data with what we saw in our line chart where the biggest number of users are males.


### User Trips by Gender by Weekday
![User Trips by Gender by Weekday](https://user-images.githubusercontent.com/110848660/209018219-da37fec0-ed77-4412-8d1d-fb39a844e6bb.png)

The final chart that we created was another heatmap that showed the breakdown of users by gender, day of the week, and whether they were a customer or subscriber to the bike-sharing program. We can see from looking at the chart that the greatest concentration of users appears to be male riders, who are subscribers. We can also see that their heaviest usage is during Monday-Friday which would make us think that this group is using the bike-sharing program for commuting.

## Summary

There are a few conclusions that we can make from looking at the data and visulizations above. We saw in multiple charts that the highest usage in the bike-sharing program is by males. We can also see the peak usage times in different visulizations where it shows that the bikes were normally used around normal business opening and closing hours. We can assume that these riders are commuters and may not have a vehicle of their own since they live in the city. We were also able to see in our symbol map where the most popular usage points were. We suspect that these areas are areas that either have tourist destinations or areas in the business district where commuters are utilizing them. One of the other main takeaways that we have from the charts is that the usage time is generally less than 20 minutes per ride. There is also very little usage once the ride time goes over 40 minutes. 

Despite the number of visualizations that we completed in this challenge, there is still much to be done to help us in our proposal.

 - One additional visualization that I would like to do with the dataset are to do a similar analysis, but to use a different month. We used the month of August in this analysis due to it being a popular month. I would like to see how the usage numbers would look if we used one of the winter months like December or January where people would be less likely to ride bicycles. My guess is that there would not be a lot of bicycle usage so we would need to find ways to scale down or store bikes that may not be needed during those months to keep costs down. 
 
 - The other analysis that I would like to see done is to drill down on the popular areas to see where the most popular drop off locations are. Since most of our riders appear to be commuters, it would be interesting to see if these users drop them off at gyms or office buildings that may have access to changing rooms and showers. We would suspect that most users are changing and showering after biking to work so it would be interesting to see what and where those facilities are. This make also explain the discrepancy in the rider's gender if females don't have access to changing facilities or showers. Not being able to change or shower after biking to work is going to discourage them from riding a bicycle to work.

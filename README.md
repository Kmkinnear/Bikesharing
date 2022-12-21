# Bikesharing

## Project Overview

In this project, we did an analysis on a dataset to use in our bike-sharing proposal for the city of Des Moines. The first deliverable in this challenge was to pull bike sharing data from the Citi Bike System for August 2019. From there we used Jupyter Notebook to create a dataframe using Pandas. We then used Pandas to change the data type of our "Trip Duration" column from the "int64" data type to the "datetime64" data type. After that was completed we exported our dataframe to a new .csv file that we would use in Tableau for Deliverable 2. We were able to use our new trip data .csv file to manipulate and create 5 different visualizations that we would be able to use in our proposal. The final deliverable involved creating a story in Tableau with our visualizations that we previously created.

## Results

![August Peak Hours](https://user-images.githubusercontent.com/110848660/209014341-20aab0d5-be60-442e-b87d-a9c047c99412.png)

The bar chart above shows the peak usage hours for the bike sharing program. We can see that the busiest time for bike usage is around 17:00-18:00. We can also see that the lowest usage hours are from all hours before 5:00.

![Top Starting Locations](https://user-images.githubusercontent.com/110848660/209014794-3671309d-04a2-416a-b56e-d3dc779a091c.png)

The next visual that we have is a symbol map and we've used it to show the most popular places for bike usage. We can drill down to get exact coordinates on where the most popular spots are for bike rentals. We would expect to see hot spots around popular tourist destinations since many tourists can get around easier in a larger city on a bicycle.

![Checkout Times for Users](https://user-images.githubusercontent.com/110848660/209015759-09c3bf92-70f8-4f8b-8a66-b52b1e2b02e0.png)

The line chart shown above shows us the typical checkout times for the users. We can see that the highest percentage of riders are using the bikes for less that 20 minutes. There is also a big drop off in the number of trips lasting longer than 40 minutes. It's pretty clear that people do not mind a bicycle for a shorter trip but prefer other means of transportation for any kind of longer trip.

![Checkout Times by Gender](https://user-images.githubusercontent.com/110848660/209016205-9d6dfe05-fe36-43e0-a0ef-5aa5e729de72.png)

We took our checkout time line chart a step further and broke it out by "gender". We see similar results where the majority of rides are less than 20 minutes and trips after 40 minutes being almost nonexistent. This chart also shows us that the majority of bike rental are by males.

![Trips by Weekday for Each Hour](https://user-images.githubusercontent.com/110848660/209016666-edbf882d-0581-4636-8987-65c047c56909.png)

The next chart that we created was a heatmap that showed us the number of trips by weekday and then broken down by each hour. We can see in the chart that the busiest days for bike rental usage are Monday-Friday. We can also see that the busiest times for usage are between 6:00-9:00 and 17:00-18:00. We can assume here that not only are tourists using the bike sharing program but commuters are too. On the weekends we can see that bike usage is pretty constant between 9:00-19:00 without as many peak usage hours as during the week

## Summary


# Weather To Go

This repo contains the "Weather to go" chatbot source code as well as ideas and storyboards created during the design process.

## About the project

Our team aims to provide a solution for public transportation challenges that Sydney is facing. According to the data provided by BOM and Open Data, there is an obvious correlation between weather, and busses or trains punctuality and high usage volumes. We have prepared the “Weather to go” software: a two-part solution to help out both the users and the public transportation officers.
Users can connect to the chatbot that analyzes the real-time data around the user like weather and the traffic intensity, and helps to decide what is the most optimal time to leave for the bus or train. The dashboard is our future feature, that could provide the recommendations for the governmental agencies. It would include the real-time data about the capacity, weather, and traffic. All data would be provided in easy to use, interactive graphs.

In that matter, the “Weather to go” could be a great help in planning, developing and improving the NSW public transportation.

## Data Sets

BOM:

![alt text][bomlogo]

<br>

Open Data Transport NSW:

![alt text][tnswlogo]

[bomlogo]: https://static1.squarespace.com/static/57b1a49df7e0ab6f35b45df6/t/57bb0a95b8a79b87b20cbd8a/1471875737444/ "Bureau of Meteorology"
[tnswlogo]: https://opendata.transport.nsw.gov.au/themes/open_data_portal/logo.png "Open Data Transport NSW"


## What do we want from government data?

https://2018.hackerspace.govhack.org/challenges/41

As developers, having the best access to data enables us to create high performing data driven applications. For GovHack 2018, we used Transport NSW data sets to help consumers decide their transport options as well as help public transport officials with forecast scheduling.

One thing that we found during our data exploration was that we wanted more granular data to work with. We found this particularly in relation to the Transport NSW data sets as we were investigating public transport performance trends. We were interested in doing day to day
comparisons but the data was only broken down by month only. If the data had been broken down by day we would have been able to have more accurate results. Similarly, when we were looking at location based data there could have been more specificity around postcodes instead of only area based.

Our team also found that the government data was often available for export across a wide variety of file types. For example, some data was accessible via APIs and the data format was JSON and others such as the Realtime Trip Updates API used the General Transit Feed Specification GTFS-realtime. This meant that extra time was spent consuming different datasets as they needed to be handled separately.

In some cases there was limited access to historical data. For example, ferry performance data only went back to 2016.


## Tech

- Node JS
- Express
- Facebook Messenger Platform https://developers.facebook.com/docs/messenger-platform/
    - Used the boilerplate [Messenger Platform quick start tutorial](https://developers.facebook.com/docs/messenger-platform/getting-started/quick-start).
- Hosted on Heroku

## Privacy Policy

We do not store or share any user data whatsoever. Location data is used solely for weather and travel predictions.
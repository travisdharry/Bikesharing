# Bikesharing
Bikeshare Analysis Project for UT Austin Data Analysis & Visualization Program <br>

## Project Overview
We were asked to analyze bikeshare data and create a series of visualizations that would describe ridership patterns. We analyzed ride data by starting and ending location, and looked as well at usage times based on gender and on customer/subscriber type. We created visualizations and a final story report in Tableau. <br>
<a href="https://public.tableau.com/app/profile/travis.harry/viz/Bikeshare_Report/BikeshareReport">Final Report - Tableau Story</a>

## Resources
- Data Sources: citibikenyc.com (2019-08-citibike-tripdata.csv)
- Software: Python, Tableau, Jupyter Notebook

## Results
#### - Top Starting and Ending Locations
<p padding-left: 50px>We used the latitude/longitude coordinates for each ride's starting and ending locations to create a map of New York City, then adjusted the marker sizes and colors to reflect the frequency of rides to and from each location. The analysis shows that rides often originate outside the city and move inward to the city center.</p><br>
<a href="https://public.tableau.com/app/profile/travis.harry/viz/Bikeshare_StartLocs/TopStartingLocations">Top Starting Locations</a>
<p align ="center">
<img src="images/screenshot1.png" alt="Start Location"/><br>
</p>
<br>
<a href="https://public.tableau.com/app/profile/travis.harry/viz/Bikeshare_EndLocs/TopEndingLocations">Top Ending Locations</a>
<p align ="center">
<img src="images/screenshot2.png" alt="End Location"/><br>
</p>
<br>

#### - Peak Hours
<p padding-left: 50px>We created a bar chart to show the count of rides by each hour of the day. This chart shows that the peak hours of the day are 8-9am and 5-6pm.</p><br>
<a href="https://public.tableau.com/app/profile/travis.harry/viz/Bikeshare_PeakHours/AugustPeakHours">Peak Hours</a>
<p align ="center">
<img src="images/screenshot3.png" alt="Peak Hours"/><br>
</p>
<br>

#### - Checkout Times
<p padding-left: 50px>We charted the number of trips by trip duration. This shows that most trips last less than an hour, with the greatest number being around ten minutes.</p><br>
<a href="https://public.tableau.com/app/profile/travis.harry/viz/Bikeshare_CheckoutTimes/CheckoutTimesforUsers">Checkout Times</a>
<p align ="center">
<img src="images/screenshot4.png" alt="Checkout Times"/><br>
</p>
<br>


#### - Trips by Weekday
<p padding-left: 50px>We created a heatmap to show the most popular times of week to ride. The most popular times corresponded to the business day morning/evening rush hours. Weekend days were more spread out.</p><br>
<a href="https://public.tableau.com/app/profile/travis.harry/viz/Bikeshare_TripsWeekdayHour/TripsbyWeekdayperHour">Trips by Weekday</a>
<p align ="center">
<img src="images/screenshot5.png" alt="Trips by Weekday"/><br>
</p>
<br>

#### - Breakdown by Gender
<p padding-left: 50px>We created a pie chart showing ride usage by gender. The bulk of customers are male, with females or those of unknown gender composing a smaller segment of the customer base.</p><br>
<a href="https://public.tableau.com/app/profile/travis.harry/viz/Bikeshare_GenderBreakdown/GenderBreakdown">Breakdown by Gender</a>
<p align ="center">
<img src="images/screenshot6.png" alt="Breakdown by Gender"/><br>
</p>
<br>

#### - Checkout Times by Gender
<p padding-left: 50px>We charted trip duration based on gender. The genders shared similar riding habits, preferring to ride less than an hour.</p><br>
<a href="https://public.tableau.com/app/profile/travis.harry/viz/Bikeshare_CheckoutTimesGender/CheckoutTimesbyGender">Checkout Times by Gender</a>
<p align ="center">
<img src="images/screenshot7.png" alt="Checkout Times by Gender"/><br>
</p>
<br>

#### - Trips by Weekday by Gender
<p padding-left: 50px>We created another heatmap to show the differences in usage by hour based on gender. This shows that female riders and male riders share similar usage patterns throughout the week.</p><br>
<a href="https://public.tableau.com/app/profile/travis.harry/viz/Bikeshare_TripsWeekdayHourGender/TripsbyWeekdayperHourbyGender">Trips by Weekday by Gender</a>
<p align ="center">
<img src="images/screenshot8.png" alt="Trips by Weekday by Gender"/><br>
</p>
<br>

#### - Trips by Weekday by Gender and Usertype
<p padding-left: 50px>We created a final heatmap showing usage frequency by time, as well as by gender and whether the user was a subscriber or a one-time customer. This heatmap shows that one-time customers tend to ride more on weekends, while subscribers tend to ride during the week, especially during rush hour times.</p><br>
<a href="https://public.tableau.com/app/profile/travis.harry/viz/Bikeshare_UserTripsGenderWeekday/UserTripsbyGenderbyWeekday">Trips by Weekday by Gender and Usertype</a>
<p align ="center">
<img src="images/screenshot9.png" alt="Trips by Weekday by Gender and Usertype"/><br>
</p>
<br>


## Summary
<p>The analysis of the bikeshare data has shown that most users are male. Even so, gender does not play as much of a role in rider habits. Subscribers tend to ride during the weekday, gravitating towards rush hour times. These users are likely workers in the city using bikes to commute to and from their jobs. Non-subscribers tend to ride on the weekends. These users are likely tourists in town for the weekend using bikes to visit sightseeing locations. For further analysis we should ask if these non-subscribers are indeed one-time users or if they are repeat users. We should also ask if the numbers of subscribers who are riding on weekends is greater or less than the number of non-subscribers.</p>
# bikesharing
https://public.tableau.com/app/profile/ashi.shukla/viz/CitiBikestory_16229236728170/CitiBikestory

# Overview

This is the citi bike campaigns that is annually organized within New York. The main idea is to provide visitors easy access of whole Manhattan and Neighbouring cities.There are 800 Citi Bike stations and 13,000 bikes across Manhattan, Brooklyn, Queens and Jersey City.

The new member as customer can join with 3 day pass also, the annual member join as subscriber to enjoy the rides from start station to end station. The idea is to analyze the number of records with trip duration every year and compare the number of records every year on basis of weekdays for hourly basis, gender preference also impact the data and results.

# Results

We have created numbers of worksheet to analyze different scenario using 2019 acv data. First we updated the data of trip duration using pandas and created gender in string type. Tableau Desktop is used to visualize and compare the data in structure, organize and most formatting way to understand the analysis.

1- Number of trip duration is used in two different ways (Hourly and Minutes) vs Number of Bikes generated which tells that most of the rides were commuted between 20 to 40 minutes.
<img width="1440" alt="Screen Shot 2021-06-05 at 3 52 58 PM" src="https://user-images.githubusercontent.com/79673185/120905334-5f4b7a80-c61f-11eb-892f-1f5cde96998d.png">
https://public.tableau.com/app/profile/ashi.shukla/viz/CheckoutTimesforUsersViz/CheckoutTimesforUsersViz

2- Number of trip duration using (Hours and Minutes) vs number of bikes generated using gender specified generated field which tells that Male have the highest rate of rides s compare to female and other gender specifics people.
<img width="1440" alt="Screen Shot 2021-06-05 at 3 53 18 PM" src="https://user-images.githubusercontent.com/79673185/120905332-5c508a00-c61f-11eb-9334-a13f8b62233b.png">
https://public.tableau.com/app/profile/ashi.shukla/viz/CheckoutTimesbyGenderViz/CheckoutTimesbyGenderViz

3- We needed to know the trips by weekday for each hour using stop and start time with number of bike records in marks field. The data shows that morning time between 7 to 9 am and in evening 5 to 7pm have the highest peak.

<img width="1440" alt="Screen Shot 2021-06-05 at 3 53 28 PM" src="https://user-images.githubusercontent.com/79673185/120905323-53f84f00-c61f-11eb-8ee8-1ba2d132d6e1.png">
https://public.tableau.com/app/profile/ashi.shukla/viz/TripsbyWeekdayforEachHourViz_16229232967460/TripsbyWeekdayforEachHourViz
4- This shows the same fields just the addition of gender generated field that tells us that Males like to ride in morning and evening time the most where as females like the evening time best.

<img width="1440" alt="Screen Shot 2021-06-05 at 3 54 12 PM" src="https://user-images.githubusercontent.com/79673185/120905319-4d69d780-c61f-11eb-81d3-cf475ad84a12.png">

https://public.tableau.com/app/profile/ashi.shukla/viz/TripsbyGenderWeekdayperHourViz_16229233416860/TripsbyGenderWeekdayperHourViz
5- The user types field with gender generated by weekdays tells us that customer are lest interested in riding the bikes as compare to subscribers and in those also males are the most active users.

<img width="1440" alt="Screen Shot 2021-06-05 at 3 54 20 PM" src="https://user-images.githubusercontent.com/79673185/120905310-4642c980-c61f-11eb-990f-6d7291c811e6.png">
https://public.tableau.com/app/profile/ashi.shukla/viz/UserTripsbyGenderbyWeekdayViz_16229233884770/UserTripsbyGenderbyWeekdayViz

The other two visuals are created that I have learnt in this module using map layers:

A- Overall users using start station data with number of stations shows that number of stations with average of bikeid.

<img width="1440" alt="Screen Shot 2021-06-05 at 3 55 16 PM" src="https://user-images.githubusercontent.com/79673185/120905305-3dea8e80-c61f-11eb-94ea-d202233783be.png">
https://public.tableau.com/app/profile/ashi.shukla/viz/OverallUsersusingstartstationname/OverallUsersusingstartstationname

B- Overall users using end station data with number of stations shows that number of stations with average of bikeid. 

<img width="1440" alt="Screen Shot 2021-06-05 at 3 56 12 PM" src="https://user-images.githubusercontent.com/79673185/120905301-388d4400-c61f-11eb-8027-3b8eb45e843b.png">
https://public.tableau.com/app/profile/ashi.shukla/viz/OverallUsersusingendstationname/OverallUsersusingendstationname

# Summary


To summarize the all the visuals story is created where all the charts and analysis is described as per the information provided in updated data. Apart from the results that I have presented above the other two data that I would recommend or would want to show is the top 10 start stations as per the start time and top 10 end station as per end time that shows us the more information for future analysis. I have tried to make the charts and added in the story book.

<img width="1440" alt="Screen Shot 2021-06-05 at 3 56 17 PM" src="https://user-images.githubusercontent.com/79673185/120905291-23181a00-c61f-11eb-8dff-54d8a462d54e.png">

https://public.tableau.com/app/profile/ashi.shukla/viz/Top10startstationsvsstationidcount/Top10startstationsvsstationidcount

<img width="1440" alt="Screen Shot 2021-06-05 at 3 56 21 PM" src="https://user-images.githubusercontent.com/79673185/120905285-1f849300-c61f-11eb-8505-5499f63d9671.png">
https://public.tableau.com/app/profile/ashi.shukla/viz/Top10endstationsvsstationidcount/Top10endstationsvsstationidcount

<img width="1440" alt="Screen Shot 2021-06-05 at 5 00 06 PM" src="https://user-images.githubusercontent.com/79673185/120905370-928e0980-c61f-11eb-97e1-032a85ee3f76.png">



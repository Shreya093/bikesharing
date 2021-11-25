# Citibike Bikesharing

## Purpose

The purpose of the project was to use data from New York City's Citi Bike program and see if it would be possible to recreate the program in De Moines, Iowa. In order to complete this analysis, I used Python's pandas library to clean up the data and then created visualizations of that data using Tableau.

## Objectives

1. Import data into Tableau.
2. Create and style worksheets, dashboards, and stories in Tableau.
3. Use Tableau worksheets to display data in a professional way.
4. Portray data accurately using Tableau dashboards.

## Link to Tableau Story

[Tableau Story]("https://public.tableau.com/app/profile/shreya.srivastava4743/viz/NYCCitiBikeStory_ModuleChallenge/NYCCitiBikeStory?publish=yes")

## Cleaning the data

We had to use Pandas to clean our data. Using it we changed the "tripduration" column from an integer to a datetime datatype.

**Before Change :**

<img width="371" alt="datatype before" src="https://user-images.githubusercontent.com/88418201/143499157-056a58f6-eb48-4eae-9941-496b5aae1fcc.png">

**After Change :**

<img width="1272" alt="query" src="https://user-images.githubusercontent.com/88418201/143499370-c459b71a-985c-4307-91ab-0c6c22f543b2.png">

<img width="359" alt="datatype after" src="https://user-images.githubusercontent.com/88418201/143499183-099d9e5d-2c42-4e3e-8b01-b0132dc31d4b.png">

## Results of the NYC Citibikes Analysis

Using the NYC citibike data we found that there were some interesting geographical areas of interest. Some trips were outside the main city center. Other areas followed the along the river. Future analysis would need to include a geographical review.

## 1. Checkout Time for All Users :

[Checkout Time for All Users]("https://public.tableau.com/app/profile/shreya.srivastava4743/viz/CheckoutTimeforUsers_16377972283520/CheckoutTimesforUsers?publish=yes")

The graph shows that the vast majority of trips taken on CitiBike bikes are under an hour in length. More specifically, most trips are under a half-hour in length, with a swift dropoff in number of rides over an hour in length.

<img width="1400" alt="1" src="https://user-images.githubusercontent.com/88418201/143500370-bedde68a-26ec-4414-beb6-502a7b2b1e7c.png">


## 2. Checkout Times by Gender :

[Checkout Times by Gender]("https://public.tableau.com/app/profile/shreya.srivastava4743/viz/CheckoutTimebyGender_16377978903760/CheckoutTimesbyGender?publish=yes")

This breakdown of number of rides by duration, separated by gender, makes it even more apparent that Males are significantly higher bike users than others.

<img width="1400" alt="2" src="https://user-images.githubusercontent.com/88418201/143500613-b21ae038-5dd1-43d5-b41c-995907abdf01.png">


## 3. Trips by Weekday per Hour :

[Trips by Weekday per Hour]("https://public.tableau.com/app/profile/shreya.srivastava4743/viz/TripsbyWeekdayperHour_16377984964870/TripsbyWeekdayperHour?publish=yes")

The heatmap graph shows that 6-10 am and 5-8 PM are peak riding hours during the weekday and 5 am to 10 pm on the weekends.

<img width="1400" alt="3" src="https://user-images.githubusercontent.com/88418201/143500742-b16d9565-049f-4018-9a30-9a6f2f372ae6.png">


## 4. Trips by Gender (Weekday per Hour) :

[Trips by Gender (Weekday per Hour)]("https://public.tableau.com/app/profile/shreya.srivastava4743/viz/TripsbyGenderWeekdayperHour_16377988662440/TripsbyGenderWeekdayperHour?publish=yes")

Male bikers are the high users during the peak hours.

<img width="1400" alt="4" src="https://user-images.githubusercontent.com/88418201/143501049-8ede7a39-2cd4-43d6-b005-84fb957ca15b.png">

## 5. User Trips by Gender by Weekday :

[User Trips by Gender by Weekday]("https://public.tableau.com/app/profile/shreya.srivastava4743/viz/UserTripsbyGenderbyWeekday_16377992836770/UserTripsbyGenderbyWeekday_1?publish=yes")

The graph shows that the Males subscribers are the highest users followed by female subscribers.

<img width="1400" alt="5" src="https://user-images.githubusercontent.com/88418201/143501208-a4e03c4b-ad97-42b5-ba39-01a695f261dd.png">

## 6. Number of Rides per Hour :

[Number of Rides per Hour]("https://public.tableau.com/app/profile/shreya.srivastava4743/viz/NumberofRidesperHour/NumberofRidesperHour?publish=yes")

The bar graph shows that 1am to 5am are the non-peak bikeriding hours.

<img width="1400" alt="6" src="https://user-images.githubusercontent.com/88418201/143501477-39fac9a9-c23e-4ede-837b-b05c48a4c0cb.png">


## 7. Number of Rides with Bike ID :

[Number of Rides with Bike ID]("https://public.tableau.com/app/profile/shreya.srivastava4743/viz/NumberofRideswithBikeID/NumberofRideswithBikeID?publish=yes")

The divergence line shows that there are high use on 1/3 of the bikes.

<img width="1400" alt="7" src="https://user-images.githubusercontent.com/88418201/143501571-9ba56550-2fc9-4823-bf44-db7d135d0db1.png">


## Summary 

1. Bike Repairs for 1/3 of the Citibikes need to be done during non-peak hours around 1-5 am.
2. Male subscribers are the highest users and follow the traditional high use times of travel to and from work.
3. Target market should be males needing transportation to work and weekend activities and push for subscribing to the services.

## Additional Analysis

For NYC, there were some interesting geographical areas of interest. Some trips were outside the main city center. Other areas followed the along the river. Future analysis would need to include a geographical review.

## 1. Ride Starting Locations by Gender

[Ride Starting Locations by Gender]("https://public.tableau.com/app/profile/shreya.srivastava4743/viz/RideStartingLocationsbyGender/RideStartingLocationsbyGender?publish=yes")

The map shows that Males are more likely to start a trip farther than the main city center of NYC than others.

<img width="1400" alt="8" src="https://user-images.githubusercontent.com/88418201/143501920-edd06b6d-920a-44b6-b16e-d16ed2b33603.png">


## 2. Ride Ending Locations by Gender

[Ride Ending Locations by Gender]("https://public.tableau.com/app/profile/shreya.srivastava4743/viz/RideEndingLocationsbyGender/RideEndingLocationsbyGender?publish=yes")

Males are more likely end a trip across the river in the southwest area of NYC than others.

<img width="1400" alt="9" src="https://user-images.githubusercontent.com/88418201/143501924-38a11c30-9088-40fc-9ad6-c5cedb89220c.png">

## 3. User Type Starting Location

[User Type Starting Location]("https://public.tableau.com/app/profile/shreya.srivastava4743/viz/UserTypeStartingLocation/UserTypeStartingLocation?publish=yes")

Subscribers are more likely to start trip farther than the main city center of NYC than others.

<img width="1400" alt="10" src="https://user-images.githubusercontent.com/88418201/143501925-128db8b5-b39b-40a7-af33-16287824912b.png">






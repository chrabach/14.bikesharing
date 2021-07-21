# BikeSharing

## Resources
Tableau 2021.2.0, Pandas 1.2.4

## Overview

The purpose of this analysis is to evaluate the viability of a bike share opportunity in Des Moines, Iowa.  To do so, we utilize data from an already running bikesharing program in New York City.


## Results


![Fig1: Checkout Times](other_resources/01_Checkout_Times_For_Users.png)
[Fig1: Checkout Times](other_resources/01_Checkout_Times_For_Users.png?raw=true "Figure 1: Checkout Times")

Figure 1 demonstrates that the bulk of trips are less than 30 minutes long, with the outstanding majority around 5 minutes long.  This is likely due to the pricing structure of the citibikes program, which charges an overage price for rental times greater than 45 minutes.  

![Fig2: Checkout Times by Gender](other_resources/02_Checkout_Times_by_Gender.png)
[Fig2: Checkout Times by Gender](other_resources/02_Checkout_Times_by_Gender.png?raw=true "Figure 2: Checkout Times by Gender")

Figure 2 goes into more detail, illustrating the same checkout times, but now broken down by gender.  The main conclusion here is that the bulk of bike users during this period were men.

![Fig3: Trips by Weekday per Hour](other_resources/03_Trips_by_Weekday_per_Hour.png)
[Fig3: Trips by Weekday per Hour](other_resources/03_Trips_by_Weekday_per_Hour.png?raw=true "Figure 3: Trips by Weekday per Hour")

Figure 3 illuminates the time of day of bike trips, portraying that the heaviest traffic times are during rush hours.

![Fig4: Trips by Weekday Each Hour](other_resources/04_Trips_by_Weekday_Each_Hour.png)
[Fig4: Trips by Weekday Each Hour](other_resources/04_Trips_by_Weekday_Each_Hour.png?raw=true "Figure 4: Trips by Weekday Each Hour")

Figure 4 is similar to Figure 3, but drills into genders.  As in figures 1 and 2, we see that men are the primary users of the service, but here in Figures 3 and 4 we see that the primary travel time is during rush hours, during the week. 

![Fig5: Users Trips by Gender](other_resources/05_Users_Trips_by_Gender_by_Weekday.png)
[Fig5: Users Trips by Gender](other_resources/05_Users_Trips_by_Gender_by_Weekday.png?raw=true "Figure 5: Users Trips by Gender")

Figure 5 further breaks down the ride frequency metrics, this time segregating User Types by Weekday and Gender.  The predominant users of the service are males, during the week, who subscribe to the service.  This is likely because of pricing benefits to the customers, and will need to be analyzed further to optimize the pricing structure of the service in Des Moines.


![Fig6: Starting Locations](other_resources/06_Top_Starting_Locations.png)
[Fig6: Starting Locations](other_resources/06_Top_Starting_Locations.png?raw=true "Figure 6: Starting Locations")

Figure 6 shows primary starting locations, with larger icons representing more heavily utilized locations.

![Fig7: Ending Locations](other_resources/07_Top_Ending_Locations.png)
[Fig7: Ending Locations](other_resources/07_Top_Ending_Locations.png?raw=true "Figure 7: Ending Locations")

Figure 7, meant to be viewed in conjunction with Figure 6, illustrates stopping locations, with larger icons again representing more heavily utilized locations.  New York City is a heavily concentrated business district, with most of the traffic focused into a relatively small area.  Many of the main starting and stopping locations are the same and in the business district, indicating that the service is largely utilized by commuters.



Please find the link to the Tableau version of the figures here:

[Link to Tableau](https://public.tableau.com/app/profile/chris7098/viz/14_BikeShare_Challenge/ChallengeStory?publish=yes"Link to Tableau")


## Summary

The main users of the NYC ride share service are men who subscribe to the service and utilize it during rush hour in a relatively concentrated surface area.  Another visualization that would accentuate this analysis would be a display of age of riders utilizing the service, by time of week.  A second visualization might be to represent pricing schedules, which might highlight some of the reasons for the results represented in this analysis. 

# UT_Austin-BCycle_project

This is the final project of Data Analytics programing. My group studied on: " Improving the rebalancing plan for Austin B-cycle, the bike sharing company,  to relief the traffic problem in Austin, Texas by using AUstin B-cycle's trip data and station data". I was mainly responsible for exploratory data analysis, and the bike traffic plot on Google map.

After finishing exploratory data analysis, we came up with several conslution: First, bike ride taken by different types of membership differ in their trip duration and the time of their bike rental. Second, bike rental trips differs significantly between weekdays and weekends. Third, while the bike trips boosts during festivals like South by South West and Austin City Limit, we consider Austin B-Cycle take an important role in transportation of these festivals and the bike rental pattern at that time will be very different.


## Google Map plots 
To improve the bike rebalancing plan for Austin B-Cycle, I plotted each station's bike borrow and return on Google Map. A blue and red circle indicates borrow and return of bikes, respectively. While the radius of the circle are weighted by the number of borrow / return, the rings of two overlap circles on each bike stations tells the difference between borrow and return. Therefore, a pink circles says that there are more borrow than return of bikes, and the surrounding red rings shows the number of difference. On the other hand, a purple circle tells that there are more return than borrow, and the surrounding blue ring shows thme number of difference.


### In General 
This plot is generated using the entire dataset. We can see that, generally, people borrow bikes from the surrounding area and ride them to downtown Austin or places like Zilker Park or Mini Golf place. And the Austn B-Cycle has a descent balance of bike distribured between stations.

![gm_general](https://user-images.githubusercontent.com/31845611/44631808-d31cac80-a936-11e8-8ab7-bd2be3339d72.png)


### In Rush Hours
In order to solve Austin City's traffice problem, we look into the bike trips in the morning rush hour. We found that most bike rides in this time starts from residentail area to downtown Austin. Therefore, we suggest the bike rebalancing among stations to spread bikes from downtown to the surroundings and meet the demand of a bike ride. Comparatively, in a raninly, there are signigicant drop in number of bike trip taken. And the starting station of a bike trip seems more concentrated but has similiar patterns.

<img width="912" alt="screen shot 2018-08-26 at 1 53 35 pm" src="https://user-images.githubusercontent.com/31845611/44631858-7d94cf80-a937-11e8-90d5-f6f75e3771bc.png">


### On Weekends
On weekends, the imbalance of bikes between stations become a smaller problem. And we can see a greater number of bike returns in the areas around the river. Which implies those stations being destinations of recreational bike trips.

![gm_weekend](https://user-images.githubusercontent.com/31845611/44631942-cef18e80-a938-11e8-9593-a93260224259.png)


### Special events: South by South West and Austin City Limit
During both special events, we can found very different borrow/return patterns. Where bike returns are concentrated on the venues of the festivals.

<img width="901" alt="screen shot 2018-08-26 at 2 05 10 pm" src="https://user-images.githubusercontent.com/31845611/44631958-1e37bf00-a939-11e8-8893-d4ebb62e20c7.png">



## Conclusion
Though the borrow/return pattern displayed on Google map seems intuitive. It is still nice to know the shortage or overwhelmed number of bikes visualised at each station. And this provides valueable insights on exactly which stations are the ones that is in urgent need of bike-rebalancing. By including more factors and examine the problem under smaller time sclae, I believe there will be even more interesting findings and come up with a thorough plan to solve the traffice problem in Austin, Texas.

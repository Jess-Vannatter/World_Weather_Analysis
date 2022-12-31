# World_Weather_Analysis
## Overview of Analysis

### Purpose 
-   The goal of this analysis was to create a user interface that allows a client to chooose from over 650 countries and city's based on their temperature/ weather preference for  their possible vacation destination. We used API's to generate over 650 cities from random longitude and Latitude points across the globe and then gave the client the option to choose their preferred temperature range for their preferred vacation destination by posing the questions below in our code:
```
  (min_temp = float(input("What is the minimum temperature you would like for your trip? "))
  (max_temp = float(input("What is the maximum temperature you would like for your trip? "))
```
-   Which in our example we chose a minimum temperateure of 75 degree's and a maximum temperateure of 90 degrees. This then narrowed our City selection down to 198 possible destinations. We then took the next step by adding a parameter that narrowed it down even further for the cleint and added only city's that provided a near by Hotel as an option for the client to stay in. All while plotting these in our code and providing images of these plots.

![image](https://user-images.githubusercontent.com/117245167/210140178-04f9a59c-a1c4-4be6-a5d7-2965457a7eb2.png)

-   Lastly we provided a possilbe Iteneray for the client with a route to 4 possible city's thatfell in to the provided temerature parameters selected above. This was plotted using the hvplt.pandas function> al the data was generated using the GeoApify API. 

![image](https://user-images.githubusercontent.com/117245167/210140184-6a53ecd5-20d1-401d-b3f2-d3aa571d5ad1.png)

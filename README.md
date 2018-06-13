# Write-up: Flight Delays Visualization using Tableau
Alexander Andreev

Initial Version:
[public.tableau.com/views/AirDelays](https://public.tableau.com/views/AirDelays_0/StoryDelays?:embed=y&:display_count=yes&publish=yes)

Second Version:
[public.tableau.com/views/AirDelays_v2](https://public.tableau.com/views/AirDelays_v2/StoryDelays?:embed=y&:display_count=yes&publish=yes)


# Summary
The dataset contains information on United States flight delays and flight performance from 2013 until March 2018. 
The project covers four issues:
1. Trend in data and seasonal pattern of domestic flights
2. Distribution of delayed departures depending on the current traffic
3. Detailed presentation of the delay causes available in the source data
4. Hidden structure of delays, the key role of weather conditions

The first three items can be easily visualized from the downloaded data. The last part required additional data not available for download: two reasons, National Aviation System (NAS) delays and late-arriving aircraft, are recursive data and require further detailing.

# Design
Line plots and map diagrams are appropriate tools for visualization of spatio-temporal data and allow the user to interactively obtain the necessary information.
The last two plots are limited by the time data only due to the lack of spatial details of the additional data.

# Feedback
P.Martin wrote:  
"I have also analyzed the flight dataset so I find interesting to see other Tableau Stories.  
   - From my point of view, I would use finer lines in the linear graphs. In the third graph is specially confusing to see where the delay causes intersect one with each other.  
   - I would add more information regarding the hidden weather data. I have seen that you have used a coefficients to reshape the graphs. Where exactly did you get the data? Which coefficients do you use to get the visualization?
    Once you have included a map of the US flight air space, I would add filters to play around with the maps."   

Comments are taken into account. Linear graphics are better readable. There is an opportunity to choose of an airport and/or a state of US. The description of the data in the last slide is extended.



# Resources
 [Bureau of Transportation Statistics](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp)

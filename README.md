# Write-up: Flight Delays Visualization using Tableau
Alexander Andreev

Initial Version:
[public.tableau.com/views/AirDelays](https://public.tableau.com/views/AirDelays_0/StoryDelays?:embed=y&:display_count=yes&publish=yes)

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

# Resources
 [Bureau of Transportation Statistics](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp)

# TDI-Proposal
TDI Preliminary Data Analysis

Two data sets - Chicago Taxi and Chicago Rideshare

Taxi:
https://data.cityofchicago.org/Transportation/Taxi-Trips/wrvz-psew

Rideshare:
https://data.cityofchicago.org/Transportation/Transportation-Network-Providers-Trips/m6dm-c72p

The two datasets are disjoint - Taxi from 2013 to mid 2018, while the rideshare only has november and december of 2018

Ridhshare set is small enough to download and analyze locally. Taxi set is ~50gb, and must be done via api. Api calls are included in the R - run them in browser in order to download the reqiured data file, then rename it as indicated to load it into the script.

Can look at each individually, as well as combinations e.g. how has the decline of taxis affected rideshares? Where do taxis retain an advantage? Are ridshares most popular where taxis have declined?

Preliminary Results - Interesting behaviors with regards to airports (generally being more expensive / lucrative trips, even when accounting for trip time), an inverse relationship between number of trips and trip cost rate (e.g. cheapest to ride during rush hour, most expensive late at night or during lunch hours), and an increase in tipping behavior over time for taxis (possibly related to increased awareness due to ongoing debate about taxis and rideshares).

Future work could expand looking into changes in taxi or uber behavior by region (airport or otherwise), efficiency changes over time and region, as well as a better comparison of taxi vs uber data. This last would require a better way to deal with the taxi data via api - I am unfamiliar with this and was only able to set up a pretty basic workflow for this preliminary exploration. I would ideally like to compare taxi decline (over time, based on area, cost category, or other) vs current uber behavior.

Multiple exploratory figures generated in the script. The two chosen summaries are the cleaned up versions at the end of each section, which are also reproduced seperately in this project repository.




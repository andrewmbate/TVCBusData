# TVCBusData
Here we have data behind the figures and tables behind paper "A Quantitative Microbial Risk Assessment Approach to Estimate Exposure to SARS-CoV-2 on a Bus".

All csv files are either single simulation data or a summary of data 1000 simulation under default parameters, whereas all csv.xz are compressed csv files that contain all passengers data across many simulations.

Data for the total number of passengers onboard over time for different route and loading pairs.

Data around the selected single run is within .... for passengers and 

For figures around formite and close dose

With resepct to fixed VL are within ....FixedVL.

With respect to all route and loading results can be found within ... RouteLoad with different settings for "RouteFile".

With respect to the proportion of mask wearing, all simulations are within ...MaskFreq. This includes all percentages by increments of 10% from 0% to 100%. Although this is sometimes duplicated in other files, the default values are taken from this file for maskProp=30.

With respect to ventilation, all simulations are with ...ACH, which has different values of "fresh_flow" (where ACH=3600*fresh_flow/volume).

With respect to prevalence, on top of default,  Prev0p1 is from 10000 simulations with prevalence at 0.1%, Prev0p2 is 5000 simulations with prevalence 0.2%, Prev0p5 is 2000 simulations with prevalence 0.5%, and Prev2 and Prev5 is 1000 simulations with prevalence 2% and 5% prevalance, respectively. Minor note, all files have "prev" that are 10 times larger than in reality (i.e. 1% prevalance has "prev" of 0.1 and not 0.01), this is a superficial issue and prevalence values do not mix.

With respect to the results around mask types, the 50000 simulations with 75% masks, split equally between fabric, surgical and FFP2.  

With respect to handwashing, no-wash is default. ...Hand1000 contains simulations for both washing at boarding and alighting, ...Hand0100 contains simulations for washing at boarding only and ...Hand0010 contains simulations for washing at alighting only.

# TVCBusData
Here we have data behind the figures and tables behind paper "A Quantitative Microbial Risk Assessment Approach to Estimate Exposure to SARS-CoV-2 on a Bus".

All csv and xlsx files are either single simulation data or a summary of data 1000 simulation under default parameters, whereas all csv.xz are compressed csv files that contain all passengers data across many simulations.

Data for the total number of passengers onboard over time for different route and loading pairs.

Data around the selected single run is within SingleRun. This include calculatons for passenger seating and dose colour scaling, and a file for terminal surface values.

AggregMaskFreq contains passenger data under with varying levels of "maskProp" from 0% to 100% in increments of 10% (including default simulations of "maskProp"=30).

AggregFixedVL contains passenger data where viral load is fixed.

AggregRouteLoad contains passenger data for all six route and loading combinations (see different settings for "RouteFile" within AggregRouteLoad).

AggregACH contains ventilation results, where different values of "fresh_flow" is uses (where ACH=3600*fresh_flow/volume).

Prevalence is split across different files.  AggregPrev0p1, AggregPrev0p2, AggregPrev0p5, AggregPrev2 and AggregPrev5 are for prevalences of 0.1%, 0.2%, 0.5%, 2% and 5%, respectively (1% prevalence is default). A minor note, all files have "prev" that are 10 times larger than in reality (i.e. 1% prevalance has "prev" of 0.1 and not 0.01), this is a superficial issue and prevalence values between files do not mix.

The largest file, AggregMask75Run50000, is the data around different mask types, the 50000 simulations with 75% masks, split equally between fabric, surgical and FFP2.  

Handwashing is also spread over a few files. AggregHand1000 contains simulations for both washing at boarding and alighting, AggregHand0100 contains simulations for washing at boarding only and AggregHand0010 contains simulations for washing at alighting only.



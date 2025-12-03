# blue-bikes-electrification

Some initial exploration of historical Blue Bikes data around Boston.
* Currently using October 2025 data (not included in repo but available [here](https://s3.amazonaws.com/hubway-data/index.html))
* Stations locations data available [here](http://assets.ctfassets.net/p6ae3zqfb1e3/5YxN7XJodVcCCYXl2mKdbc/5e0cc33e96dcbcb4524fbd6f679f1c66/-External-_11.17.25_Bluebikes_Station_List.csv) but renamed to ```11.17.25_Bluebikes_Station_List.csv)``` in the repo

## Wish list / TODO
* Would be nice to understand where bikes are dying
* Would be nice to understand how long bikes are staying in docking stations-- data is not tied to a bike number, so the best we can do is approximate this with the sequence of rides assuming the bike taken out was the previous bike returned to the station, which is definitely a "worst-case" scenario
* The majority of e-bike rides seem to be "within the city" (within 4km of average station location), TODO: see how long bikes are staying at stations in the city vs how long they stay outside the city (e.g., is there enough time to actually charge?)
* TODO: Download census/income data and look at relationships with BB use
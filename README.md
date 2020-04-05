# Welcome in the covid-self-report project

It is a fork from [Switzerland](https://covid-self-report.ch/). We need to modify the backend and data model for Back Tracing functionality in phase 2 and 3. 

This app is hosted firebase.google.com. The analysis of the data is done on a local machine after getting the data from the database and then the results
are published to github. Then the frontend can use "github raw content" to make the most recent views.

- frontend: vue.js
- backend: serverless functions on firebase
- [analysis scripts](https://github.com/covidmap-sweden/analysis-scripts): python

## Data output

The analysed data are published to a repository by country ([example](https://github.com/covidmap-sweden/datasets)).


## Geocoding 

We need a geo locations file for post code for every targeted country.
One [repository](https://github.com/covidmap-sweden/geo-locations) is hosting all the geo-location data.


## Privacy Preserving Protocol
To trace contacted people, we use a privacy preserving protocol explained in [Traceing-protocol](https://github.com/covidmap-sweden/welcome/blob/master/Privacy%20preserving%20protocol.pdf).

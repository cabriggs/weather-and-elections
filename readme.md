## Files included

alaska_counties.csv: boroughs of Alaska with their FIPS codes
alaska_votes.csv: election data for Alaska boroughs
df_citydata.csv: data scraped from city-data.com
df_votes.csv: 2012 and 2016 election data, indexed by FIPS code
df_weather.csv: weather info for the (center of) each county (by FIPS code) on election days 2012 & 2016
votes\_by\_county\_2012_2016.csv: vote totals per county, broken down by DNC and GOP, 2012 and 2016
weather-and-elections.ipynb: a Jupyter notebook containing the analysis and narrative.

## Background

The objective in this project is to assemble data from disparate sources about the counties (and boroughs, parishes) in the US. This data consists of almanac data (e.g. population, median income, etc), election data from the 2012 and 2016 elections, and weather information for each county on the dates of those elections.

## Problem statement

Investigate some relationships between the data from the different sources.

## What data

We have a dataset of 3141 records showing almanac data about each county in the US, presidential election data for 2012 and 2016, and weather data on the dates of those elections. The data was gathered from city-data.com, wikipedia, meteostat, and kaggle (election data).

## What methods

The Kaggle data was downloaded. The city-data data was gathered using a custom-coded web scraped. This involved analyzing the html code of several pages, and designing the scraper accordingly. The weather data was gathered from Meteostat using their API.

### Technology

The analysis was performed in a Jupyter notebook, leveraging pandas, numpy, requests, and BeautifulSoup.

## What conclusions

There appears to be a relationship between declining home values and GOP shift from 2012 to 2016.

## What questions remain

What other interesting relationships between these data sets can be modeled?

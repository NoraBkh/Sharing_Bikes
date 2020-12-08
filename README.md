# Bike sharing demand

This project explains how we can go about explore and prepare data for model building. We try to predict the number of bikes rented per hour in the city.


###


## Installation


```bash
sudo apt-get install python python-pip

```

## Data

#### Overview

The dataset is taken from the kaggle Bike Sharing Demand competition:

* https://www.kaggle.com/c/bike-sharing-demand

It brings together a set of statements concerning a bicycle system shared (“Vélib” type).The goal is to predict the number of bikes rented per hour in the city (variable count). To simplify preprocessing, a dataset has been formatted and updated in the “bike_data.csv” file.

#### Data Fields


* __datetime__ - hourly date + timestamp
* __season__ - 1 = spring, 2 = summer, 3 = fall, 4 = winter
* __holiday__ - whether the day is considered a holiday
* __workingday__ - whether the day is neither a weekend nor holiday
* __weather__ -
    * 1: Clear, Few clouds, Partly cloudy, Partly cloudy
    * 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
    * 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
    * 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
* __temp__ - temperature in Celsius
* __atemp__ - "feels like" temperature in Celsius
* __humidity__ - relative humidity
* __windspeed__ - wind speed
* __count__ - number of total rentals (Dependent Variable)


## Requirements

The project was done in Jupyter Notebook, Python 3.
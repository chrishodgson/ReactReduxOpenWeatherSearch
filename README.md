# ReactReduxWeatherSearch

A simple search screen that displays 5 day weather forecasts from Open Weather Map with Temperature, Pressure and 
Humidity charts along with a Google Map of the location.

## Getting Started

Setup your API keys, checkout this repo, install dependencies, then start the webpack process with the following:

### Setup your Open Weather Map API Key

A default Open Weather Map API key is setup for this project. This should be changed by editing the `API_KEY` in `src/actions/index.js`.
You can register your own api key at the Open Weather Map site `https://openweathermap.org/api` 

### Setup your Google Maps API Key

A default Google Maps API key is setup for this project. This should be changed by editing the 
`script` tag pointing to `googleapis.com` in `index.html`. You can register your own api key at 
the Google Maps Platform site `https://cloud.google.com/maps-platform` 

### Installing

This assumes that `npm` is already installed. 

```
> git clone https://github.com/chrishodgson/ReactReduxWeatherSearch.git
> cd ReactReduxWeatherSearch
> npm install
> npm start
```


## Showing Weather Forecasts for a different country

By default, it will search for weather forecasts in the UK, but you can easily change this by editing the `COUNTRY_CODE` in `src/actions/index.js`.
You can find a list of the country codes at the Open Weather Map site by entering a city from that country  `https://openweathermap.org/city` 

# Weather Forecast
This is a weather forecast, which actually works by creating a model from training data and then forecasting weather data from this model. The file initialize_training_data.py is used to initialize the training data and save it in the data folder. The weather_foreacast.py file is used to generate the output data. Currently I have generated data for 12 places defined in forecast_locations.txt file. The generated data file name is forecast_weather_data.csv.

## Requirements
This application requires Python 2.7 and following python packages.

* pandas ( for DataFrames to load and save the data )

* sklearn ( for machine learning model creation like linear regression model, guassian naive bayes model )

* forcastio ( to download training weather data from forcast.io )

## Requirement Installation
If you don't want to install modules in your workspace, then use virtualenv like below

* sudo pip install virtualenv
* virtualenv ~/virtualenvironment/weather_cba
* cd ~/virtualenvironment/weather_cba/bin
* source activate
* Then install below modules

```bash
sudo pip install requests
sudo pip install pandas
sudo pip install sklearn
sudo pip install python-forcastio
sudo pip install scipy
```

Else

```bash
sudo pip install requests
sudo pip install pandas
sudo pip install sklearn
sudo pip install python-forcastio
sudo pip install scipy
```

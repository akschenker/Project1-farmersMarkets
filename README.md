# Farmers' Markets Across the US

This is a submission for Project 1 of the UC Berkeley Data Analytics bootcamp. For this assignment, we chose to investigate various aspects of farmers' markets in the US. Some examples include the prevalence of farmers' markets, whether there is a relationship between prevalence of farmers' markets in an area and income of that area, and the distribution of well-rated farmers' markets, as determined by Yelp. To accomplish this task, we obtained a public dataset of farmers' markets from the US Department of Agriculture, cleaned the dataset, then performed analysis and made graphs using Matplotlib and gmaps.

# Add results here


## Prerequisites

A `config.py` file with personal API keys for [Google](https://developers.google.com/places/web-service/intro), [US Census](https://www.census.gov/developers/), and [Yelp](https://www.yelp.com/developers/documentation/v3) must be included for the notebooks to run properly. The notebooks should be run in an Anaconda 3 environment.

The initial dataset, in CSV format, was obtained from the [US Department of Agriculture](https://catalog.data.gov/dataset/farmers-markets-geographic-data). To clean the data, run the Jupyter notebook entitled `Master Cleaning Notebook.ipynb`, followed by `Yelp_Ratings_Cleanup.ipynb`.

## Data Wrangling

We used the Pandas library in Python to clean the initial CSV file. Namely, our wrangling steps included the following:

* Querying the Google Geocoding API with latitude and longitude to find the nearest zipcode
* Merging the data with a list of US climate regions
* Removing duplicate entries of a farmers' market
* Merging the data with information from the US Census
* Merging the data with ratings from Yelp


## Built With

* Jupyter Notebook
* Pandas
* NumPy
* Requests
* Matplotlib Pyplot
* [gmaps for Jupyter Notebook](https://jupyter-gmaps.readthedocs.io/en/latest/)
* Census API
* Yelp API

## Authors

* Mehrun Nisha @mnisha4git
* Arley Schenker @akschenker
* Garima Sharma @garisharma23
* Cuong Tang @cuongtang11

<p align="center">
   <img src="banner.png" >
</p>

# AirBnB Seattle - Udacity Project

The following project has been created as part of the Udacity Data Science Nanodegree https://www.udacity.com/course/data-scientist-nanodegree--nd025

## Motivation:

It was done a analysis, in order to answer 3 key questions bellow.

- What are the neighborhoods with the best prices?

- What type of property has the best prices ?

- What to expect in terms of cleaning fee and how much it increases the price on average?

- When are high seasons and low seasons ?

## Libraries Used

Python Version: 3.8.5

- Pandas
- Matplotlib

## Files:

- seattle_airbnb.ipynb - Jupyter Notebook which contains the analysis.

Seattle folder contains:
- calendar.csv - Detailed Calendar Data for listings in Seattle
- listings.csv - Detailed Listings data for Seattle

This dataset and others can be found [here](http://insideairbnb.com/get-the-data.html)

## Results:

##### What are the neighborhoods with higher and lower prices ?

- Higher Prices
    * 1 - Pike-Market
    * 2 - Central Business District
    * 3 - Harrison / Denny-Blaine
    * 4 - Portage Bay
    * 5 - West Queen Anne
    
- Lower Prices
    * 1 - Olympic Hills
    * 2 - Meadowbrook
    * 3 - Highland Park
    * 4 - South Delridge
    * 5 - South Park
    
##### What type of property has the higher and lower prices ?
From the selected property types in the analysis:

- Higher Prices:
    * Serviced Apartment
    * Apartment
    * Loft
- Lower Prices:
    * Aparthotel
    * Guesthouse
    * Guest Suite

##### What to expect in terms of cleaning fee and how much it increases the price on average?

- The data show that the mean of means by property is nearly 39%

- Higher mean Cleaning fee was "condominium type" (50.49%)

- Lower mean Cleaning fee was "Aparthotel" (3.08%). However if i consider 'Aparthotel' an outlier, the second lower was 'Apartment' (35.29%)


##### When are high seasons and low seasons ?
- High season: June, July and August
- Low season: January, February and March

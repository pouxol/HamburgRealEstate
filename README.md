# HamburgRealEstate
Hamburg Appartement Market Data Analysis and Modelling

[Blog Post on Medium.com](https...)

## Project Motivation
As a long-time resident I have been watching the appartement market in Hamburg for a long time.
The prices are rising and its getting more and more difficult to find an appartement for a good price.
That is why I started to scrape data from one of the biggest real-estate websites in germany.
I want to use the data to find out what appropriate prices are and which appartements are overpriced.
In order to do this I want to create a model that predicts the price of an appartement based on the information that is available.

## File Descriptions
I have been scraping the data from https://www.immobilienscout24.de/ for a year now.
I scraped the search results for appartements for purchase in a 50 km radius around Hamburg.

Sometimes I scraped the data daily. Sometimes I paused for a few weeks.
The Data for each scraping is stored in an excel-file tagged with the date and time.

## Results
I analyzed the coefficients of the trained model to find out the impact of different features on the price of the appartements.

### Neighbourhood
The neighbourhoods **"HafenCity"**, **"Harvestehude"** and **"Uhlenhorts"** have the highest positive impact on the price.
The neighbourhoods **"Heimfeld"**, **"Moorrege"** and **"Langenbek"** have the highest negative impact on the price.

### Living Space and Number of Rooms
The **"living space"** has a positive Impact on the price.
The **"number of rooms"** has a negative Impact on the price.

### Private Offers
**"Private offers"** have a negative impact on the price.

### Other Factors
**"Balconies"** have a high positive impact on the price.
**"Built in Kitchens"** have a high negative impact on the price.
**"Floorplans"** have a negative impact on the price.
**"Gardens"** have a positive impact on the price.

## Licensing, Authors, Acknowledgements
I used the scraper from balzer82 [GitHub](http://insideairbnb.com/behind.html).

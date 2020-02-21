# Craigslist Filter
#### In Development...

Craigslist Filter (working title) is a web application built with python and flask which scrapes used car sales data weekly from all seperate craigslist sites in the United States and allows users to filter them by criteria such as (but not limited to) city, price, manufacturer, and odometer. This project is currently in development.

View the application [here](https://craigslist-filter.herokuapp.com/). (Due to infrequent use, you may need to refresh the page once or twice to allow time to connect to the RDS database)

You can also browse an older version of the dataset in CSV form [here](https://www.kaggle.com/austinreese/craigslist-carstrucks-data)

## Specific Future Implementations

* Allow users to specify a search radius and return more specific results when searching by location

* Add Google maps API feature to allow users to browse sales in specific areas

## Broad Future Implementations

* User-specific sale tracking (price has changed, listing has been removed, etc.)

## Blocked

* Pivot to multiprocessing to allow for many requests to be made at once, speeding up the scraper exponentially (I am worried about Craigslist blocking my EC2 IP)

## Completed Tasks

* Filter implemented.

* Improved filter form including dropdown lists automatically generated by column entries in the database

* Scraped the map on the listing page to extract more specific location (lat/long) instead of just the region

* Added a message that alerts a user when their search yields no results

* Allowed for filtering between two values for fields such as price and odometer

* Added photos to results page.

* Remain on the form page when a search yields no results

* Added back button on search page

* Allow for users to search by any city using latitude and longitude instead of specific craigslist regions

* Track which cities have been scraped recently to add order to the scraping process

* User-entered vehicle description has been added to the vehicles table, paving the road for in-depth machine learning.

* Frequent automated database updates

* App deployed

* Added sort by column


## Contributors

This application is being developed by Austin Reese.


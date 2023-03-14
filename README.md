# ChicagoYelpDivvyRealTimeWebApp

This is a web-based real-time application for Divvy bikers that will allow them to search and chart Yelp reviewed Chicago social places (restaurants, bars, coffee shops, etc) and plot real-time available docks in near-by Divvy docking stations on Chicago downtown area map.

The following is the list of technologies, platforms, and packages used in the design and development of this app.
  1. Angular 7
  2. Node.js/Express
  3. D3.js
  4. Google Maps(AGM)
  5. PostgreSQL – to store Divvys tations real-time status
  6. ElasticSearch – to store Yel previews for Chicago Businesses
  7. ElasticSearch – to create and store Divvy real-time logs and store Divvy trips anonymized data
  8. ChromebrowserthatiscompliantwithECMAScript2015scripting
  2015, (ES6)
   
For this project there are two data sources that we will use for our application:
  1. We will use Yelp business reviews (See Appendix A) to make recommendations for restaurants in Chicago downtown area that are highly reviewed and got at least 3-stars on Yelp.
    a. Here is the URL for Yelp API:
    https://www.yelp.com/developers/documentation/v3/get_started
    b. Here is the URL for businesses search:
    https://www.yelp.com/developers/documentation/v3/business_search
    c. Here is the URL for the supported search categories:
    https://www.yelp.com/developers/documentation/v3/all_category_list

  2. We will use Divvy real-time data (See Appendix B) about the status of their docking stations
    a. Here is the URL for the real-time data they publish:
    https://gbfs.divvybikes.com/gbfs/gbfs.json
    
    b. Here is the URL for the real-time status for the docking stations:
    https://gbfs.divvybikes.com/gbfs/en/station_status.json
    
    c. Here is the URL for the information for the docking stations:
    https://gbfs.divvybikes.com/gbfs/en/station_information.json
    
    d. Here is the URL for the anonymized data for Divvy trips:
    https://www.divvybikes.com/system-data

# **Travel**Bear
## Collaborators: [Wicked001](https://github.com/Wicked001) | [jbcurrie](https://github.com/jbcurrie) | [avish2](https://github.com/avish2) | [rbenjamin19](https://github.com/rbenjamin19)

# Video Walkthrough

<a href="https://youtu.be/uBOm1EeXC44" target="_blank"><img src="https://media.giphy.com/media/3ohhwlhbsiiKdSMLTO/giphy.gif" 
alt="IMAGE ALT TEXT HERE" width="480" height="266" border="10" /></a>


# [Demo the **Travel**Bear App](https://jbcurrie.github.io/Travel_Bear/.)


# [Slide Deck](https://docs.google.com/presentation/d/1BlEvGMfdMj3Wbv4HbrHxUS5TOzqtNJKRUVNHrONgdjM/edit?usp=sharing)

# Features
## Google Maps JavaScript API

* ### Google Places Autocomplete

   ![](https://media.giphy.com/media/3ohhwh0F4cRsMQ7wRy/giphy.gif)

   Google Place autocomplete provides a typeahead list of cities for users to choose. **Travel**Bear restricted  the search to the US. 

* ### Google Places API

   ![](https://media.giphy.com/media/3o7aCV3jZwDjcCrnXi/giphy.gif)
   
   **Travel**Bear uses the Places API to search for 'lodging' in the selected city, within a pre-determined radius. The resulting JSON data object is used to populate the map coordinates for nearby hotels in the city. 

## Other Third-Party APIs
* ### Zomato Food API
   ![](https://media.giphy.com/media/l378pDl4Yy8AH8R56/giphy.gif)

   The Zomato Food API typically returns the top 10 most popular restaurants in the selected city. The location details are passed to the Maps JavaScript API which places markers on the map for each point of interest. 

   Credit - Amey Shirsagar for the CORS compliant API SDK. [Zomato-js-sdk](https://github.com/ameykshirsagar/zomato-js-sdk)

* ### Eventful API

   ![](https://media.giphy.com/media/3ov9jZPTxbFZise2Sk/giphy.gif)

   The Eventful API searches for the top 10 popular events happening during the current week. The location details for the results are passed to the Maps JavaScript API. 

* ### Weather Underground API

   ![](https://i.imgur.com/Z8xOzoi.png)

   The Weather Underground API searches for weather conditions for the current month, and is used to provide a forecast, and information blurb. 

* ### Google Custom Search Engine

   <img src="https://i.imgur.com/DLsNZlf.png" 
alt="IMAGE ALT TEXT HERE" width="466" height="263" border="10" />

   Using Google's Custom Search Engine, **Travel**Bear displays an array of skyline images for the current city. 

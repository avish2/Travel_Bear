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

   ![](https://lh3.googleusercontent.com/jyVoKrQAoUtI15RgiXoRTn0dgBYqBxQXmFPOMc79oKjW1dS4J8XseyGmQD2weFFzCUZZh1CxvGXDb2NvoKHwbarOTdVLSBDH5y-bFYubsWaiO8vr04FlT5rFKf5YlM8Ef9tealdwu_VM8824-PMcTqocfUl-JKDf5Fesjf2t-sLoaEG-6KTRqjMa-PHVr5NGf75HDbW4F-DcV3Ey1LpPXic3fG0BJR_dW-zd9cLGkc0yy0JGjX4__7S_-MNt38mrlXUymhXHX_7i-Gx5ZjJYvhEufpcoNU5yFVW3vycNabF9ldRrM8AhJx-ooXdjCou7Oq6CkQrKDUNEja5ePaTQKBXOu-jTqSHk5grqKtZqG0LQD1ejEdjH8-zec19AmrtUAtI_BJqEUA-1gfamj_kVG4uVnpd5OuACdGjazTeJ5_AH8CHguVKNu5UpHvOZDk1kKVVJRoSoQhDOKJTcTM2ZesXF3B1k5HxlCC5b4zB9os9lIWlNT1R1s4lh3bWA7Zzrn-pBvzy-_bKOG37ZVQCq6_FX5Shj0jsAK-9QvlwKTJEp2_sj8dlQrxuEy2gMX5azIytXck8K4aMegAVDE7mAYF9nSgm-jwCAH7nY7YC5pLw=w815-h191-no)

   The Weather Underground API searches for weather conditions for the current month, and is used to provide a forecast, and information blurb. 

* ### Google Custom Search Engine

   <img src="https://lh3.googleusercontent.com/s_37UBTfaIGJbO9sUS8lQ0PBvkW7aFl4ZUwrJdmuv3vcSjMOMDvMjGSCap4GaErGS12V-EN-zevNi_TrcuPI2m3koiS8-ikicf_webPfEufGyxil1AxeIISkUdlGn39bXhXZbuw9Fol2xUNMD8E52iuMEqxOXD5nKRUy4I1BmHO9c0nnc2abE7ZdfoDDrZR7f0JK_64gielXwLQZChORtvPEezShxM3xylwN-rA1EUPD31mvC9P9VzhQPmv8GEc_DTFjPN49rSR3mNpl9QKvaMsXyhCKUVU0LE7drhU7h11jtenYahVYMXuXUI08vKMH4yMmzxOQlZsOG3JitOoVi0CI-mMj8faPmZHZK-sNuDrGXNkYmsRbizdPnU57YiLYmXtIIfNPoQMk4l0IvjtcS1nckaWDkNEbZ0lz3B9dlOiAT5qNz9fS1zTGM3-lugDCxXuo9nvlU4DsNdmMuwap_Sd6YX_gaFbzYVuSfbtFrjpzWaY7ech8bK_w9UoyqDgySmDZDrkk6aH2HVQKPikVYZsnlv97JNvq2Xt5S1gyErYUsAO5FpinFMEkxhAADp48sVndO-Mbqvs26hwyGOM4dOIhz0ufBR7uqseTBHCZ8Pc=w854-h483-no" 
alt="IMAGE ALT TEXT HERE" width="466" height="263" border="10" />

   Using Google's Custom Search Engine, **Travel**Bear displays an array of skyline images for the current city. 

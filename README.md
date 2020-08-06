# 
Webscraping on Spotify and Walmart
#
###
Walmart
###
#
Walmart Data:
#
https://www.walmart.com/search/?query=bath%20and%20body%20works%20body%20mist&cat_id=1085666&typeahead=bath%20and%20bod
#
Data was scraped from Walmart on female body spray using beautiful soup.  It was very difficult to retrieve 15 – 20 variables and I had to split the data to create variables.  For example, the product description gave the name of the fragrance, brand, and the ounces.  I removed the brand and created a variable named brand. Walmart does have a developer code, but it is used for vendors only.  Once tried to inspect the elements the data was hidden, and I had to right click on each item that I wanted to scrape to bring up the div tabs.   Most of the items are disallowed, but you can scrape some data.  I was successful in retrieving my 15 variables.

The information retrieved from Walmart can provide information on the types of body spray, cost, ratings, shipping cost, etc. It can give the store things to keep on the rack’s dependent on surveys, yet information would require further investigation such as revenues being generated in order to perform a thorough investigation of the products.  Weekly and monthly analysis should be performed depending upon the stores policy. 

###
Spotify
###
#
Items Required:
Before starting you should have two things done:
https://developer.spotify.com/

1.  Spotify API permissions & credentials that could apply in the next block of code. Simply log in, go to your “dashboard” and select “create client id”.
2.  Python module — spotipy — imported (you can download it using - "pip install spotipy")
#
The API will extract data of Coldplay Artist from Spotify to include 15 variables pertaining to various songs and albums most well-known songs being played on Spotify by the artist. Spotify requires API permissions & credentials that must be requested through their developer's code. The credentials are in the “dashboard” under select “create client id. Python module — spotipy — was imported and pip install Spotify had to be installed. Data was extracted from Coldplay’s song and another artist who may collaborated with him.  Fifteen variables pertaining to various songs and albums by this artist were created. I removed duplicates and perform cleaning.  At the end I decided to place a graph just to see which song was played most often. The API is JSON file and it provides most of the variable names. 

The data recovered from here furnished the music craftsman with data on the recurrence of their songs are being played, frequency, sound data and more. The artist will have the option to take the information to make new melodies dependent on their fans.  In the event artist just released an album, week after week to month to month investigation ought to be performed utilizing this code to monitor what is playing. This can help craftsman with improving music on the off chance that they recognize what individuals are tuning by this artist.




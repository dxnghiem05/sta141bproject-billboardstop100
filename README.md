# sta141bproject-billboardstop100

## How to get the Spotify API (need spotify premium account)
 here is the link to the site: https://developer.spotify.com/documentation/web-api
## STEPS
 1. get to this page, https://developer.spotify.com/dashboard, and click on create app
 2. the app name, app description, and website can be named whatever you feel like, but for Redirect URIs, we used http://127.0.0.1:8888/callback
 3. For the list of options at the bottom, you only need the Web API
 4. From there, you are done and it should give both a Client ID and Secret Client ID which you can then plug into
 client_id = "YOUR_SPOTIFY_CLIENT_ID"
 client_secret = "YOUR_SPOTIFY_CLIENT_SECRET"


## Billboard Hot 100 Song Analysis (2020 through 2025)
 This project examines how the characteristics of songs on the Billboard Year-End Hot 100 have changed between 2020 and 2025 using track information from Spotify.
 In particular, the analysis explores:
 - Whether average song duration has changed over time
 - Whether the proportion of explicit songs has increased
 - Whether collaborations between multiple artists have become more common

 For the data sources, we used two things:
 1. Wikipedia Billboard Year-End Top 100 (links are in the .ipynb file)
 2. Spotify API track metadata (the dataset is provided through the .csv file)

## About Coverage of major course topics:
- in order to comply with this, we ended up demonstrating three of the topics we have learned throughout this quarter:
1. Web Scraping (for getting data through wikipedia)
2. Visualizations (for all the  bar plots and other charts)
3. Pandas/Numpy (for data cleaning, parsing html, text processing and other small functions)
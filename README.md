# GoogleMapsAPI 

Google Maps API is a web app that that uses Javascript, Python, and references the google maps API. The app allows you to search google maps, and see current news stories (Yahoo News) for up to 10 cities within the users viewport.

This was my final assignment as part of the course "CS50" through edX. The project required a good understanding of JavaScript, Python, APIs, and documentation of various technologies, however I did not write all of the code for the assignment. 

The course implementation of the app can be viewed <a href="http://mashup.cs50.net/">HERE</a>, whith my end result being mroe or less identical. 


<strong><h2>Information</h2></strong>


<strong>application</strong>

Launches the Flask App. Application directs the flow of information among the database, api, and the end user. 

<strong>helpers</strong>

Contains additional functions to lookup relevant articles.

<strong>mashup.db</strong>

SQLlite database that was used for the project. 

<strong>US.txt</strong>

Text file of US cities, states, and zip codes to be loaded into the database. Allowed user to search for any US city, zip code, or state
and return articles from their desired location.

<strong>script.js</strong>

Page with all JavaScript. Get and display additional information on users screen.

your celebrity match

![alt tag](http://vignette3.wikia.nocookie.net/fantendo/images/c/c4/Project_Universal_Mario.png/revision/latest?cb=20130726165045)

The application uses IBM Watson Personality Insights and Twitter to find the celebrities that are similar to your personality. Twitter is being use to get the tweets for a given handler, the text from those tweets is send to Personality Insights, who analyze the text and reply with a personality profile. That profile is compared to celebrity profiles to find the most similar.

Live demo: http://your-celebrity-match.mybluemix.net/

Give it a try! Click the button below to fork into IBM DevOps Services and deploy your own copy of this application on Bluemix.
Deploy to Bluemix
Note: Once you deploy the application in Bluemix you will need to do some extra steps described below to setup the database and Twitter API credentials.

API Reference:

The application uses The Personality Insights API

How it works

Steps
You input your Twitter handle
You input your Twitter handle.
Calls the Twitter API.
Calls the Twitter API to get the latest 2300 tweets from your public feed.
Calls the Personality Insights API.
Calls the Personality Insights API to analyze the language in your tweets and apply it to a spectrum of characteristics.
Compares your Personality Insights profile to 232 celebrity profiles analyzed with the service.
Compares your Personality Insights profile to 232 celebrity profiles analyzed with the service.
Sorts your matches and shows you the highest and lowest. These are calculated by the euclidean distance between the two.
Sorts your matches and shows you the highest and lowest. These are calculated by the euclidean distance between the two.
![Alt text](http://vignette3.wikia.nocookie.net/fantendo/images/c/c4/Project_Universal_Mario.png/revision/latest?cb=20130726165045 "Optional title")

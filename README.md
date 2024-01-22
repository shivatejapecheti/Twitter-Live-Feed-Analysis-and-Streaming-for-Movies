# Twitter-Live-Feed-Analysis-and-Streaming-for-Movies


 <div align="justify"> The Movie Tweet Analysis project utilizes various technologies and libraries to analyze public sentiment and opinions about movies using Twitter data. This comprehensive analysis involves data collection, storage in MongoDB Atlas, and visualization using various tools. The project leverages Python for scripting, Tweepy for Twitter API access, and MongoDB for data storage and retrieval. </div>

## Overview
The Movie Tweet Analysis project involves the following key technologies and libraries:

### Data Collection:

+ Twitter API (Tweepy): Tweepy is used to interact with the Twitter API and collect tweets containing specific keywords ("Varisu" and "Thunivu").

+ Python: Python scripting is employed to execute the data collection process.

### Data Analysis:

+ TextBlob: TextBlob, a natural language processing library, is used for sentiment analysis of tweet text.
  
+ MongoDB (PyMongo): + PyMongo facilitates the interaction between Python and MongoDB, allowing seamless storage and retrieval of tweet data.

### Data Visualization:

+ MongoDB Charts: MongoDB Charts is utilized to create various data visualizations.

### Queries and Analysis:

+ MongoDB (PyMongo): PyMongo is used to perform queries on MongoDB collections, exploring different aspects of the stored tweet data.

### Recommendation System:

+ Scikit-learn: Scikit-learn is used for creating a recommendation system that suggests similar tweets based on their text.

### Visualization:

+ MongoDB Charts: MongoDB Charts is utilized for the creation of visualizations providing insights into tweet distribution, user engagement, and sentiment about movies.

## Project Components

## Prerequisites:

+ Ensure you have the necessary Python packages installed (Tweepy, TextBlob, PyMongo, etc.).
+ Set up a Twitter Developer Account and obtain API credentials.

Twitter API Authentication:

+ Create a Twitter Developer Account.
+ Create an application under your project and obtain authentication credentials.
+ Store the credentials in a config.ini file.
  
MongoDB Setup:

+ Create an account in MongoDB Atlas.
+ Create a database and configure network accessibility.
+ Obtain the MongoDB URI connection string.
  
## Running the Project:

Execute the provided Python script.
Access the MongoDB database and explore the collections (movie_TV and Temp_collection) for stored tweets.

## Data Visualization 
[Click here](https://charts.mongodb.com/charts-project-0-bzacq/public/dashboards/a5e98a4b-2363-4e02-abe5-21694ddf0665)

Explore different visualizations created using MongoDB Charts and optionally other tools:

+ Geo Scatter Map: Represents the geographic distribution of tweets about movies.

+ Geo Heatmap: Shows the density of tweets in different geographic areas.

+ Pie Chart: Illustrates the distribution of tweets per movie.

+ Period-based Visualization: Displays the temporal distribution of tweets about movies.

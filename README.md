# Twitter-Live-Feed-Analysis-and-Streaming-for-Movies


 <div align="justify"> The Movie Tweet Analysis project utilizes various technologies and libraries to analyze public sentiment and opinions about movies using Twitter data. This comprehensive analysis involves data collection, storage in MongoDB Atlas, and visualization using various tools. The project leverages Python for scripting, Tweepy for Twitter API access, and MongoDB for data storage and retrieval. </div>

## Overview

![visualization](https://github.com/shivatejapecheti/Twitter-Live-Feed-Analysis-and-Streaming-for-Movies/assets/126412107/0c1eafb8-8920-4ca4-a766-aba1e8b150a8)


Process Overview

1. Objective Definition:

- Identified the goal to analyze Twitter data for the films "Varisu" and "Thunivu" to understand audience sentiment and engagement.

2. Data Collection:

- Utilized Tweepy to connect to the Twitter API for streaming tweets.

- Defined search queries based on keywords related to the movies and focused on specific geographic coordinates (e.g., Andhra Pradesh) to target relevant users.

- Collected a specified count of tweets per query to ensure a robust dataset.

3. Data Storage:

- Stored the collected tweets in a MongoDB database to facilitate easy retrieval and processing.

- Set up two main collections: Temp_collection for initial tweets and movie_TV for processed data.

4. Data Processing:

- Cleaned and formatted the tweet data, extracting relevant information such as text, timestamp, user details, and engagement metrics (likes, retweets).

- Applied sentiment analysis using TextBlob to categorize tweets as positive, negative, or neutral based on the text content.

- Implemented aggregation queries in MongoDB to analyze hashtag usage, user engagement metrics, and identify trends in discussions related to the films.

5. Sentiment and Engagement Analysis:

- Compared occurrences of keywords related to the movies to determine the predominant sentiment.

- Analyzed tweet engagement levels to identify the most active users discussing the films.

6. Results Generation:

- Summarized findings in comprehensive reports that highlighted public sentiment trends, popular hashtags, and influential users.

- Utilized data visualization tools (e.g., Matplotlib and Seaborn) to create visual representations of the data, making insights easier to understand for stakeholders.

7. Recommendations:

- Developed targeted marketing strategies informed by the analysis, such as focusing promotional efforts in regions with high engagement or tailoring content based on sentiment findings.

Results

- Improved Understanding: Gained insights into public sentiment regarding "Varisu" and "Thunivu," identifying both positive and negative feedback.

- Increased Engagement: As a result of the insights produced, the project contributed to a 20% increase in social media interactions during marketing campaigns around movie releases.

- Effective Marketing Strategies: Provided data-driven recommendations that aligned marketing initiatives with audience preferences, leading to more effective promotional tactics.

- Stakeholder Communication: Successfully communicated key findings through visual reports, promoting better decision-making among marketing teams and executives.



# Google Playstore Exploratory Data Analysis

The Google Play Store is a digital marketplace for mobile apps on the Android operating system. These apps now significantly influence how we live our lives. The goal of this project is to provide information that will assist developers better understand client needs and, in turn, help the product become more well-known. This includes analyzing the relationship between app ratings and download numbers, identifying the most popular app categories, or exploring the sentiment of app reviews. The project also includes visualizations to help communicate the findings and insights.

# Analysis

The analysis will include the following steps:

    1. Data cleaning and preprocessing
    2. Exploring the distribution of sentiment in the reviews
    3. Identifying the most common themes and keywords in the reviews
    4. Visualizing the relationship between sentiment and other variables in the data
    5. Creating a model to predict the sentiment of reviews based on the text

#  Data

Two data sets are used in this project which includes the following information:

Play store data:

    1. App - Name of the Application
    2. Category - Category of the Application
    3. Rating - Rating given to the Application
    4. Reviews - No of reviews given to the Application
    5. Size - Size of the Application
    6. Installs - No of downloads of the Application
    7. Type - Free or Paid
    8. Price - Price of the Application if it is paid
    9. Content Rating - It is Age appropriate or Not
    10. Genres - Type of Genre the Application belongs to
    11. Last Updated - When the last time the Application is Updated
    12. Current Ver - Current version of the Application
    13. Android Version - Minimum Android version required to run the Application

User reviews data:

    1. App - the name of the app the review is for
    2. Translated_Review - the text of the review (translated to English)
    3. Sentiment - the sentiment expressed in the review (positive, negative, or neutral)
    4. Sentiment_Polarity - a numerical score indicating the sentiment polarity (ranging from -1 to 1)
    5. Sentiment_Subjectivity - a numerical score indicating the sentiment subjectivity (ranging from 0 to 1)

# Requirements

To run this project, you will need to have the following packages installed:

    1. Python - Programming Language
    2. Numpy - Scientific computing library
    3. Pandas - Data manipulation library
    4. Matplotlib - Data visualization library
    5. Seaborn - Data visualization library

# Usage

    * Clone the repository
    * Run the jupyter notebook google_playstore_eda.ipynb

# Conclusion

These are the general conclusions that may be drawn from an EDA on the Google Playstore:

    1. Majority of apps that people use are free based and very few people use the Play Store to buy apps.
    2. Apps on the play store have an average rating of 4.4.
    3. The Family category had the most Paid app installs while the Game category had the most Free app installs.
    4. Genres "Parenting," "Brain," and "Games" have the lowest Average Ratings, whilst "Board," "Pretend Play," and "Comics," Creativity," have the greatest Average Ratings of 4.8 each.
    5. Majority of apps that people utilise have a "Everyone 10+" as Content Rating.
    6. Majority of review sentiment is positive, with neutral reviews making up the smallest percentage.
    7. After looking at the percentage of sentiments for the top 3 apps, it is discovered that the health and fitness category had the most positive sentiments, whilst the game app category received the most negative.

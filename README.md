# Google_PlayStore_Analysis--Python

# Introduction

Google Play Store or formerly Android Market, is a digital distribution service developed and operated by Google. It is an official apps store that provides variety content such as apps, books, magazines, music, movies and television programs. It serves an as platform to allow users with 'Google certified' Android operating system devices to donwload applications developed and published on the platform either with a charge or free of cost. With the rapidly growth of Android devices and apps, it would be interesting to perform data analysis on the data to obtain valuable insights.

The dataset that is going to be used is 'Google Play Store Apps' from Kaggle. It contains 10k of web scraped Play Store apps data for analysing the Android market. The tools that are going to be used for this EDA would be numpy, pandas, matplotlib and seaborn

# Problem statement. 

1) Today, 1.85 million different apps are available for users to download. 
2) Android users have even more from which to choose, with 2.56 million 
    available through the Google Play Store. 
3) These apps have come to play a huge role in the way we live our lives today. 
4) Our Objective is to find the Most Popular Category, find the App with largest number
    of installs , the App with largest size etc.


 # Feature Information

     App :- Name of the App.
     
     Category :- Category under which the App falls.
     
     Rating :- Application's rating on playstore.
     
     Reviews :- Number of reviews of the App.
     
     Size :- Size of the App.
     
     Install :- Number of Installs of the App.
     
     Type :- If the App is free/paid.
     
     Price :- Price of the app (0 if it is Free).
     
     Content Rating :- Appropiate Target Audience of the App.
     
     Genres:- Genre under which the App falls.
     
     Last Updated :- Date when the App was last updated.
     
     Current Ver :- Current Version of the Application.
     
     Android Ver :- Minimum Android Version required to run the App.
 

# Data Preparation and Cleaning

In this section, we will be loading the Google Store Apps data stored in csv using pandas which is a fast and powerful python library for data analysis and easy data manipulation in pandas DataFrame object. It is usually used for working with tabular data (e.g data in spreadsheet) in various formats such as CSV, Excel spreadsheets, HTML tables, JSON etc. We will then perform some data preparation and also cleaning on it.

# Insights 

Rating and Year is left skewed while Reviews, Size, Installs and Price are right skewed. Most of the apps are free in playstore.

The apps Content Rating indicates that it is suitable for all audiences and mostly targeted to everyone.

The most popular top 3 categories in the playstore are Family , Game ,  Tools.

Beatuty,comics,arts and weather kinds of apps are very less in playstore.

Family category has the most number of apps with 18.75% , followed by Games category which has 10.83% of the apps.

Least number of apps belong to the Beauty category with less than 1% of the total apps belonging to it.

Out of all the categories "GAME" has the most number of Installations. 

With almost 35 Billion Installations GAME is the most popular Category in Google App store.

Top 5 apps highest installed for category Game are Subway Surfers , Temple Run 2 , Candy Crush Saga , Pou , My Talking Tom.

Most popular for game is Subway Surfers ,for communication app is Hangouts , for productivity app is Google Drive ,for social app is Instagram.

There are 271 rows where Rating is 5.0 apps on Google Play store.

There are 50 installations for app 'CricQuick' from 'SPORTS' Category.

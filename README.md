# Playstore_DateDrigger
Play Store App Review Analysis - analysis by DataDigger

Reasons for Analysis

1.The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market

2.Taking into account billion of Android users worldwide, mining this data has the potential to reveal user behaviors and trends in the whole global scope. This dataset is obtained from scraping Google Play Store.

3.Explore and analyze the data to discover key factors responsible for app engagement and success.

Each app (row) has values for catergory, rating, size, and more. Another dataset contains customer reviews of the android apps.

![](playstore_logo.webp)

## Data provided by : 

Almabetter

The playstore-analysis by using Python libraries.

### Main Dataset Features
•	App: the app name.

•	Category: a categorical label, which describes which broad category the app belongs to.

•	Rating: a continuous variable with a range from 0.0 to 5.0, which describes the average rating the app has received from the users.

•	Reviews: a continuous variable describing the number of reviews that the app received.

•	Size: the size of the app. The suffix M is used for megabytes, while the suffix K is used for kilobytes.

•	Installs: a categorical label that describes the number of installs.

•	Type: a label that indicates whether the app is free or paid.

•	Price: the price value for the paid apps.

•	Content Rating: a categorical rating that indicates the age group for which the app is suitable.

•	Genre: a semicolon-separated list of genres to which the app belongs.

•	Last Update: the date the app was last updated.

•	Current Version: the current version of the app as specified by the developers.

•	Android Version: the Android operating system the app is compatible with.



### Reviews Dataset Features
•	App: the app name.

•	Translated_Review: the review text in English.

•	Sentiment: the sentiment of the review, which can be positive, neutral, or negative.

•	Sentiment_Polarity: the sentiment in numerical form, ranging from -1.00 to 1.00.

•	Sentiment_Subjectivity: a measure of the expression of opinions, evaluations, feelings, and speculations.



# ![image](https://user-images.githubusercontent.com/55895912/181234425-6fa1739e-38d4-41fb-830c-68864bd5e840.png)

### Summery :

1.Popular category vs Type count 

2.Popular category vs sentiment (positive ,negative ,natural count )

3.Content rating (user's ages) vs them feedback positive ,negative or natural 

4.App price trend across categories ,

5.Total sentiment count from whole database 

6.App's size histogram for which size apps are more available in playstore 

7.User's age (content rating) vs available free and paid apps count 

8.Content rating ratio across the database 

9.How much apps are update in year

10.Ratio of free and paid apps 

11.Find % of nan value in type column using chart 

12.Most frequent ratings of apps

13.Top genres on playstore 

14.Top categories on playstore

15.Corrention chart to understand data responce with other data 

16.% of adroid version supports apps across the database


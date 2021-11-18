# Trending-YouTube-Videos-EDA
Exploratory Data Analysis (EDA) on Trending YouTube Videos in the United States.
![youtube](https://user-images.githubusercontent.com/47735276/142191843-23ded5e2-b55a-42e9-81ce-44a4690d2242.jpeg)

## •	Data Description:
The dataset’s purpose is to display a list of trending videos on youtube platforms (US) from 2017 till 2018 ,  measured by user interaction like number of views, shares, comments and likes and a size of 40950 row and 16 columns 

by youtube API. The dataset’s Attributes are 16 (video_id,trending_date, title, channel_title, category_id, publish_time, tags, views, likes, dislikes, comment_count, thumbnail_link, comments_disabled, ratings_disabled, video_error_or_removed, description), Category_Id as mention in details :

 1: Film & Animation. 10: Music.
15: Pets & Animals. 17: Sports.
19: Travel & Events. 2: Autos & Vehicles. 20: Gaming.
22: People & Blogs.
23: Comedy.
24: Entertainment.
25: News & Politics.
26: Howto & Style.
27: Education.
28:Science & Technology. 29:Nonprofits & Activism. 43: Shows.

# •	Question/Problem statement:
o	The objective is to study the behavior of the US (united states)  YouTube users, Figure out if some conditions effect (views or likes) generally other attributes.

## • Data cleaning
The preprocessing helps to get a clean dataset, such as removing rows or columns, and adding new features.
Droping rows, first, drop rows with Null value. Second, drop rows with duplicates values. Third, drop rows that contain videos with error, videos with disapplied comments and videos which don't allow rating.
I transformed the number of days to the name of the day, then the code which shows distribution of the number of views on each day.


## • Outliers:
An outlier is an observation that lies an abnormal distance from other values in a random sample from a population. In a sense, this definition leaves it up to the analyst to decide what will be considered abnormal. Before abnormal observations can be singled out, it is necessary to characterize normal observations.
This step was done after visulization.



## • Data visulization 

The figure below shows the a bar chart of the most watched category youtube users in the united states of america.
It answers my qustion about what is the most watched categories.
![2](https://user-images.githubusercontent.com/47735276/142196434-57c5a4de-1e7d-4b7d-addb-c65304d6dfef.jpg)


The below figure shows the highset views on each day of the week.
It answers whats the highest number of views for the weekdays. 
![3](https://user-images.githubusercontent.com/47735276/142196586-d65ad7e1-4bf1-4b9c-b615-686f4effe44b.jpg)

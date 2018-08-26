# youtube_project

## Summary ##

This project is an exploration of YouTube trending videos to examine some of the factors that impact whether a video trends. The data included a list of daily trending videos in the United States from November 2017 through June 2018. Here is a link to the dataset which we found on Kaggle.

https://www.kaggle.com/datasnaek/youtube-new

## Data Cleaning ##


https://docs.google.com/presentation/d/1Zz3tMyjvQufpL28Xpg46TWHZx77IytMGPCK1t1HwYm8/edit

We used Python libraries pandas and Matplotlib to examine a number of questions broken down by video categories including: total views, average views, likes and dislikes, and sentiment by category.

## Findings ##

**Does video category impact the number of trending videos and average views?**

    1. There is significant variation in the number of trending videos per category. The Entertainment category had over 25% of all the trending videos in our sample. S number of categories had no videos, and some categories such as Shows and Nonprofits/Activism had very few trending videos videos.

    2. Out of categories with a larger sample, Music videos had the most average views per video, followed by Gaming.

    3. Music and Gaming also had the highest number of comments per video on average which suggests that these categories drive higher engagement.

**Does video category impact how long a video takes to trend and how long it trends for?**

    1. Shows and Nonprofits/Activism had the shortest average time to trending, but they had very small samples. Travel & Events, Howto & Style, and Pets & Animals had the fastest time to trending among larger sample size categories. On the other hand, Autos and Film & Animation took the longest amount of days to trend on average.

    2. Music and Gaming stayed trending for the longest number of days, whereas Sports and News/Politics trended for the shortest number of days.

**Is there variation in how many views each category receives per month?**

    1. There is variation in how many views some categories received by month. Some categories, such as Education and Pets were relatively stable, whereas others such as People/Blogs and Film/Animation had wide variations in views over the 6 months. The sample for some of these categories was fairly low so the data needs a larger sample. Certain categories may be impacted by events such as The Oscars.

**Does the percentage of likes and dislikes vary by category?**

    1. Comedy and Education had the highest percentage of likes whereas News/Politics and Autos/Vehicles had the lowest percentage of likes.

    2. Gaming had the highest percentage of dislikes, while Autos/Vehicles had the lowest percentage of dislikes.

**Is video description sentiment positive on average? Does it vary by category?**

    1. On average, video descriptions have a positive sentiment.

    2. There were categories that showed a lower average sentiment, including News/Politics and Music. Education and Howto/Style showed the highest average description sentiment.


## EDA On My Favorite Youtube Data Science Channels From Youtube API




### Introduction
In my journey to study data science and artificial intelligence, next to academic studies and MOOC courses, one of my favorite sources of knowledge and learning is YouTube. You can find dozens of dedicated channels dealing with programming, statistics, data science, artificial intelligence, and more.

For me, these channels are very effective in my learning process because, among others, you can find diverse and high-quality content that cannot always be found elsewhere. The videos are often short, simplify complex ideas, introduce the latest tools and techniques, and provide samples of projects.

As such, I decided to leverage this wealth of data to undertake a data analysis project that would apply the knowledge I had gained. I chose to work with the data from videos across the channels that had contributed significantly to my learning experience.

### About the Dataset
* I created this dataset myself using Google Youtube Data API version 3.0:  https://developers.google.com/youtube/v3
* I chose my **Top 20** favorite YouTube channels for this project.
* The data set is divided into 2 data frames:
	* **"channel_data"** contains general information about each channel
	* **"video_df"** contains information about each video on each channel

### My chosen top 20 channels
* Tech With Tim
* Rob Mulla
* Patrick Loeber
* Data Professor
* Krish Naik
* Ken Jee
* Keith Galli
* Derek Banas
* Codebasics
* Alex The Analyst
* Statquest
* Corey Schafer
* Shashank Kalanithi
* AssemblyAI
* Thu Vu data analytics
* Aladdin Persson
* Greg Hogg
* Sentdex
* Tina Huang
* Luke Barousse



### Tasks
* **Creating the dataset from the YouTube API**
* **Data cleaning (NULL/missing values, duplicate rows, etc.)** 
* **Enriching the data for further analyses by creating new columns from existing columns**
* **Analyzing Channels data**
* **Analyzing videos data:**
	* Does the number of likes and comments matter for a video to get more views?
	* Does the video duration matter for views and interaction (likes/ comments)?
	* Does title length matter for views?
	* Which day of the week are most videos uploaded?
	* Which month in the year are most videos uploaded?


### Conclusions
* There is a large variation in views/subscribers per channel.  There is a direct correlation between the number of subscribers and the total number of views on the channel which is expected.


* The more likes and comments a video has, the more views the video gets (it is not guaranteed that this is a causal relationship, it is simply a correlation and can work both ways). Likes seem to be a better indicator of interaction than comments. The number of likes seems to follow "social proof", which means the more views the video has, the more people will like it.


* Most-viewed videos have 30-70 characters in the average title length. Too short or too long titles seem to harm viewership.

* Most-viewed videos are between 5 to 15 minutes, and short videos tend to be more popular which makes sense nowadays when we lose patience and attention over time.

* Videos are usually uploaded on Mondays and Fridays. Sundays in particular are not a popular time for posting new videos.

* Most videos are uploaded in the first quarter of the year, while fewer videos are uploaded during the summer and at Christmas time.

### Project limitations
* In this project, I chose my 20 favorite pages, but they are not necessarily the most popular channels in this domain on YouTube.

* The number of videos is quite small (the dataset has only ~8500 videos)

* There are many other factors that were not taken into analysis, including the marketing strategy of the creators and many random effects that will affect the degree of success of the video.



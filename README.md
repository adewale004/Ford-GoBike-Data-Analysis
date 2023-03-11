# Ford GoBike Data Analysis
## by Adewale Olayemi


## Dataset
The dataset used for this project consist of 519700 bike trips made between June 2017 to December 2017. The dataset was provided by Ford GoBike, a bike sharing system covering the greater San Francisco Bay area. Some of the variables in the dataset includes trip duration, user type, start and end station, user gender, etc. I performed data wrangling on the dataset like assessing the data, changing data type, removing missing values, etc. The dataset can be downloaded [here](https://www.kaggle.com/datasets/franckjay/ford-gobike-data?resource=download)


## Summary of Findings

During the data exploration, I found out that most of the trip duration were between one (1) minutes to twenty (20) minutes, though, there are some trips above 100 minutes, even up to 1000 minutes. Also, most of the users are youth between the age of 18 to 40 years old. We also have more trips during the day (Morning and Afternoon) and less trip in the night.

Most users tend to start/end their trip at stations located at a train station (Caltrain station) and Ferry terminal. I also discovered that subscribers made more bike trip than customers, but customers spent more time riding bike than subscribers. This same pattern was observered when I considered gender effect on bike trips; there were more male riders, but female spent more time riding bike.

When considering the date/time factor, users made  more bike ride during the weekdays (Monday to Friday) than weekend (Saturday and Sunday). The number of bike trips increased gradually from June to October, and then reduced from October to December. Users also spent longer duration  on their bike trip on Saturday and Sunday.


## Key Insights for Presentation
For the presentation, I focus on the effect of bike trip on user type and days of the week. I start by showing the distribution of users age using histogram plot. I then introduce the number of bike trips made by different user type (Subscribers and Customers). I use barplot to show which user spend more time riding bike.
Aftewards, I use seaborn countplot to determine the bike trip distribution within 7 days of the week, and the lineplot to show the average trip duration.

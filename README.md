# Crochet youtube channels analysis

## Idea
In 2018 I started crochet and then had small brand of knitted decor. However, with the relocation, I realized that the cost of materials here is much higher and due to the large number of orders, my hands began to hurt. I decided to try to open my channel with knitting on YouTube to share my skills, patterns and designs and to have money for it (monetization + sell patterns). I decided to analyze channels and videos on this topic.

Within this project, I would like to explore the following:

- Getting to know Youtube API and how to obtain video data (Because I learn on Data Analytics Track).
- Analyzing video data and have recommendations for my Youtube channel, for example:
   Does the number of likes and comments matter for a video to get more views?
   Does the video duration matter for views and interaction (likes/ comments)?
   Does title length matter for views?
- How many tags do good performing videos have? What are the common tags among these videos?
- Across all the creators I take into consideration, how often do they upload new videos? On which days in the week?
- Explore the trending topics using NLP techniques, which popular topics are being covered in the videos (e. g. using wordcloud for video titles)?

## Steps of the project:
1) Finding popular Youtube channels about crocheting. 
1) Obtain video data via Youtube API for the top channels in the knitting niche (this includes several small steps: create a developer key, request data and transform the responses into a usable data format).
2) Data preprocessing and feature enginering for analysis.
3) Exploratory data analysis.
4) Conclusions.

## Techniques in this project:
1) Work with API. 
2) Data cleaning, feature engineering,  work with Timedata. 
3) Visualisation liblraries: matplotlib, seaborn. 

## Data
I didn't find any data for analysis because theme is not so popular. So I desided scrap data. 
Separate file for data scrapping and [final dataset](https://github.com/DanaFilipovich/Crochet-youtube-channels-EDA/blob/92d9e85e737146743030457551599335c01fe3cc/video_data_14channels_crochet.csv) are in reposintary and by the link.
Feel free using my dataset for educational ways.

## Challenges
1) Scrap the data. 
2) Find solution for Wordcloud (and whole NLP part). 
3) Demonstrate distribution of views for all channels. 

## Ideas for future research
* Make an categorization of videos such tutorials, yarn and hooks, life-hacks and compare theirs popularity;
* Does YouTube promote those who post regularly or does it depend on the specific video? (Is there a channel karma.)
* Expand the dataset to also smaller channels in this niche;
* Do market research by analyzing questions in the comment threads and identifying common questions/ market gaps which could potentially filled;
* According to the analysis and additional research, predict approximate monetization.

## References
[1] Youtube API [official documentation](https://developers.google.com/youtube/v3?hl=ru)

[2] Youtube Channel ID search service [by the link](https://commentpicker.com/youtube-channel-id.php)

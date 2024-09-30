# "Hmmm": A Deep Dive into Fan Engagement

### Dashboard Link : Download Dashboard [here](https://github.com/Isioma-Clement/-Hmmm-A-Deep-Dive-into-Fan-Engagement/blob/main/'Hmmm'%20Comment%20Analysis%20Dashboard.pbix)

## Project Background

On June 5, 2024, Chris Brown released the music video of his song titled "Hmmm" in collaboration with Davido, an afrobeat music artist.
The video quickly gained popularity, surpassing 1 million views within two days and accumulating over 16 million views on YouTube and 51.9 million associated TikTok posts.

This project thoroughly analyses how fans engaged with the music video following its release on the YouTube streaming platform by looking at the key metrics such as Likes and comments.

Insights are provided on the following key areas: 

- **Likes and Comments Volume:** Illustrates the total number of comments, replies, and likes to assess overall engagement. 

- **Like-to-Comment Ratio:** Evaluates the ratio of likes to comments to understand the level of positive feedback.

- **Reply Rates:** Analyses comment reply rates by weekdays and specific days.

- **Music Style Preferences:** Analyses which music styles, including Afro Beat and Amapiano, are most discussed.

- **Viewer Interactions:** Identifies streamers with multiple comments, indicating higher engagement.

- **Peak Engagement Times:**  Assesses the times of day or days of the week when comment activity is highest.

- **Comment Trends:** Analyzes comment activity over time to identify any patterns or trends.

The interactive Dashboard can be downloaded [here](https://github.com/Isioma-Clement/-Hmmm-A-Deep-Dive-into-Fan-Engagement/blob/main/'Hmmm'%20Comment%20Analysis%20Dashboard.pbix)



## Data Source, Transformation & Model

The data was extracted from YouTube comments using the YouTube Data API v3 and Google Apps Script. This dataset consisted 18,190 rows which included columns such as user IDs, likes, comments, replies, published dates, and timestamps. 
The dataset was structured in a tabular format, making it suitable for further analysis and visualization.


#### Data Transformation

The data transformation included the following:

- **Column Renaming:** Renaming of some columns such as Name to UserID

- **Additional columns:** Creating of additional columns by splitting the timestamp columns into separate date and time columns

- **Data Type Formatting:** Ensuring the formatting of columns to the appropriate data types





#### Data Model

The Data model consists of 2 tables: 

**Fact Table:** The original YouTube comment dataset (18k+ records), containing columns such as UserIdentifier, Likes, Comments, Replies, Date, and Time.

**Date Table:** A separate date table was created to facilitate temporal analysis. This date table was then linked to the fact table (the original YouTube comment dataset) to create a one to many relationship in the data model.



![Screenshot 2024-09-30 195730](https://github.com/user-attachments/assets/926ba0ce-edaa-4237-8dfd-38d5525debfd)




## Executive Summary

### Overview of Findings

The music video "Hmmm" by Chris Brown and Davido experienced a significant surge in initial engagement, with a peak of 5,610 comments and 61,025 likes on the premiere date. However, engagement rapidly declined, dropping to just over 2,800 comments and 12,000 likes within 2 days. This downward trend continued in the following weeks.


#### Key Performance Indicators

- **Rapid Engagement Decline:** Initial enthusiasm quickly dissipated, leading to a substantial drop in comments and likes within the first few days.

- **Dominant Artist:** Chris Brown was more frequently mentioned in comments than Davido, indicating greater fan interest in the former artist.

- **Limited Discussion:** While comments were abundant, replies and discussions were relatively scarce, suggesting a primarily passive viewing experience.

![Screenshot 2024-09-30 202216](https://github.com/user-attachments/assets/0bbb7cd4-19e1-4e1a-b283-3f7f66ece4a2)


### In-depth analysis 

### Comment Activity and Engagement

***High Comment Volume:*** The video received a substantial number of comments, totaling around 18,000.

***Positive Sentiment:*** The high number of likes (93,000) compared to replies (2,346) suggests a generally positive sentiment towards the video.

![Screenshot 2024-09-30 224853](https://github.com/user-attachments/assets/68639aa3-f96a-4be4-a2ab-2460ffcb9790)

### Artist Popularity

***Chris Brown Dominance:***  Chris Brown was more popular among fans than Davido, with his name mentioned approximately 2,000 times more frequently.


### Fan Behaviour

***Repeat Commenters:*** A small group of dedicated fans contributed significantly to the comment volume, with the top commenter leaving up to 75 comments, followed by the next commenter with 25 comments

***Limited Engagement:*** The like-to-comment ratio of 1:5 indicates a relatively low level of engagement beyond likes.


### Temporal Analysis Insights

***Peak Engagement Time:*** The highest level of engagement occurred during the early hours of the morning (12 AM - 2 AM). Comments made in this time group alone accounted for 23% of the total comments. This suggests a preference for late-night viewing and interaction.

![Screenshot 2024-09-30 202121](https://github.com/user-attachments/assets/f6287ade-6263-442a-acba-355eba4ddfb1)


***Weekday Variation:*** Wednesday saw the highest engagement with 62,625 likes and 6,336 comments, compared to Thursday's 14,220 and 3,471. However, while Wednesday saw the highest engagement, it's difficult to attribute this to a specific pattern due to the release date and rapid decline in overall engagement

![Screenshot 2024-09-30 224830](https://github.com/user-attachments/assets/f949a7a9-608b-4082-af63-62309acc1737)

## Dashboard Snapshot

![Screenshot 2024-09-30 225108](https://github.com/user-attachments/assets/b2b1810f-ea21-4dba-b3b3-4c35eb351408)



## Conclusion
The analysis of the music video "Hmmm" by Chris Brown and Davido revealed a pattern of high initial engagement followed by a rapid decline. While the video initially garnered significant attention and positive sentiment, it failed to sustain viewer interest over time, Suggesting a need to explore strategies to maintain viewer interest over time.

Further analysis could explore these factors to gain a deeper understanding of the reasons behind the engagement drop and identify potential strategies for future music videos.

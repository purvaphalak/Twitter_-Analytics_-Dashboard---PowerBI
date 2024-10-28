# Twitter Analytics Dashboard || Power-BI

### ➡️ Introduction :-

- This project focuses on analyzing Twitter data to help us understand social media engagement and performance better. 

- By exploring various metrics, such as impressions, engagements, and interactions, this dashboard helps provide insights that can drive better decision-making for content strategy.

### ➡️ Data Source 

Twitter Data : data.world/markbradbourne/rwfd-real-world-fake-data/workspace/file?filename=SocialMedia.csv

### ➡️ Tools 

- PowerBI- Data Cleaning, Data Transformation, Creating Dashboards & Data Visualization


### ➡️ Background:-

- In today’s digital world, social media platforms like Twitter play a crucial role in brand communication and user engagement. 

- Analyzing these interactions is essential to gauge what content resonates with the audience. 

- This project aims to create a comprehensive Twitter Analytics Dashboard to track these activities and understand the trends that drive engagement.

### ➡️ Learning Objectives :-

- To gain practical skills in data analysis and visualization using Power BI.

- To understand Twitter’s engagement metrics and derive actionable insights.

- To learn how to handle real-world social media data and create meaningful visualizations for reporting purposes.

### ➡️ Activities :-

- Here’s a detailed breakdown of each activity you completed in the data preparation phase:

#### 1) Data Loading and Inspection
   
- The data from Twitter was loaded into Power BI for analysis. This involved importing the dataset and reviewing its structure to ensure that all necessary fields (such as impressions, engagement, likes, retweets, timestamps, etc.) were present.

- After loading, we examined the data types and any potential discrepancies, such as missing values, to confirm data integrity before starting any transformations or calculations.

#### 2) Cleaning and Processing Twitter Data for Relevant Metrics

The dataset underwent a thorough cleaning process. This included:
- Removing any duplicate entries to ensure accurate metrics.
- Handling missing values either by filling them in with reasonable defaults (if applicable) or removing records where data was insufficient.
- Extracting or converting date and time values to separate columns, like “Tweet Date” and “Tweet Hour,” to facilitate time-based filtering and analysis.
- Additionally, columns for specific metrics, like “Engagement Rate,” “Impressions,” and “Retweets,” were formatted correctly for further calculations.

#### 3) Creating KPIs for Impressions, Engagement Rates, Retweets, and Other Metrics

Key Performance Indicators (KPIs) were created to summarize critical metrics:
- Total Impressions: The total count of views the tweets received.
- Engagement Rate: Calculated as (Engagements / Impressions) * 100 to provide a percentage view of audience interaction.
- Total Retweets and Likes: These individual metrics were set up as KPIs to track tweet popularity and engagement levels.
- These KPIs helped establish a clear view of how tweets performed over time and by specific categories (e.g., media vs. non-media).

#### 4) Designing Visualizations for Media vs. Non-Media Tweet Performance, Peak Engagement Times, and Interaction Breakdowns

Various charts and visual elements were created to visualize performance data:
- Media vs. Non-Media Tweets: A comparison chart to show differences in impressions, engagement, and other metrics for tweets containing media (images, videos) versus plain text tweets.
- Peak Engagement Times: A time-based visualization showing which hours and days resulted in the highest engagement, helping identify the best times for posting.
- Interaction Breakdown: Separate visuals for types of interactions, like likes, retweets, replies, and URL clicks, allowed for an in-depth understanding of user responses to tweets.

#### 5) Developing Filters for Specific Data Views

To allow targeted data analysis, several filters were added:
- Time-Based Filters: These filters allow selection of tweets within specific hours or time ranges (e.g., only tweets posted between 9 AM and 5 PM).
- Conditional Filters: Additional conditions, like only showing tweets with even-numbered impressions or tweets posted on weekdays, were set up to provide granular insights.
- These filters enable viewers to dynamically adjust the visualizations for different analytical needs, such as identifying weekday vs. weekend performance or focusing on tweets with high impressions.
- These steps provided a clean and structured dataset, along with powerful visualizations and flexible filtering, allowing for comprehensive Twitter analytics.

### ➡️ TASKS :-

#### 💠 TASK-1
- Create a visual that shows the average engagement rate and total impressions for tweets posted between '01- 01-2020' and '30-06-2020'. Filter out tweets that received fewer than 100 impressions and like should be 0 and this graph should work only between 3Pm to 5 PM IST apart from that we should not show the graph.

![Screenshot 2024-10-28 164512](https://github.com/user-attachments/assets/2bae49bc-75fb-4aa6-849d-fb97d53ec548)

#### 💠 TASK-2
- Build a chart to identify the top 10 tweets by the sum of retweets and likes. Filter out tweets posted on weekends and show the user profile that posted each tweet and this graph should work between 3 PM to 6 PM and the tweet impression should be even number and tweet date should be odd number as well as tweet word count be below 30.

![Screenshot 2024-10-28 164523](https://github.com/user-attachments/assets/018e47ce-344a-41df-8dcc-aaf7d5b25dd6)

  

#### 💠 TASK-3
- Analyse tweets to show a comparison of the engagement rate for tweets with app opens versus tweets without app opens. Include only tweets posted between 9 AM and 5 PM on weekdays and this graph should work between 12 PM to 6 PM and the tweet impression should be even number and tweet date should be odd number as well as tweet word count be below 40.

![Screenshot 2024-10-28 164534](https://github.com/user-attachments/assets/1d566829-2ea4-400b-aafe-b2c90d6468e1)

###➡️ Project dashboard includes:-

- Sheet 1: Tweets Analysis
- Sheet 2: Enagagement Analysis

## Tweets Analysis

![Screenshot 2024-10-27 194010](https://github.com/user-attachments/assets/4238413d-46df-4b49-a12b-a86270d0b4eb)

- This Twitter Analytics Dashboard offers a clear overview of the key metrics and performance of tweets over a specific period. Here’s a breakdown of each section and the insights it provides:

➤ Top KPIs (Key Performance Indicators)

#### - Total Impressions (912K): 
This shows the total number of times tweets were viewed. A high impression count suggests good visibility.
  
#### - Total Engagements (92K): 
This represents all actions taken on tweets (e.g., likes, retweets, comments), indicating how well tweets resonate with the audience.
  
#### - Total Likes (8K): 
Shows how many likes tweets received, giving an idea of the content's likability.

#### - Total Tweets (1166): 
This is the total count of tweets analyzed in this period.
  
#### - Average Engagement Rate (3.64%): 
This percentage indicates the engagement relative to impressions—a good measure of tweet effectiveness.
  
#### - Total Media Engagement (62K): 
Shows engagement with tweets containing media, like images or videos.

####  - Total Media Views (89K): 
This metric shows the number of times media (e.g., photos, videos) within tweets was viewed.
  
### ➡️ Visual Insights

#### ➤ Impressions by Weekday:

- Friday has the highest impressions at 256K, while Sunday has the lowest at 44K.
- Insight: Tweets posted on Friday seem to reach a wider audience, while Sunday has the least activity.

#### ➤ Tweets by Weekday:

- Thursday has the most tweets (230), followed by Tuesday and Wednesday, with the fewest tweets on Saturday and Sunday.
- Insight: More tweets were posted on weekdays, likely to align with higher audience activity during workdays.
  
### Project dashboard includes:-

#### ➤ Top 10 Tweets by URL Clicks:

- Shows the top-performing tweets in terms of clicks on any embedded URLs, with the highest at 240 clicks.
- Insight: Certain tweets attract more user interaction through URL clicks, possibly due to intriguing content or call-to-action links.

#### ➤ Impressions Over Time (in Hours):

- Peaks at 215K impressions in the early hours and 60K impressions around the end of the day.
- Insight: Impressions vary significantly through the day, with notable spikes early and late, indicating when tweets are most viewed.

#### ➤ Tweets Over Time (in Hours):

- The highest number of tweets (120) is posted at 9 AM, with a notable drop later in the day.
- Insight: There’s a trend of posting more in the morning, which may suggest aiming to capture early engagement.

#### ➤ Top 10 Tweets by Engagement Rate:

- Lists tweets with the highest engagement rates, with the top tweet reaching 34.53%.
- Insight: Specific tweets engage the audience more effectively, suggesting these types of tweets resonate well with followers.

### ➡️ Overall Insights :-

#### ➤ Tweeting Patterns: 
- Most tweets are sent out on weekdays and during the morning, targeting times when user activity may be higher.

#### ➤ Engagement Trends: 
- Engagement rates are varied, with some tweets significantly outperforming others.
- Tweets that generate higher engagement rates may share common characteristics (like time of day, topic, or media type) that can guide future content strategy.

#### ➤ Weekend Activity: 
- Both tweets and impressions are lower on weekends, which might suggest a strategic opportunity to either post less on weekends or experiment with content that appeals more to weekend users.

- This dashboard, created in Power BI, provides a detailed view of how tweets perform over time, by day, and based on tweet characteristics (e.g., with media). It can be used to refine social media strategies, identifying the best times and types of content to engage the target audience.

### Engagement Analysis

![Screenshot 2024-10-27 194035](https://github.com/user-attachments/assets/496f6721-73f4-4854-b5f0-3e489220e7e3)

This Twitter Analytics Dashboard provides a detailed analysis of tweets containing media (like images or videos) and their impact on engagement. Here’s a breakdown of each section and insights:

- Top KPIs (Key Performance Indicators)

- Total Media Views (89K):
- This metric shows the total views of media content (photos, videos) within tweets.
  
- Engagement Rate for Media (15.41%):
- The percentage of media tweets that received interactions, showing how engaging these tweets were.
  
- Tweets with Media (435):
- The number of tweets containing media, indicating that a portion of the total tweets included visual content.
  
- Total Media Engagement (62K):
- Shows total interactions (likes, retweets, replies) specifically on media tweets.
  
- Total Engagements (92K):
- Represents overall interactions, including both media and non-media tweets.

Visual Insights

#### ➤ Engagement by Month:

- Shows the distribution of likes, replies, and retweets each month, with July having the highest engagement.
 
Insight: The spike in July could indicate either an increased volume of tweets or particularly engaging content during that period.

#### ➤ Engagement Breakdown:

- A pie chart that breaks down the types of engagements across all tweets:
Likes make up 83% of total engagements, suggesting a preference for simply liking over more interactive engagements.
- Retweets and Replies make up the remaining engagements.
- Insight: Likes dominate as the primary form of engagement, showing a generally passive audience response.
  
#### ➤ Clicks Breakdown:

Displays types of clicks:
URL Clicks (50%) and Hashtag Clicks (45%) are the major forms of user interaction, while UserProfile Clicks are minimal.

Insight: Users are actively engaging with URLs and hashtags, which can indicate interest in external content and trending topics.
Media Views vs Media Engagement:

#### ➤ Compares views to interactions on media content:

Media Engagement is at 59%, while Media Views are at 41%.
Insight: This indicates that a substantial number of viewers of media content are also engaging with it, suggesting that media in tweets drives significant interaction.

#### ➤ Media Engagement and Media Views by Month:

Tracks the monthly trends for media engagement and views.
July again shows a high level of both media views and engagements, possibly due to a higher frequency of media-rich tweets or highly engaging media content during that time.
Insight: This aligns with the general engagement trends, reinforcing that July had particularly engaging media content.

#### ➤ Total Impressions and Average Engagement Rate by Tweets:

A line and bar graph that shows impressions alongside the average engagement rate for top-performing tweets.
Notable tweets have higher impressions and engagement rates, with a peak engagement rate of 17.71%.
Insight: Tweets with high impressions do not always have the highest engagement rates, indicating that while visibility is important, it doesn’t guarantee interaction.

### ➡️ Overall Insights :- 

#### ➤ Monthly Trends: 
July stands out as a highly engaging month for media content, suggesting that content posted in that month was particularly resonant with the audience.

#### ➤ Engagement Preferences: 
Likes are the dominant engagement type, followed by retweets and replies, suggesting that audiences are more inclined to show passive interest.

#### ➤ Clicks: 
High URL and hashtag clicks indicate users’ interest in external resources or related topics, making these effective tools for driving interaction.

#### ➤ Media Content: 
Media tweets (with photos or videos) perform well in terms of views and engagement, indicating the effectiveness of visual content in boosting engagement.

This Power BI dashboard provides valuable insights into the performance of media tweets, helping to identify what works best in terms of engagement and visibility. These findings can guide future strategies for maximizing tweet reach and interaction.


### ➡️ Skills and Competencies ;-

#### ➤ Data Analysis: 
Extracting and processing data to create actionable insights.

#### ➤ Power BI:
Using Power BI to visualize and report data clearly.

#### ➤ DAX Functions: 
Creating calculated columns, measures, and filters to refine data views.

#### ➤ Time and Project Management: 
Managing data, preparing visuals, and delivering a final product within deadlines.

### ➡️ Feedback and Evidence:-

- Upon completing the project, feedback was received highlighting the dashboard's usability, depth of insights, and design quality.

- Evidence of improvement was reflected in the effectiveness of the visualizations and how they communicated key findings.

### ➡️ Challenges and Solutions:-

- Challenge: Applying complex filters (like time restrictions) to visualize specific metrics.
Solution: Used DAX formulas to create calculated columns and applied custom filters for precise data segmentation.

-Challenge: Handling large datasets and ensuring smooth performance.
Solution: Optimized data models and used aggregations to improve load times and visualization performance.

###➡️  Outcomes and Impact :-
   
- The dashboard successfully highlighted key trends in engagement, enabling better understanding and tracking of Twitter content performance.
  
- It provided valuable insights for refining content strategies to increase reach and engagement.

### ➡️ Conclusion:-

- This project provided valuable experience in social media analytics, data visualization, and Power BI techniques. 

- The resulting dashboard is a useful tool that offers actionable insights, helping drive engagement strategies and making the process of analyzing social media data more efficient.




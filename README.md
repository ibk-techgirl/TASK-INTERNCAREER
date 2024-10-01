# YouTube Streamer Analysis: Understanding Popularity and Engagement

## 1. Introduction
In this project, we analyzed a dataset of YouTube streamers to uncover insights into their popularity and engagement levels. The data includes information on 1000 streamers, such as their usernames, categories, subscriber counts, countries, visits, likes, comments, and links to their channels. The primary goal of this analysis was to identify trends, popular categories, and the geographical distribution of top streamers, as well as to understand their audience engagement.

## 2. Data Overview
The dataset consists of 9 columns and 1000 entries, detailing various attributes of YouTube streamers. The key columns include:

- **Rank**: Position of the streamer based on popularity.
- **Username**: The streamer’s channel name.
- **Categories**: The genre or type of content produced (e.g., Gaming, Music).
- **Subscribers**: The number of people subscribed to the channel.
- **Country**: The country where the streamer is based.
- **Visits**: Total views on the streamer’s videos.
- **Likes**: Total likes received on the videos.
- **Comments**: Total comments received.
- **Links**: URL to the streamer’s channel.

## 3. Methodology
We followed a structured approach to analyze the dataset using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn. The steps included:

1. **Data Loading and Initial Review**: Loaded the dataset and reviewed the first few entries to understand its structure.
2. **Data Cleaning**: Addressed missing values, corrected column names, and ensured the correct data types.
3. **Data Visualization and Analysis**: Created visualizations to explore the data and derive insights.

## 4. Data Cleaning
The dataset required some preprocessing to ensure accurate analysis:

- **Corrected Column Names**: Fixed minor typos like 'Suscribers' to 'Subscribers'.
- **Handled Missing Values**: Removed entries with missing values in critical fields such as categories and usernames.
- **Converted Data Types**: Ensured numeric fields like `Subscribers`, `Visits`, `Likes`, and `Comments` were properly formatted.

## 5. Visualizations and Insights

### 5.1. Distribution of Subscribers
A histogram was created to show the distribution of subscriber counts among streamers. The analysis revealed that most streamers have between 1,000 and 10,000 subscribers, indicating a significant presence of small to mid-sized channels in the dataset.

### 5.2. Top Categories by Subscriber Count
We visualized the top 10 content categories by total subscriber count. The results highlighted that categories like **Gaming**, **Music**, and **Entertainment** are the most popular, suggesting that these genres attract a large audience on YouTube.

### 5.3. Country Analysis
A bar chart was used to display the top 10 countries with the most streamers. The analysis showed that countries like the **United States**, **India**, and **Brazil** have the highest number of streamers in the dataset, reflecting the global nature of YouTube's user base.

### 5.4. Engagement Metrics
We calculated and visualized average likes and comments per visit to assess audience engagement. The boxplot revealed a diverse range of engagement levels, with some streamers receiving significantly more interactions per visit than others. This suggests varying levels of viewer loyalty and content quality.

### 5.5. Correlation Analysis
A heatmap was used to explore the relationships between subscribers, visits, likes, and comments. A strong correlation was found between **visits** and **likes**, indicating that more views generally lead to more likes. However, the correlation between subscribers and comments was weaker, suggesting that high subscriber counts don’t always translate to high engagement.

## 6. Key Findings

1. **Most Popular Categories**: Gaming, Music, and Entertainment dominate the platform, drawing the highest number of subscribers.
2. **Top Countries for Streamers**: The United States, India, and Brazil are the leading countries in terms of the number of streamers, reflecting their large user bases.
3. **Engagement Levels Vary Widely**: While some streamers have high likes and comments per visit, many struggle with audience engagement despite having a large number of subscribers.
4. **Correlation Insights**: Higher view counts often lead to more likes, but not necessarily more comments, suggesting different forms of audience interaction.

## 7. Conclusion
The analysis provided valuable insights into the dynamics of YouTube streaming. It highlighted the importance of category and geography in determining a streamer’s popularity and engagement. Future studies could explore the impact of content strategies on subscriber growth and audience retention.

## 8. Next Steps
- **Deep Dive into Content Strategies**: Analyze the types of videos posted within top categories to understand what drives engagement.
- **Audience Demographics**: Explore the impact of demographics on engagement and popularity.
- **Predictive Modeling**: Build models to predict future subscriber growth based on current trends.

## 9. Appendix
Additional visualizations and detailed statistical tables can be found in the appendix section, providing further granularity to the insights presented.

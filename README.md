# Task-4-Exploratory-Data-Analysis-with-python
This task involves performing exploratory data analysis on a dataset. Create visualizations to understand the distribution of variables, identify outliers and check for correlations between variables

Introduction:
This dataset contains data on YouTube videos from the US, comprising 40,949 rows and 16 columns. The goal is to perform Exploratory Data Analysis (EDA) to uncover trends, patterns, and relationships within the data. Through visualizations, we aim to understand the distribution of variables and identify correlations between them, providing valuable insights into YouTube video performance and user behavior.
________________________________________
What is EDA?

Exploratory Data Analysis (EDA) is a vital step in the data analysis process that helps reveal hidden patterns, detect anomalies, and extract key insights from the dataset. By summarizing the data's main features through statistical methods and visualizations, EDA serves as a foundation for deeper analysis. In Python, EDA typically involves libraries like Pandas for data manipulation, NumPy for numerical operations, and visualization tools such as Matplotlib and Seaborn. These tools enable analysts to make informed, data-driven decisions.
________________________________________
Process:
1.	Import Necessary Libraries: Start by importing essential Python libraries: Pandas, NumPy, Matplotlib, Seaborn, and Datetime.
2.	Explore the Dataset: Use functions like df.head(), df.shape, df.info(), and df.describe() to get an initial overview of the dataset.
3.	Remove Unnecessary Columns: Drop irrelevant columns such as thumbnail_link and description to streamline the analysis.
4.	Convert Date Columns: Properly format trending_date and publish_time as datetime objects to allow for time-based analysis.
5.	Feature Engineering: Extract new features like year, month, day, and hour from the publish_time column, and create a category_name column from category_id.
________________________________________
Visualizations:
•Bar Charts:
1.	Total videos published per year.
2.	Total views by year.
3.	Top 5 categories by total views.
4.	Video count by category.
5.	Number of videos published per hour.
•	Line Plot: Video publishing trends over time.
•	Scatter Plot: Correlation between views and likes.
Bar Plots: Analyzing comments disabled, ratings disabled, and videos with errors or removals.
________________________________________
Key Insights:
1.	Video Publication Trends:
•	Yearly Trends: The number of videos published increased from 2017 to 2018, reflecting a growing trend in YouTube video production.
•	Audience Engagement: Total views were higher in 2018 compared to 2017, likely driven by the increased volume of content produced.
•	Peak Upload Times: The highest concentration of video uploads occurred around 4 PM, suggesting this is a popular time for creators to post content.
2.	Category Insights:
•	Top Categories by Views: Music, Entertainment, Film & Animation, Comedy, and People & Blogs dominate viewership, signaling that these categories are the most engaging and popular.
•	Content Distribution: Categories like Entertainment, Music, How-To & Style, Comedy, and People & Blogs have the highest video count, indicating these are the most prolific content genres on the platform.

3.	Temporal Trends:
•	Video Uploads Over Time: A steady increase in video uploads was observed, particularly in 2018, which suggests rising content creation trends over the analyzed period.
4.	Relationship Between Views and Likes:
•	Positive Correlation: The scatter plot between views and likes shows a strong positive correlation (0.849), indicating that videos with higher views tend to receive more likes, reflecting greater audience engagement with popular content.
5.	Disabled Features:
•	Comment and Rating Disabling: Many videos had comments and ratings disabled, with "false" values being more common, suggesting that most creators choose to keep these features enabled.
•	Video Errors or Removal: A notable number of videos had errors or were removed, likely due to violations of YouTube’s policies or other issues.
________________________________________
Business Insights:
•	Category Popularity: YouTube could consider promoting more content creation in top-performing categories like Music, Entertainment, and Comedy to maximize viewership and engagement.
•	Optimal Upload Time: Creators could be advised to post videos during peak hours (around 4 PM) to increase their chances of visibility and audience interaction.
•	Feature Disabling: The data shows that videos with errors or those that were removed have a higher count of "false" compared to "true," meaning that most videos remain available without issues. This suggests a relatively low occurrence of content removal or errors, potentially due to effective policy enforcement.
These insights can drive strategic decisions around content creation, user engagement, and platform management for YouTube, enhancing overall performance and user satisfaction.

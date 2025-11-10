# 620 Final Project Proposal
Naomi Buell and Richie Rivera

## Background and Goal
This project seeks to answer the research question: **What factors influence user reviews for Steam video games?** Steam is a popular digital distribution platform for video games, and user reviews play a significant role in shaping the perception and success of games on the platform. Understanding the factors that influence these reviews can provide valuable insights for game developers, marketers, and the gaming community.

For our project, we'll analyze Steam game reviews for some of the top 100 best selling games to explore how factors such as game genre, release date, and user demographics impact reviews. We'll use web scraping techniques to collect review data from Steam's platform, followed by data cleaning and preprocessing to ensure the dataset is suitable for analysis. With our data cleaned up, we’ll perform a network analysis on reviewers to see if there are any “super” reviewers among them who may influence the overall sentiment.

## Data Sources
- Steam Web API: We'll use the Steam Web API to gather app IDs for the top 100 best selling games. Here is the link: https://api.steampowered.com/ISteamApps/GetAppList/v2/
- Steam Store Reviews Page: We'll scrape user reviews directly from the Steam store pages for select games, gathering data including review text and user information. Here is the link: https://store.steampowered.com/appreviews/

## Work Plan and Responsibilities
1. Source data (RR)
2. Pre-process data (RR)
3. Perform sentiment analysis (RR)
4. Perform network analysis on reviewers (NB)
5. Analyze results and draw conclusions (NB and RR)

## Potential Challenges
Here are some potential challenges and ways we plan to mitigate them:
- Data Quality: User-generated content can be noisy and inconsistent. We may need to implement robust data cleaning techniques to ensure the quality of our dataset.
- Network Analysis Sparsity: The network of reviewers may be sparse, making it challenging to identify meaningful connections. For example, there may be few reviewers who have reviewed multiple games in our dataset. We may need to explore alternative approaches or focus on specific subsets of the data to ensure meaningful analysis. 

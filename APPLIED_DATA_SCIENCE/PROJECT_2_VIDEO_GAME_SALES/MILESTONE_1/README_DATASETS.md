
# Video Game Sales Analysis Project Datasets

## Overview
This project analyzes the determinants of video game sales, leveraging four unique datasets provided for in-depth analysis. Each dataset addresses different aspects of the sales performance and market dynamics.

---

### 1. Global Video Game Sales Dataset
**Description**: Contains sales figures for video games across multiple platforms and regions.
- **Fields**:
  - `Game_ID`: Unique identifier for each game
  - `Title`: Name of the video game
  - `Platform`: Platform(s) on which the game was released (e.g., PlayStation, Xbox, PC)
  - `Genre`: Genre classification (e.g., Action, RPG, Sports)
  - `Region`: Region of sales (e.g., North America, Europe, Asia)
  - `Sales_Units`: Units sold in each region (in millions)
  - `Release_Date`: Game release date
  - `Publisher`: Company that published the game
  - `Price`: Average retail price at launch
  - `Physical_vs_Digital`: Sales breakdown (e.g., 70% Physical, 30% Digital)

---

### 2. Consumer Sentiment and Engagement Dataset
**Description**: Compiles sentiment and engagement data from social media and user reviews.
- **Fields**:
  - `Game_ID`: Unique identifier for each game
  - `Review_Date`: Date of the review or social media post
  - `Platform`: Source of the review (e.g., Twitter, Reddit, Metacritic)
  - `Sentiment_Score`: Sentiment score from -1 (negative) to 1 (positive)
  - `Engagement_Metrics`: Number of likes, shares, or comments
  - `Topic_Tags`: Keywords or topics discussed (e.g., “graphics,” “gameplay”)
  - `Review_Text`: The actual review or post content

---

### 3. Critic and User Review Scores Dataset
**Description**: Provides critic and user ratings from different review platforms.
- **Fields**:
  - `Game_ID`: Unique identifier for each game
  - `Critic_Score`: Average critic score (0-100 scale)
  - `User_Score`: Average user rating (0-10 scale)
  - `Review_Platform`: Platform for the review (e.g., Metacritic)
  - `Score_Date`: Date of the review
  - `Reviewer_Comments`: Notable comments from reviews
  - `Score_Volatility`: Changes in score over time

---

### 4. Market Trends and Competitive Analysis Dataset
**Description**: Aggregates data on market trends, platform popularity, and competitor analysis.
- **Fields**:
  - `Year`: Year of the data
  - `Region`: Specific region (e.g., North America, Europe, Asia)
  - `Platform_Popularity`: Ranking of platforms by market share
  - `Genre_Trends`: Most popular genres in the region/year
  - `Competitor_Releases`: Major game releases by competitors
  - `Marketing_Spend`: Estimated marketing spend by companies
  - `Economic_Indicators`: Economic metrics (e.g., GDP growth rate)

---

## Usage
These datasets provide a foundation for conducting Exploratory Data Analysis, sentiment analysis, predictive modeling, and more. Proper preprocessing and analysis methods should be applied as needed for insights.

---

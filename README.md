# 🎮 Steam Library Analysis: Uncovering User Behavior and Video Game Popularity

Welcome to the **Steam Library Analysis** project! This comprehensive analysis dives into user behavior, game popularity, and platform trends using data from Steam, one of the largest PC gaming platforms.

---

## 📌 Project Overview

In this project, we:
- **Analyzed** user engagement patterns, including game ownership, playtime, and reviews.
- **Examined** game ratings, pricing dynamics, and seasonal trends.
- **Derived insights** to aid game developers in optimizing their strategies for pricing, user engagement, and platform compatibility.

🚀 **Motivation**: With the growth of the gaming industry and upcoming trends like virtual reality, this analysis provides valuable insights into user preferences and game dynamics.

---

## 📊 Key Insights

### 🔹 **User Behavior**
- **Average game ownership**: 124 games per user.
- **Playtime per game**: ~1.3 hours (much lower than average game completion time).
- **Average reviews per user**: Only 3% of owned games are reviewed.

### 🔹 **Game Popularity**
- Top games like *Lost Ark*, *Elden Ring*, and *Mount & Blade II: Bannerlord* dominate in playtime and user engagement.
- October is the most popular month for new game releases, aligning with holiday season trends.

### 🔹 **Platform Trends**
- **Windows** is the dominant operating system among users (2.85M), followed by **Mac** (423K) and **Linux** (210K).
- Windows-exclusive games are ~$5 cheaper on average compared to cross-platform titles.

---

## 📈 Analytical Approach

### 🔧 **Data Source**
Data was collected from the [Steam API](https://store.steampowered.com/) and includes:
1. **Games** table: Details like release date, price, OS compatibility, and reviews.
2. **Users** table: User-specific data on purchases, reviews, and playtime.
3. **Recommendations** table: User ratings and engagement metrics.

### 🗂 **Data Cleaning**
- **Null values** were addressed, and duplicate entries were removed.
- Users without purchases were excluded to focus on meaningful data.
- The dataset was filtered for the year 2022 to ensure consistency.

---

## 🖥️ Tableau Dashboard

Explore the interactive visualizations via Tableau: [Steam Library Dashboard](https://public.tableau.com/app/profile/sahasra.konkala/viz/SteamLibraryAnalysisUncoveringUserBehaviourandVideoGamePopularity_17020620794440/DeepInsightsfromTop10Games?publish=yes).

---

## 🔍 Research Questions Answered

1. **What is the average playtime and reviews per user?**
   - Users spend an average of **162 hours per year** across their owned games.
   - Most users leave reviews for less than **3%** of their games.

2. **Which games have the highest engagement?**
   - *Lost Ark* leads with over **27M hours** played in 2022.

3. **What is the impact of ratings on user engagement?**
   - Games with **positive ratings** attract significantly higher engagement and reviews.

4. **How do game prices vary across platforms?**
   - Cross-platform games are more expensive (~$30) compared to Windows-only titles (~$25).

5. **What are the most reviewed games?**
   - Titles like *Counter-Strike: Global Offensive* and *Terraria* have garnered millions of reviews.

---

## 🔥 Challenges Faced

- **Incomplete Data**: Missing metrics like gameplay mechanics limited in-depth analysis.
- **Limited Timeframe**: Analyzing data for a single year (2022) restricted longitudinal insights.

---

## 🛠️ Technologies Used

- **BigQuery**: For data querying and transformations.
- **Python**: Data cleaning and exploratory analysis.
- **Tableau**: Interactive visualizations and dashboards.

---

## 🚀 Future Work

- **Machine Learning Models**: Predict user engagement based on game features.
- **Deeper Behavioral Analysis**: Study the correlation between game ratings and purchase patterns.
- **Interactive App**: Build a dashboard to allow real-time exploration of game trends.

---

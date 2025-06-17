# Covid-Misinformation-X-Analysis
**Author:** Tak Do  
**Dataset:** [CoAID - COVID-19 Healthcare Misinformation Dataset](https://github.com/cuilimeng/CoAID)  
**Tools:** R, igraph, network analysis  

---

## 📌 Project Summary

The social media platform X (formerly Twitter) played a central role in shaping public understanding and misunderstanding during the COVID-19 pandemic. This project investigates how COVID-19 misinformation spread through user networks by analyzing repost (retweet/reply) behavior using the CoAID dataset.

By visualizing and analyzing the **reply network**, this study explores structural features such as:
- **Degree centrality**
- **Betweenness centrality**
- **Closeness centrality**
- **Clustering and density**

These metrics reveal influential users and suggest how misinformation may circulate within echo chambers online.

---

## 📂 Dataset & Structure

- **Source:** [CoAID GitHub Repository](https://github.com/cuilimeng/CoAID)
- **Files Used:**
  - `NewsFakeCOVID-19_tweets.csv`
  - `NewsFakeCOVID-19_tweets_replies-2.csv`

- **Nodes:** Users who posted or replied to misinformation tweets  
- **Edges:** Directed connections (replies) between users  
- **Timeframe:** January to June 2020

---

## Business Problem
TikTok is a fast-growing platform with high user engagement. This project aims to identify key factors that drive content performance and creator popularity.

## Key Questions
• What factors influence high engagement on TikTok content?  
• Which creators dominate interaction metrics?  
• How do content characteristics (e.g., duration, followers, verification) affect performance?  

## Dataset
• Source: Kaggle (TikTok dataset)  
• Data includes: followers, likes (diggCount), shares, comments, video duration, and creator metadata  

## Methodology
• Data cleaning and preprocessing using Python (Pandas)  
• Exploratory Data Analysis (EDA)  
• Data visualization using Matplotlib & Tableau  
• Basic machine learning (regression & clustering) for pattern identification  

## Key Analysis
• Engagement metrics (likes, shares, comments) were analyzed to identify performance trends  
• Distribution analysis showed strong imbalance with high-performing outliers  
• Correlation analysis identified relationships between followers, likes, and engagement  
• Clustering (K-Means) grouped creators into low, medium, and high engagement segments  

## Key Insights
• Engagement is highly concentrated among a small number of top creators  
• Verified creators consistently achieve higher interaction rates  
• Shorter video duration tends to generate higher engagement  
• High follower count does not always guarantee high engagement per post  
• Significant data imbalance indicates that viral content is not evenly distributed  

## Machine Learning (Summary)
• A regression model was tested to predict engagement but showed low accuracy due to data imbalance  
• Clustering analysis successfully identified distinct engagement groups among creators  

## Recommendations
• Content creators should focus on short, engaging videos to maximize interaction  
• Building credibility (e.g., verified status) can significantly improve reach and trust  
• Brands should prioritize collaboration with high-engagement creators rather than just high-follower accounts  
• Further analysis with more balanced datasets is recommended for better prediction accuracy  

## Tools & Technologies
• Python (Pandas, NumPy, Matplotlib)  
• Google Colab  
• Tableau  

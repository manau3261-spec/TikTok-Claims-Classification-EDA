# TikTok Claims Classification Project
## Exploratory Data Analysis & Engagement Trends

### 📊 Project Overview
This project analyzes a TikTok dataset to distinguish between **claims** (factual assertions) and **opinions** (personal views). The goal is to support the Trust & Safety team in optimizing their moderation queue by identifying high-risk, viral content before it spreads misinformation at scale.

### 💡 Key Insights
* **Balanced Data:** The dataset is split into 50.35% claims and 49.65% opinions, eliminating class imbalance risks for future machine learning models.
* **The Virality Premium:** Claim videos experience massive virality. Banned authors posting claims see a median share count **33 times higher** (14,468) than active authors (437).
* **Risk Profile:** Authors who post claim videos are over **7 times more likely** to be banned or placed under review, proving a strong correlation between factual assertions and terms-of-service violations.

### 🔍 Engagement Analysis
Engagement metrics per view are leading indicators of content type. Claim videos achieve a median click-through like rate of 32-35%, whereas opinion videos only reach 20-22%. The comments-per-view ratio is nearly 3 times higher for claims, confirming that controversial statements provoke heavy user interaction.

### 🚀 Next Steps
1. Resolve the 298 missing data entries identified during cleaning.
2. Conduct formal statistical hypothesis testing on engagement variance.
3. Build a predictive classification model (e.g., Random Forest) to automate real-time claim flagging.

# Tiktok-Content-Analytics

# 📌 Project Description
This project performs an end-to-end Exploratory Data Analysis (EDA) on 19,000+ TikTok videos to investigate behavioral and engagement differences between claim-based and opinion-based content. By analyzing metrics such as views, likes, shares, comments, and author ban status, the project surfaces patterns relevant to content moderation, trust & safety strategy, and platform analytics.
The analysis is paired with an interactive Tableau dashboard for stakeholder-ready visual storytelling: https://public.tableau.com/views/TikTokDashboard_17732850806220/TiktokDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 

# 🧩 Problem Statement
TikTok and social media platforms in general, face a critical challenge: claim-based content spreads differently from opinion-based content, and bad actors who produce misleading claims often exhibit distinct behavioral signatures before being flagged or banned.

This raises key questions:

- Do claim videos engage audiences differently than opinion videos?
- Do banned or under-review authors show measurable behavioral differences from active authors?
- Can engagement metrics serve as early signals for content moderation?

# 🎯 Objective

- Quantify the engagement gap between claim-based and opinion-based TikTok content
- Analyze how author ban status correlates with content type and engagement behavior
- Engineer normalized engagement metrics to enable fair, unbiased comparison across content segments
- Deliver actionable insights through Python analysis and an interactive Tableau dashboard

# 📊 Key Insights

- 100x View Gap: Claim videos averaged 501K views vs. 5K for opinion videos, suggesting claims are algorithmically inherently more viral.
- Banned Authors Share Far More: Banned accounts had a median share count of 14,468 vs. only 437 for active accounts, indicating a potential behavioral early-warning signal for moderation pipelines
- Claim Content Dominates Across All Engagement Ratios: Claim videos outperformed opinion videos on likes-per-view, comments-per-view, and shares-per-view regardless of author ban status, pointing to a content-type effect independent of author behavior.
- Banned Authors Skew Toward Claims: 1,439 banned authors posted claim content vs. only 196 for opinions, revealing a strong correlation between making factual claims and account suspension risk
- Under-Review Accounts Mirror Banned Behavior: Under-review authors showed median share counts of 9,444, which is far above active authors, suggesting the moderation system is successfully flagging high-risk behavior early.

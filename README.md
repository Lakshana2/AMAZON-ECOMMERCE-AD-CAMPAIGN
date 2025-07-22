Amazon E-commerce Campaign Analysis Dashboard
This project analyzes Amazon’s e-commerce marketing campaign data using Power BI to uncover key performance insights.

📊ABOUT DATASET:

Company- Company name or brand

Campaign_Type- Email, Social Media, Ads, etc.

age.duration- How long the campaign ran (days)

Channel_Used- Instagram, Facebook, Google, etc.

Conversion_Rate- % of users who converted

Acquisition_Cost- Cost to acquire a customer

Location- Region or City Text

roi- Return on Investment

Clicks- No. of users who clicked

Impression- How many people saw it

Engagement- Likes, shares, comments

Customer_Segment- Target group (Youth, Professionals, etc.)

🔍 Key Metrics Analyzed: Click Through Rate (CTR)

Cost per Click (CPC)

Engagement Rate

ROI % (Return on Investment)

✍️ DAX Functions used: CPC (Cost per Click) = DIVIDE(SUM('Amazon Ecommerce'[Acquisition Cost]),SUM('Amazon Ecommerce'[Clicks]),0)

CTR(Click Through Rate) = DIVIDE(SUM('Amazon Ecommerce'[Clicks]),SUM('Amazon Ecommerce'[Impressions]),0)*100

Engagement Rate = DIVIDE(SUM('Amazon Ecommerce'[Engagement_Score]),SUM('Amazon Ecommerce'[Impressions]),0)*100

ROI%=ROI_Percent = DIVIDE(SUM(roi), SUM(Acquisition_Cost), 0) * 100

📈 Visuals Used: Table Chart: Compare campaign types by clicks, ROI, and conversion.

Scatter Plot: Analyze ROI vs Acquisition Cost efficiency.

Line and Stacked Column Chart: Show clicks and conversion trends by campaign.

Bar/Map Charts: Understand location and channel performance.

💡 Insights Uncovered: Which channels and campaign types give the best ROI

Cost-efficiency of each campaign

Most engaging customer segments and locations


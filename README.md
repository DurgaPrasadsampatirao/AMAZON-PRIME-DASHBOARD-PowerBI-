# Amazon Prime Dashboard PowerBI

## Project Overview
This project focuses on creating an interactive PowerBI dashboard for analyzing Amazon Prime's content performance, user engagement, and subscription metrics. The dashboard aggregates key metrics like viewing trends, customer demographics, content ratings, and subscription growth to provide actionable insights. The goal is to empower stakeholders to make data-driven decisions for content strategies, marketing, and customer retention.

Project link: [Amazon Prime Dashboard PowerBI](https://github.com/DurgaPrasadsampatirao/AMAZON-PRIME-DASHBOARD-PowerBI-/blob/main/proj_3.jpg)

---

## Key Objectives
1. **Content Performance Analysis**: Analyze the performance of different content types (movies, TV shows, original content) based on user engagement metrics.
2. **Customer Engagement**: Track metrics such as watch time, views per customer, and content ratings to evaluate how well content resonates with viewers.
3. **Subscription Growth**: Measure the growth of Amazon Prime subscriptions across regions, demographics, and time periods.
4. **User Demographics**: Identify key user segments based on their content preferences, viewing habits, and demographics.
5. **Revenue Analysis**: Analyze the impact of subscription plans, promotions, and regional pricing on Amazon Prime's revenue.

---

## Insights and Findings

### 1. Data Overview
- **Dataset**: The dataset includes data about Amazon Prime content, user engagement, customer demographics, and subscription details.
- **Key Columns**:
  - `customer_id`: Unique identifier for each subscriber.
  - `content_id`: Identifier for each movie or TV show.
  - `content_type`: Type of content (e.g., movie, TV show, original).
  - `genre`: Genre of the content (e.g., drama, action, comedy).
  - `watch_time`: Total watch time per user.
  - `rating`: Rating given by the user (1 to 5).
  - `subscription_date`: Date the user subscribed to Amazon Prime.
  - `subscription_type`: Type of subscription plan (e.g., monthly, annual).
  - `region`: Geographic region of the user.
  - `device`: Device used to stream content (e.g., mobile, tablet, TV).

### 2. Content Performance Analysis
- **Most Watched Content**: The top genres with the highest viewing hours include drama, action, and comedy. Amazon Originals like "The Boys" and "Jack Ryan" had the most engagement.
- **Content Type Performance**: TV shows are watched for longer periods compared to movies, with binge-watching behavior being more prominent in long-running series.
- **User Ratings**: Content rated 4 and above tends to have higher retention rates, with users more likely to recommend content they enjoyed.

### 3. Customer Engagement
- **Watch Time Trends**: Users tend to watch content more during the weekends, with Friday evening to Sunday being the peak viewing period.
- **Engagement by Region**: North America and Western Europe have the highest average watch time per user, while emerging markets are showing increasing engagement.
- **Device Usage**: Most users watch content on smart TVs, followed by mobile devices, with tablets showing lower engagement.

### 4. Subscription Growth
- **Subscription Trends**: There has been a steady increase in subscriptions over the past few years, with spikes seen during major sales events like Amazon Prime Day and Black Friday.
- **Churn Rate**: The churn rate is slightly higher in regions with lower engagement, suggesting a need for better content localization and customer retention strategies.
- **Regional Growth**: North America, followed by Western Europe, remains the largest market for Amazon Prime, with growth opportunities in Asia and South America.

### 5. Revenue Analysis
- **Subscription Revenue**: Monthly subscriptions contribute to steady revenue flow, while annual subscriptions offer higher revenue per user but are more susceptible to churn.
- **Impact of Promotions**: Subscription growth spikes during promotions, but long-term retention post-promotion varies depending on content offerings.
- **Regional Pricing**: Pricing strategies have different impacts across regions, with emerging markets showing a preference for lower-cost subscription plans.

---

## Methodology
1. **Data Collection**: The dataset was collected from internal Amazon Prime logs, including customer interaction with the platform, subscription data, and content performance metrics.
2. **Data Cleaning**: Missing values were handled using imputation methods, and categorical data was encoded for proper analysis.
3. **PowerBI Dashboard Design**: The dashboard includes multiple visualizations like bar charts, line graphs, pie charts, and maps to represent key business metrics.
4. **Insights Extraction**: Key performance indicators (KPIs) were calculated, such as customer retention rate, watch time, churn rate, and revenue per user, to uncover actionable insights.

---

## Technologies Used
- **PowerBI**: For building the interactive dashboard, visualizing data, and providing insights into customer engagement and content performance.
- **SQL**: For querying the data from Amazon Prime’s internal databases.
- **Excel**: For data cleaning and preliminary analysis before visualizing in PowerBI.
- **Python (optional)**: For advanced analysis and integration with PowerBI (e.g., using Python scripts for data processing).


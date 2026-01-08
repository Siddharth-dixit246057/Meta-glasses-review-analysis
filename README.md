# Meta Glasses Customer Review Analysis (SQL)

# Project Overview
This project analyzes 10,000 verified customer reviews for Meta Glasses using SQL.  
The goal is to extract meaningful business insights related to customer satisfaction, review helpfulness, and sentiment reliability.

# Tools Used
- MySQL (XAMPP)
- SQL (Joins, Aggregations, CASE, Filtering)
- Power query editor for cleaning

# Dataset Summary
- Total Reviews: 10,000
- Market: United States
- Verified Purchases: 100%
- Missing Values: None

# Key Analyses Performed
- Rating distribution and customer satisfaction
- Review helpfulness behavior
- Impact of review length on helpfulness
- Sentiment alignment with ratings

#  Key Insights
- Over 80% of customers rated the product 4 or 5 stars.
- 3-star reviews were found to be the most helpful, suggesting users trust balanced opinions.
- Long-form reviews received 40x more helpful votes than short reviews.
- Sentiment labels aligned perfectly with customer ratings, indicating high data reliability.

#  Project Structure
Refer to the `sql_queries` folder for all SQL scripts and `screenshots` for query outputs.

# Conclusion
This project demonstrates practical SQL skills, analytical thinking, and the ability to translate raw data into actionable business insights.

# 🧱 Data Schema

| Column Name            | Description |
|------------------------|-------------|
| reviewID               | Unique review identifier |
| rating                 | Customer rating (1–5) |
| review                 | Review text |
| helpful                | Number of helpful votes |
| verifiedPurchase       | Verified buyer flag |
| is_positive_review     | Sentiment label (1 = positive) |
| date                   | Review date |
| country                | Reviewer's country |
(The dataset is downloaded from kaggle)

# Instagram User Analytics Dashboard (Tableau)

## 📌 Project Overview

This project analyzes **Instagram post-level performance data** to understand what drives user engagement and content success.
Using Tableau, an interactive dashboard was built to help **content, marketing, and growth teams** make data-driven decisions around posting strategy, content mix, and audience engagement.

---

## 🎯 Business Objective

The objective of this project is to:

* Identify high-performing content categories
* Measure the impact of Call-to-Action (CTA) on engagement
* Analyze the relationship between followers and engagement
* Determine optimal posting **days and times**
* Highlight top-performing posts for replication

---

## 📊 Dataset

**Source:** Kaggle – Instagram Analytics Dataset
**Granularity:** Post-level data

### Key Fields Used

* Engagement metrics: likes, comments, shares, saves, engagement_rate
* Reach metrics: follower_count, reach, impressions
* Content attributes: content_category, media_type, CTA flag
* Time attributes: post_date, post_hour, day_of_week
* Performance classification: performance_bucket_label

---

## 🧹 Data Preparation

* Verified and corrected data types in Tableau
* Created calculated fields for:

  * Total Engagement
  * Engagement Rate (%)
  * CTA usage labels
* Validated engagement metrics before visualization

---

## 📈 Dashboard Components

The dashboard includes the following analytical views:

### 🔹 KPI Summary

* Average Engagement Rate
* Average Reach
* Average Followers
* Percentage of Posts with CTA

### 🔹 Engagement Analysis

* Engagement by Content Category
* CTA Impact on Engagement
* Followers vs Engagement (Scatter Plot)

### 🔹 Content Contribution

* Category-wise engagement contribution (Treemap)
* Top Performing Posts

### 🔹 Posting Strategy

* Best Posting Time (Hourly Trend)
* Best Posting Day (Weekly Comparison)

---

## 🎛️ Interactivity

* Filters for content category, media type, and account type
* Tooltips with contextual performance details
* Clean, dark-theme layout for executive readability

---

## 🛠 Tools Used

* **Tableau Desktop**
* Calculated Fields & Aggregations
* Interactive Dashboards
* Data Visualization Best Practices

---

## 📁 Repository Structure

```
tableau-user-analytics/
│
├── data/
│   └── Instagram_Analytics.csv
│
├── dashboard/
│   ├── instagram_user_analytics_dashboard.png
│   └── tableau_public_link.txt
│
├── insights/
│   └── key_insights.md
│
└── README.md
```

---

## 💡 Business Value

This dashboard enables teams to:

* Optimize posting schedules
* Focus on high-engagement content categories
* Understand CTA effectiveness
* Identify scalable content patterns
* Improve engagement without increasing posting volume

---

## 👤 Author

**Pritesh Patil**
Data Analyst | SQL | Power BI | Tableau | Analytics & Insights

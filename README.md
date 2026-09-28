# twitter-analytics-dashboard
# Twitter Analytics Dashboard – Power BI

## Project Overview

This project is a Power BI analytics dashboard developed as part of the ElevanceSkills Technology Data Analyst Internship.

The dashboard analyzes Twitter data to identify patterns in tweet interactions, engagement rates, media performance, and overall tweet engagement.

## Objectives

* Analyze tweet interactions by category
* Compare engagement rates based on App Opens
* Analyze Media Views and Media Engagements by weekday
* Compare Replies, Retweets, and Likes
* Track monthly engagement rate trends
* Identify the Top 10 Tweets based on total engagement

## Dataset

The project uses the Twitter Analytics Internship dataset provided for the internship training project.

The dataset contains tweet-level information including:

* Tweet Date and Time
* Tweet Text
* Tweet Category
* URL Clicks
* User Profile Clicks
* Hashtag Clicks
* App Opens
* Media Views
* Media Engagements
* Replies
* Retweets
* Likes
* Impressions
* Engagement Rate
* User Profile

## Dashboard Pages

### Task 1 – Tweet Interaction by Category

Analyzes URL Clicks, User Profile Clicks, and Hashtag Clicks across tweet categories.

### Task 2 – Engagement Rate: App Opens

Compares engagement rates for tweets with and without App Opens under the specified filtering conditions.

### Task 3 – Media Interaction by Weekday

Visualizes Media Views and Media Engagements by weekday using the required filtering conditions.

**Dataset Note:** The provided dataset contains very limited records after applying all Task 3 filtering conditions, including the exclusion of tweets containing H/h.

### Task 4 – Replies, Retweets & Likes

Compares total Replies, Retweets, and Likes for tweets posted between June and August 2020.

### Task 5 – Monthly Engagement Rate

Shows the monthly average Engagement Rate and compares tweets with and without media.

### Task 6 – Top 10 Tweets by Engagement

Identifies the Top 10 tweets based on the combined total of Retweets and Likes, using the specified filtering conditions.

## Tools & Technologies

* Microsoft Power BI
* Microsoft Excel
* DAX
* Data Cleaning & Transformation
* Data Visualization

## Key DAX Measures

```DAX
Total Engagement =
SUM(TwitterAnalytics[Retweets]) +
SUM(TwitterAnalytics[Likes])
```

```DAX
Character Count =
LEN(TwitterAnalytics[Tweet Text])
```

## Project Features

* Interactive Power BI visualizations
* Tweet engagement analysis
* Category-based interaction analysis
* Media performance analysis
* Monthly trend analysis
* Top engagement identification
* Conditional filtering based on the internship requirements

## Project Structure

```text
Twitter-Analytics-PowerBI/
│
├── README.md
├── Twitter_Analytics_Report.pbix
├── Twitter_Analytics_Dataset.xlsx
├── Screenshots/
│   ├── task1.png
│   ├── task2.png
│   ├── task3.png
│   ├── task4.png
│   ├── task5.png
│   ├── task6.png
│   └── dashboard.png
│
└── Documentation/
    └── Project_Report.pdf
```

## Internship

**Organization:** ElevanceSkills Technology Private Limited
**Domain:** Data Analytics
**Tool:** Power BI

## Author

**Dhanusri N**
B.E. Computer Science and Engineering

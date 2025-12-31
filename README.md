# SQL_Spotify_User_Churn_Analysis

**Project Overview**
* This project explores user behavior and churn patterns within Spotify using SQL. The goal is to identify behavioral trends associated with user churn and extract insights that could inform retention strategies.
* The analysis focuses on understanding how engagement metrics—such as listening activity, ad exposure, and subscription type relate to user churn.

**Objectives**
* Analyze user behavior patterns associated with churn
* Identify engagement differences between active and churned users
* Explore how subscription type and usage behavior influence churn
* Practice real-world SQL analysis using a structured dataset

**Analysis Structure**

The project is organized around a series of analytical questions:

1️⃣ What percentage of users have churned?

2️⃣ How does engagement differ between churned and retained users?

3️⃣ Does ad exposure influence churn?

4️⃣ How does subscription type relate to churn?

5️⃣ Which user segments show the highest churn risk?

**Tools & Technologies**
* SQL (BigQuery)
* Kaggle Datasets

**Dataset Overview**

| Column                | Description                               |
| --------------------- | ----------------------------------------- |
| user_id               | Unique identifier for each user           |
| gender                | User gender                               |
| age                   | User age                                  |
| country               | User location                             |
| subscription_type     | Free, Premium, or Family                  |
| listening_time        | Average minutes listened per day          |
| songs_played_per_day  | Number of songs played daily              |
| skip_rate             | Percentage of skipped tracks              |
| device_type           | Device used to access the platform        |
| ads_listened_per_week | Number of ads heard per week              |
| offline_listening     | Whether offline mode is used              |
| is_churned            | Target variable (1 = churned, 0 = active) |

**Next:**

Click here to view the [SQL Code](https://github.com/montsecodes/SQL_Spotify_Churn/blob/main/SQL%20-%20Data%20Exploration.sql)

These are my [Insights](https://github.com/montsecodes/SQL_Spotify_Churn/blob/main/Insights.md)

Here is the [dataset](https://github.com/montsecodes/SQL_Spotify_Churn/blob/main/spotify_churn_dataset.csv)

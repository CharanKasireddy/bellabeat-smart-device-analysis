# Bellabeat Smart Device Usage Analysis

> Google Data Analytics Capstone Project

## Overview

Bellabeat is a wellness technology company focused on helping women understand and improve their health habits. This case study analyzes Fitbit smart-device activity data to identify consumer usage trends and translate them into marketing recommendations for the **Bellabeat app**.

## Business Task

Analyze Fitbit activity and engagement data to identify smart-device usage trends, then use those insights to recommend ways the Bellabeat app can encourage consistent activity and long-term engagement.

### Guiding Questions

1. What trends appear in non-Bellabeat smart-device usage?
2. How could these trends apply to Bellabeat app users?
3. How could the findings inform Bellabeat's marketing strategy?

## Data Source

The analysis uses the [Fitbit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit) dataset published by Mobius on Kaggle under the CC0 public-domain license.

- Primary file: `dailyActivity_merged.csv`
- Observation period: April 12-May 12, 2016
- Participants: 33 anonymized users
- Activity records: 940 daily observations

## Tools Used

- **Google Sheets** - initial storage, formatting, and cleaning checks
- **Google BigQuery (SQL)** - aggregations, descriptive statistics, and trend analysis
- **Tableau** - dashboard creation and visualization

## Data Preparation

- Preserved original CSV files before cleaning
- Standardized date columns and formats
- Checked for duplicates, whitespace, outliers, and invalid daily time totals
- Formatted distance, weight, and BMI fields to two decimal places
- Used BigQuery to create summary statistics and investigate trends

## Dashboard Views

1. **Average Steps by Weekday** - compares average daily steps across the week.
2. **Participant Activity Segments** - shows the share of users in step-based activity categories.
3. **Participants Tracking Data Over Time** - shows how many distinct users submitted activity data each day.

## Key Findings

- Participants averaged **7,638 daily steps**.
- **57.6%** of participants averaged fewer than 8,000 steps per day, while only **9.1%** averaged at least 12,000 steps.
- Saturday was the most active day, averaging **8,153 steps**; Sunday was the least active day, averaging **6,933 steps**.
- **63.6%** of participants submitted activity data every day, but daily participation fell from **33** users at the start of the study to **21** on the final day.
- Steps and calories had a moderate positive relationship (**r = 0.592**).

## Recommendations for the Bellabeat App

1. **Offer personalized daily step goals and progress messages.** Personalized goals can help less-active users build sustainable habits.
2. **Create a weekend activity challenge, especially for Sundays.** Targeted prompts can address the day with the lowest activity.
3. **Send re-engagement notifications when users stop logging data.** Timely reminders and streaks can encourage users to continue tracking.

## Limitations

- This is an exploratory analysis of 33 Fitbit users over 31 days.
- Fitbit users are not necessarily representative of Bellabeat customers.
- Demographic, location, health-goal, and marketing-exposure data were unavailable.
- Findings identify patterns and do not establish causation.

## Author

Charan Kasireddy

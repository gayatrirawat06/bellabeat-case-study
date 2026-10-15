# Bellabeat Case Study: Fitness Tracker Data Analysis

## Project Overview
This project explores fitness tracker data to understand user activity patterns, sleep behavior, and daily habits. The analysis aims to generate actionable insights that can help Bellabeat improve user engagement and support data-driven marketing decisions.

## Business Task
Analyze smart-device usage data to identify trends in how users engage with fitness tracking devices and recommend how Bellabeat can use these insights in its marketing strategy.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Kaggle Notebooks

## Project Objectives
- Understand daily activity and sleep patterns.
- Clean and prepare data for analysis.
- Perform exploratory data analysis (EDA).
- Identify trends and relationships in user behavior.
- Develop data-driven business recommendations.

## Project Workflow
1. Data collection and understanding
2. Data cleaning and preprocessing
3. Exploratory data analysis
4. Data visualization
5. Insights and recommendations

## Key Findings
The analysis of Fitbit fitness tracker data revealed the following patterns in daily physical activity, calorie expenditure, sedentary behavior, and sleep.

1. Physical Activity and Calorie Expenditure
   Daily steps showed a moderate positive correlation with calories burned (r = 0.59), indicating that days with more steps tended to be associated with higher calorie expenditure.
   Very active minutes had a positive correlation with calories burned (r = 0.62), compared with fairly active minutes (r = 0.30) and lightly active minutes (r = 0.29).
   Total steps and total distance had a very strong positive correlation (r = 0.99).

2. Sedentary Behavior and Activity Levels
   Daily steps and sedentary minutes had a negative correlation (r = −0.33) in the daily activity dataset.
   Low-activity days averaged 1,045.2 sedentary minutes, compared with 888.7 minutes on high-activity days.
   Average very active time increased from 3.0 minutes on low-activity days to 48.5 minutes on high-activity days.

3. Daily Activity Patterns
   Saturday recorded the highest average daily steps at approximately 8,153 steps, followed by Tuesday at 8,125 steps.
   Sunday recorded the lowest average daily steps at approximately 6,933 steps.
   The difference between Saturday and Sunday was approximately 1,220 steps per day.

4. Sleep Duration and Sleep Efficiency
   Average sleep duration was 7.0 hours, with a median of 7.2 hours.
   Average time in bed was 7.6 hours, with a median of 7.7 hours.
   Average sleep efficiency was 91.6%, with a median of 94.3%.

5. Relationship Between Physical Activity and Sleep
   Daily steps and sleep duration had a weak negative correlation (r = −0.19) in the merged activity–sleep dataset.
   Sedentary minutes and sleep duration had a stronger negative correlation (r = −0.60) in the merged dataset.
   Total steps and total active minutes had a positive correlation (r = 0.74) in the merged dataset.
   Sleep efficiency showed only small correlations with the activity measures included in the analysis.

6. Weekly Sleep Patterns
   Sunday had the highest average sleep duration at approximately 7.5 hours in the merged activity–sleep dataset.
   Tuesday and Thursday had the lowest average sleep duration, at approximately 6.7 hours each.
   In this merged dataset, Sunday combined the lowest average daily steps (approximately 7,298) with the highest average sleep duration.

7. Hourly Activity Patterns
   The hourly step heatmap showed lower activity overnight and higher activity during daytime periods.
   Stronger activity patterns appeared around late morning, afternoon, and early evening, with variations across weekdays.

Overall Conclusion
The analysis identified associations between physical activity, calorie expenditure, and sedentary behavior, alongside variations in sleep duration and activity across the week. The results suggest that daily steps alone do not fully describe an individual's activity and sleep patterns. Combining activity intensity, sedentary time, sleep duration, and hourly activity provides a more comprehensive view of wearable-user behavior.

## Business Recommendations
Personalized Activity Goals: Set achievable step and activity targets based on individual activity levels.
Sedentary Time Reminders: Encourage movement breaks during prolonged periods of inactivity.
Weekday-Based Challenges: Introduce personalized challenges to encourage activity on comparatively less active days.
Sleep Insights: Display sleep duration and sleep efficiency together to help users understand their sleep patterns.
Smart Activity Notifications: Use hourly activity patterns to test more relevant reminder timings.
Combined Wellness Insights: Present steps, active minutes, sedentary time, calories, and sleep metrics together for a more comprehensive view of user behavior.

## Kaggle Notebook
[View the original notebook](https://www.kaggle.com/code/gayatrirawat6/capstone-project)  


## Conclusion
This case study demonstrates data cleaning, exploratory data analysis, data visualization, and business-oriented interpretation of fitness tracker data to support informed decision-making.

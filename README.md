College Event Feedback Analysis
Future Interns – Data Science & Analytics | Task 3
This repository contains my project for Task 3 of the Future Interns – Data Science & Analytics Internship Program.
The goal of this task was to analyze student feedback collected from college events and convert it into meaningful, actionable insights using Python, NLP, and Power BI.

📌 Project Objective
College events often collect ratings and written feedback through Google Forms.
This project focuses on analyzing that feedback to:

Identify satisfaction levels

Detect common opinions and complaints

Perform sentiment analysis on comments

Visualize all findings using reports and dashboards

Suggest improvements for future events

📁 Dataset
The raw data was exported from Google Forms and includes:

Event Name

Event Type (Workshop / Seminar / Cultural / etc.)

Rating (1–5 scale)

Feedback Comments

After cleaning, a structured dataset was prepared for analysis.

🧹 Data Cleaning Steps
Removed empty rows and duplicates

Standardized event names

Cleaned text comments (lowercase, removed punctuation, etc.)

Treated missing ratings and comments

Prepared dataset for NLP sentiment analysis

Final Cleaned Dataset:
event_feedback_cleaned.csv

🧠 Sentiment Analysis
NLP tools such as TextBlob or VADER were used to determine:

Sentiment Category: Positive / Neutral / Negative

Polarity Score: Numerical sentiment score

Outputs were merged into the dataset for deeper insight.

📊 Visualizations & Dashboard
A Power BI dashboard was created to visualize:

⭐ Average Rating per Event

📊 Rating Distribution

😀 Sentiment Distribution

📝 Feedback Table

🔍 Event-wise Satisfaction Trends

PBIX File:
[➡️ Download Power BI Dashboard](https://drive.google.com/file/d/1bBiUcBB3doGOFcQbBSkTj9YbcBOiJD5y/view?usp=drive_link)                                                             

🛠 Tools & Technologies
Tool	Purpose
Google Colab / Jupyter Notebook	Code execution
Pandas	Data cleaning & preprocessing
TextBlob / VADER	Sentiment analysis
Matplotlib / Seaborn	Visualizations
Power BI Desktop	Dashboard creation
CSV File	Feedback dataset

📈 Key Insights (Examples)
Technical workshops received the highest ratings

Comments show students appreciate hands-on sessions

Cultural events show mixed sentiment due to crowd management

Most common suggestions: better organization, more time, improved communication

📸 Screenshots
<img width="1309" height="730" alt="Screenshot (354)" src="https://github.com/user-attachments/assets/ef375d67-4a90-4f82-a032-242378a83970" />


🎯 Final Outcome
This project showcases how combining data cleaning, visualization, and NLP can help event organizers:

Understand what students liked or disliked

Improve the quality of future events

Prioritize event planning based on insights# FUTURE_DS_03

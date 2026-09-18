📱 Smartphone Usage & Addiction Analysis Dashboard
An interactive Power BI dashboard for analyzing smartphone usage behavior, screen time, smartphone addiction, sleep, stress, social media usage, gaming, notifications, and academic/work impact.
The project is built in Microsoft Power BI and uses a smartphone-usage dataset to transform user-level behavioral data into interactive reports and insights.

📊 Project Overview
Excessive smartphone usage can affect sleep, productivity, stress levels, and academic/work performance. This dashboard explores these relationships through interactive visualizations and KPIs.
Key questions explored
How much time do users spend on their smartphones?
What patterns are associated with higher smartphone addiction?
How do screen time and sleep hours vary across age groups?
How do social media and gaming usage contribute to overall smartphone usage?
Is smartphone usage associated with stress levels?
How does smartphone usage affect academic/work activities?
How do usage patterns differ by gender?
Which user groups show higher levels of smartphone dependency?

🛠️ Tools & Technologies
Microsoft Power BI
Power Query – data preparation and transformation
DAX – calculated measures and analytical metrics
Data Modeling – organizing fields and analytical relationships
Interactive Visualizations – charts, KPI cards, filters, and tables

📁 Project File
File
Description
Smartphone.pbix
Main Power BI report containing the data model, calculations, and interactive dashboards

📈 Dashboard Pages
The Power BI report contains multiple report pages, including a main dashboard and detailed analytical views.
1. Dashboard
The main dashboard provides a high-level overview of smartphone usage and addiction indicators.
Key metrics include:
User count
Daily screen time
Social media usage
Gaming hours
Sleep hours
Weekend screen time
Notifications per day
App opens per day
Work/study hours

2. Usage & Demographic Analysis
This section examines smartphone behavior across demographic groups.
Analysis includes:
Gender
Age
Age groups
Daily screen time
Weekend screen time
Social media hours
Gaming hours
Sleep hours

3. Addiction Analysis
The report analyzes smartphone addiction using variables such as:
Addiction level
Addicted status
Addicted label
Screen-time behavior
App usage
Social media usage
Gaming behavior

4. Well-being & Productivity Analysis
The dashboard also explores behavioral indicators related to:
Stress level
Sleep duration
Work/study hours
Academic/work impact
Smartphone usage intensity
Interactive filters allow users to investigate these relationships across different user segments.

🔍 Key Data Fields
The report uses smartphone-usage variables such as:
Category
Fields
User
user_id, gender, age, Age Group
Smartphone Usage
daily_screen_time_hours, weekend_screen_time, app_opens_per_day, notifications_per_day
Activities
social_media_hours, gaming_hours
Lifestyle
sleep_hours, work_study_hours
Behavioral Indicators
stress_level, addiction_level, Addicted Status, High Screen Time user
Impact
academic_work_impact
Labels
addicted_label

📐 Analysis & Measures
The report includes analytical calculations and aggregations for metrics such as:
Average daily screen time
Average weekend screen time
Average sleep hours
Average social media hours
Average gaming hours
Average app opens per day
Average notifications per day
Average work/study hours
User counts
Addiction-level distributions
Screen-time patterns by age group and gender

🎯 Interactive Features
The report is designed for interactive exploration using Power BI features such as:
Slicers and filters
Drill-down analysis
Cross-filtering between visuals
KPI cards
Category comparisons
Demographic segmentation
Addiction-level analysis
Users can select different demographic or behavioral categories to dynamically explore the underlying patterns.

🚀 How to Use
Prerequisites
Install Microsoft Power BI Desktop.
Steps
Clone this repository:
git clone https://github.com/<your-username>/<repository-name>.git
Open the project folder.
Open:
Smartphone.pbix
If Power BI prompts you for data-source credentials or paths, update the data-source settings as required.
Use the report tabs and slicers to explore the analysis.

📂 Recommended Repository Structure
smartphone-usage-analysis/
│
├── Smartphone.pbix
├── README.md
└── screenshots/
    ├── dashboard.png
    ├── usage-analysis.png
    └── addiction-analysis.png

Screenshots are optional but recommended for showcasing the dashboard on GitHub.

💡 Insights This Dashboard Can Support
The dashboard can be used to investigate relationships between smartphone usage and behavioral indicators, including:
Screen time vs. sleep
Screen time vs. stress
Social media usage vs. addiction level
Gaming usage vs. addiction level
Age group vs. screen time
Addiction level vs. sleep
Smartphone usage vs. academic/work impact
Usage behavior by gender
The dashboard is intended for exploratory analysis and does not establish causal relationships between smartphone usage and health, behavioral, or productivity outcomes.

📌 Project Goals
Build an interactive Power BI dashboard
Practice data cleaning and transformation
Develop meaningful DAX measures
Apply data modeling concepts
Identify patterns in smartphone usage
Present behavioral data through clear visual storytelling
Create a portfolio-ready business intelligence project

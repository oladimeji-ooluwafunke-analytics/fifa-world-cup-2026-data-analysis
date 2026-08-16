FIFA World Cup 2026 Data Analysis

Project Overview

This project is an end-to-end FIFA World Cup 2026 data analysis project developed in Power BI to explore tournament performance, 
team performance, player performance, fan engagement, and financial impact.

The project focuses on transforming structured football data into interactive dashboards that answer specific 
analytical questions.

The analysis was organized into four dashboard pages:

1. Tournament Overview
2. Team Analysis
3. Player Analysis
4. Fan Engagement & Financial Analysis


Project Objectives

The main objective was to use data analysis and visualization to understand:

* Overall tournament performance
* Team performance across key match statistics
* Individual player performance
* Fan engagement and audience reach
* Financial trends associated with the tournament

Rather than creating visuals without context, each dashboard was designed around specific analytical questions.
Dashboard 1: Tournament Overview

Purpose

Give executives a quick summary of the tournament.

KPIs

* Total Matches
* Total Goals
* Total Teams
* Total Players

Analysis Questions

The dashboard was designed to answer:

* How many matches were played?
* How many goals were scored?
* Which tournament stage had the most goals?
* How were goals distributed between home and away teams?

Visual Analysis

1. Goals by Tournament Stage
Compares goal production across different stages of the tournament.

2. Matches by Tournament Stage
Shows how matches were distributed across tournament stages.

3. Home Goals vs Away Goals
Compares goals scored by home and away teams.

4. Goal Events Breakdown
Provides a comparison of Goals, Assists, Yellow Cards and Red Cards.

Slicers

* Tournament Stage
* Team
  
Dashboard 2: Team Analysis
Analyze team performance.
KPIs
* Average Possession
* Total Corners
* Total Saves
* Total Fouls

Analysis Questions
The dashboard was designed to answer:

* Which team scored the most goals?
* Which team dominated possession?
* Which team committed the most fouls?
* Which goalkeeper made the most saves?

Visual Analysis

1. Goals by Team
Compares goals scored across teams.

2. Average Possession by Team
Shows how possession differed between teams.

3. Corners by Team
Compares the number of corners recorded by each team.

4. Saves by Team
Shows goalkeeper saves at team level.

5. Fouls by Team
Compares fouls committed by teams.

6. Offsides by Team
Shows the number of offsides recorded for each team.

Slicer
* Team

Dashboard 3: Player Analysis
Analyze player performance.
KPIs
* Total Assists
* Total Yellow Cards
* Total Red Cards
* Average Market Value

Analysis Questions

The dashboard was designed to answer:

* Who scored the most goals?
* Who provided the most assists?
* Which position contributed the most goals?
* Which position has the highest average market value?

Visual Analysis

1. Top Scorers
Identifies the players with the highest number of recorded goals.

2. Top Assist Providers
Ranks players based on recorded assists.

3. Goals by Position
Compares goal contributions across player positions.

4. Market Value by Position
Compares average market value across positions.

5. Average Height by Position
Compares the average player height across positions.

Slicers

* Team
* Position
Dashboard 4: Fan Engagement & Financial Analysis
Purpose: Show the commercial impact of the tournament.
KPIs
* Total Attendance
* TV Viewers
* Digital Views
* Total Revenue

Analysis Questions

The dashboard was designed to answer:

* Which country had the highest engagement?
* How many people watched the tournament?
* How has FIFA revenue changed over time?

Visual Analysis

1. Attendance by Country
Compares attendance recorded across countries.

2. TV Viewers by Country
Compares television viewership across countries.

3. Digital Views by Country
Compares digital views across countries.

4. Revenue by Year
Compares recorded revenue across the available years.

5. Revenue Trend
Shows the direction of recorded revenue over time.
Data Analysis Process

The project followed an end-to-end analytical workflow:

Data → Cleaning → Transformation → Data Modelling → DAX → Visualization → Analysis → Insights

Data Preparation

The datasets were reviewed and prepared before analysis.

Data Modelling

Fact and dimension tables were structured to support analysis across matches, teams, players, events, 
fan engagement and financial information.

DAX

DAX measures were created for the KPIs and analytical calculations required throughout the dashboards.

One important part of the process was understanding how relationships between tables affected calculations. For example, player-level event analysis required careful handling of the relationship between the player dimension and match-event data.

Visualization

Visuals were selected based on the question being answered.

For example:

* Bar charts for comparisons
* Column charts for categorical comparisons
* Line charts for revenue trends
* Cards for high-level KPIs
* Slicers for interactive filtering


Key Analytical Lessons

One of my biggest takeaways from this project was that building a dashboard is not the same as doing data analysis.

The analysis required me to understand:

* What each table represents
* What one row represents
* How tables relate to one another
* Which aggregation is appropriate
* When to use a column versus a measure
* How filters affect calculations
* How to validate unexpected results
* How to translate analytical questions into appropriate visuals

For example, during the player analysis, an initial assist calculation produced unrealistic results. Instead of accepting the visual, I traced the calculation back to the underlying relationship between the player and match-event tables and adjusted the DAX accordingly.

This reinforced the importance of data validation before presenting insights.


Insights

The insights section should contain your actual findings from the completed dashboard, 
rather than generic football statements.

For example:

Tournament Performance

The tournament overview provides a high-level picture of matches, goals and goal events across the different
tournament stages.

Team Performance

The team analysis highlights differences in goals, possession, corners, saves, fouls and offsides across teams.

Player Performance

The player analysis identifies the leading goal scorers and assist providers, while also showing how goals and market value vary across positions.

Fan Engagement & Financial Performance

The final dashboard shows differences in attendance, television viewership and digital engagement across countries, alongside the revenue pattern across the available financial periods.

All findings are based on the project dataset.

That last sentence is particularly important because we discovered during the project that some dataset statistics
differed from external FIFA statistics. We should not silently present the dataset values as official FIFA figures.


Recommendations

Based on the analysis, the project can support several areas of decision-making:

1. Use multiple engagement channels

Attendance, TV viewership and digital views should be analysed together because audience engagement can differ by market and platform.

2. Identify high-engagement markets

Countries demonstrating strong engagement can be considered for targeted marketing, digital campaigns and commercial partnerships.

3. Use player analytics for commercial decisions

Player performance and market value can provide useful information for sponsorship, promotional content and player-focused 
campaigns.

4. Monitor performance across tournament stages

Goals, matches and other match statistics can be compared across tournament stages to identify where performance patterns 
change.

5. Track financial trends over time

Revenue trends can help stakeholders understand how the financial impact recorded in the dataset has changed across
tournament periods.
Tools Used

* Power BI
* DAX
* Power Query
* Excel
* GitHub

Portfolio Development

I built this project as part of my transition into data analytics and to develop a portfolio that demonstrates more than technical dashboard creation.

The project allowed me to practice the complete process of taking data from structured tables to:

Questions → Analysis → Calculations → Visualization → Insights → Recommendations

The goal was to build a project that demonstrates both technical Power BI skills and analytical thinking.

# FIFA World Cup 2026 Data Analysis

## Power BI | DAX | Data Modelling | Data Visualization | Football Analytics

An end-to-end data analytics project exploring the FIFA World Cup 2026 through four interactive Power BI dashboards.
This project analyzes tournament performance, team performance, player performance, fan engagement, and financial trends. Each dashboard was designed around specific analytical questions to transform raw data into meaningful insights.

## The project follows the complete analytics workflow:

Data → Cleaning → Transformation → Data Modelling → DAX → Analysis → Visualization → Insights → Recommendations

# 1. Project Overview

The objective of this project was to analyse FIFA World Cup 2026 data and develop an interactive Power BI reporting solution that provides both high-level tournament insights and detailed performance analysis.
## The project was divided into four analytical areas:
1. Tournament Overview
2. Team Analysis
3. Player Analysis
4. Fan Engagement & Financial Analysis

The dashboards were designed to allow users to explore the data through KPIs, charts and interactive slicers.
The analysis focuses on both sporting performance and the broader commercial impact of the tournament.

# 2. Business & Analytical Questions
The dashboards were designed around specific questions rather than simply displaying available data.
## Tournament Overview
Purpose : Give executives a quick summary of the tournament.

## Questions
* How many matches were played?
* How many goals were scored?
* Which tournament stage had the most goals?
* How were goals distributed between home and away teams?

## Team Analysis
Analyze team performance.

## Questions
* Which team scored the most goals?
* Which team dominated possession?
* Which team committed the most fouls?
* Which goalkeeper made the most saves?
  
## Player Analysis
Analyze player performance.

## Questions
* Who scored the most goals?
* Who provided the most assists?
* Which position contributed the most goals?
* Which position has the highest average market value?
  
## Fan Engagement & Financial Analysis
Show the commercial impact of the tournament.

## Questions
* Which country had the highest engagement?
* How many people watched the tournament?
* How has FIFA revenue changed over time?

# 3. Dataset & Data Model
The project uses multiple related datasets covering tournament information, teams, players, match statistics, match events, fan engagement and financial information. The Power BI model was structured using fact and dimension tables to support analysis across different levels of the tournament.
## Key Tables
## Dimension Tables
* Dim_Players
* Dim_Teams
* Dim_TournamentStages

Dimension tables provide descriptive information used to filter and categorize the analysis.

## Fact Tables
* Fact_Matches
* Fact_Match_team_stats
* Fact_MatchEvents
* Fact_FanEngagement
* Fact_FinancialImpact

Fact tables contain measurable events and statistics used throughout the dashboards.

## Data Modelling
Relationships between the fact and dimension tables were established to allow the same data model to support tournament, team, player, engagement and financial analysis. Understanding these relationships was particularly important when calculating player-level statistics from match-event data.

# 4. Data Preparation
Before building the dashboards, the datasets were reviewed and prepared for analysis, the preparation process included:
* Reviewing the structure of the datasets
* Identifying relevant tables and columns
* Cleaning and transforming data
* Checking data types
* Preparing fields for analysis
* Structuring relationships between tables
* Preparing the data model for Power BI
* Validating calculated results against the underlying data

Power Query was used as part of the data preparation and transformation process.The objective was to create a structured model that could support reliable calculations and interactive analysis.

# 5. Dashboard Analysis

## 5.1 Tournament Overview
Purpose : The Tournament Overview provides an executive-level summary of the tournament.

## KPIs
* Total Matches
* Total Goals
* Total Teams
* Total Players

#  Visual Analysis
## Goals by Tournament Stage
  
 Shows how goals were distributed across the different tournament stages.
 
##  Matches by Tournament Stage
  
 Shows the distribution of matches across tournament stages.
 
## Home Goals vs Away Goals
  
Compares goals scored by home and away teams.

## Goal Events Breakdown
Provides an overview of recorded:
* Goals
* Assists
* Yellow Cards
* Red Cards
## Slicers
* Tournament Stage
* Team

## Questions Answered
* How many matches were played?
* How many goals were scored?
* Which stage had the most goals?
* How were goals distributed between home and away teams?

# 5.2 Team Analysis
Purpose : The Team Analysis dashboard focuses on team-level performance.
## KPIs
* Average Possession
* Total Corners
* Total Saves
* Total Fouls

## Visual Analysis
##  Goals by Team
Compares the number of goals scored by teams.

## Average Possession by Team
Shows how possession was distributed across teams.

## Corners by Team
Compares the number of corners recorded by each team.

## Saves by Team
Shows the number of saves recorded at team level.

## Fouls by Team
Compares fouls committed by teams.

##  Offsides by Team
Shows the number of offsides recorded by each team.

## Slicer
* Team
## Questions Answered
* Which team scored the most goals?
* Which team dominated possession?
* Which team committed the most fouls?
* Which goalkeeper made the most saves?

# 5.3 Player Analysis
The Player Analysis dashboard focuses on individual player performance and player characteristics.
## KPIs
* Total Assists
* Total Yellow Cards
* Total Red Cards
* Average Market Value

# Visual Analysis
## Top Scorers

Identifies players with the highest number of recorded goals.

## Top Assist Providers

Ranks players according to recorded assists.

## Goals by Position

Compares goal contributions across playing positions.

## Market Value by Position

Compares average player market value across positions.

## Average Height by Position

Compares average player height across playing positions.

## Slicers
* Team
* Position

## Questions Answered
* Who scored the most goals?
* Who provided the most assists?
* Which position contributed the most goals?
* Which position has the highest average market value?

# 5.4 Fan Engagement & Financial Analysis
This dashboard examines the audience reach and financial side of the tournament.

## KPIs
* Total Attendance
* TV Viewers
* Digital Views
* Total Revenue

# Visual Analysis

## Attendance by Country

Compares recorded attendance across countries.

## TV Viewers by Country

Compares television viewership across countries.

## Digital Views by Country

Compares digital views across countries.

## Revenue by Year

Compares recorded revenue across the available financial periods.

## Revenue Trend
Shows how the recorded revenue changes over time.

Questions Answered
* Which country had the highest engagement?
* How many people watched the tournament?
* How has FIFA revenue changed over time?

# 6. Key Insights
The analysis produced several observations across the four dashboards.
## Tournament Performance
The tournament overview provides a consolidated view of match activity, goal production and goal-event distribution across tournament stages. The analysis allows users to compare how goal production changes throughout the tournament and examine the balance between home and away goals.

## Team Performance
The team analysis highlights differences in performance across goals, possession, corners, saves, fouls and offsides, This allows teams to be compared across both attacking and defensive indicators rather than relying on goals alone.

## Player Performance
The player analysis identifies leading goal scorers and assist providers while also examining how goals and player characteristics vary by position. The analysis also shows differences in average market value between playing positions.

## Fan Engagement
The fan engagement analysis demonstrates that audience behaviour varies across countries and across engagement channels.

Attendance, TV viewership and digital views provide different perspectives on tournament reach.

## Financial Performance
The financial dataset shows an upward revenue pattern across the available periods. Recorded revenue in the dataset increased from $1.6B in 2002 to $13B in 2026, with the strongest increase occurring between 2022 and 2026.

Note: Financial figures and other statistics presented in this project are based on the dataset used for the analysis and should not automatically be interpreted as independently verified official FIFA figures.

# 7. Recommendations
Based on the analysis, several recommendations can be considered;

## 1. Develop Market-Specific Engagement Strategies
Audience engagement varies by country and platform. Marketing strategies should therefore be adapted to the behaviour of individual markets rather than applying one strategy globally.

## 2. Combine Traditional and Digital Engagement

TV viewership and digital views provide different perspectives on audience behaviour. Combining both channels can provide a more complete understanding of tournament reach.

## 3. Identify High-Engagement Markets

Countries demonstrating strong performance across attendance, television viewership and digital engagement can be prioritized for targeted campaigns and commercial opportunities.

## 4. Use Player Analytics for Commercial Decisions

Player performance, goals, assists and market value can provide useful information for sponsorship opportunities, promotional campaigns and player-focused content strategies.

## 5. Monitor Revenue Trends

Tracking revenue across tournament periods can help stakeholders identify changes in financial performance and investigate the factors associated with major increases.

## 6. Use Multiple Performance Indicators

Team performance should not be evaluated using goals alone. Possession, corners, saves, fouls and offsides provide additional context when assessing overall performance.

# 8. Power BI Features Used

The project used several Power BI capabilities, including:

* Interactive dashboards
* KPI cards
* Slicers
* Bar charts
* Column charts
* Donut charts
* Line charts
* Tables
* Filters
* Top N analysis
* Data labels
* Custom formatting
* DAX measures
* Data modelling
* Relationships between fact and dimension tables

## DAX

DAX was used to create analytical measures for the dashboards, including calculations related to:

* Goals
* Assists
* Cards
* Possession
* Corners
* Saves
* Fouls
* Attendance
* TV viewers
* Digital views
* Revenue
* Market value
* Position-level analysis

# 9. Challenges & What I Learned

This project was not only about building visuals. It also required understanding how the data and calculations worked behind the dashboard.

## Data Modelling

One of the important challenges was understanding how fact and dimension tables interact and how relationships affect calculations.

## DAX

Creating measures required understanding the difference between calculated results and raw columns, as well as choosing the appropriate aggregation for each analysis.

## Relationship Validation

During player analysis, an assist calculation produced results that needed further investigation. Instead of changing the result simply because it differed from an external statistic, the calculation was traced back to the underlying dataset and table relationships.

## Data Validation

Another important lesson was identifying differences between the project dataset and external statistics. For this reason, the project uses the dataset as the primary source of analysis and clearly distinguishes dataset-based results from independently verified external statistics.

## Visualization

Choosing the correct visual also required consideration of the question being answered.

For example:

* Bar charts were used for category comparisons.
* Column charts were used for comparisons across categories or years.
* Line charts were used to show trends over time.
* KPI cards were used for high-level metrics.
* Slicers were used to allow interactive exploration.

## Conclusion

The biggest lesson from the project was that data analysis is more than dashboard design. The process involves understanding the data, asking the right questions, selecting appropriate calculations, validating the results and communicating the findings clearly.

## 10. Dashboard Screenshots

Tournament Overview


Team Analysis

Player Analysis

Fan Engagement & Financial Analysis



# 11. Tools & Technologies

* Microsoft Power BI

Used for data modelling, DAX calculations, interactive visualization and dashboard development.

* Power Query

Used for data preparation and transformation.

* Microsoft Excel

Used for initial data review and preparation.

* DAX

Used to create measures and analytical calculations.

* GitHub

Used to document and present the project as part of my data analytics portfolio.

# 12. Portfolio Development

I developed this project as part of my data analytics portfolio to demonstrate my ability to move beyond individual technical tasks and complete an end-to-end analytical project.

The project demonstrates my experience with:

* Data preparation
* Data transformation
* Data modelling
* DAX
* KPI development
* Data visualization
* Interactive dashboard design
* Analytical questioning
* Data validation
* Insight generation
* Business recommendations

The goal was to demonstrate that a dashboard is not simply a collection of charts, The dashboard is the final communication layer of a broader analytical process:
Ask → Prepare → Model → Calculate → Analyze → Visualize → Validate → Recommend

## Project Outcome

The final project consists of four interactive Power BI dashboards covering tournament, team, player, fan engagement and financial analysis. The project strengthened my ability to work with multiple related datasets, develop analytical measures, investigate unexpected results and communicate data-driven findings through interactive visualizations.

## Disclaimer

All statistics and financial figures presented in this project are based on the datasets used for the analysis. They are presented for educational and portfolio purposes and should not automatically be interpreted as independently verified official FIFA statistics.



# Author

Oladimeji Oluwafunke 

Data Analyst | Power BI | SQL | Excel | Data Visualization

This project is part of my growing data analytics portfolio.

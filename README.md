# INDIA-GENERAL-ELECTION-RESULTS-ANALYSIS 2024
## 📊 Power BI Dashboard – India General Election Results 2024

⭐ Project Overview

This Power BI project provides an interactive and comprehensive visualization of the 2024 Indian General Election Results.
It focuses on analyzing seat distribution, party performance, alliance dominance, and voter behavior at national, state, and constituency levels.
The dashboards are designed to help political analysts, researchers, policymakers, and citizens gain data-driven insights into the election outcomes.

🎯 Objectives

To visualize national-level election results for NDA, I.N.D.I.A., and Independent/Other parties.
To enable state-wise and constituency-wise performance analysis using interactive maps and visuals.
To provide drill-through analysis for deeper insights at granular levels.
To allow users to export election data for further analysis.

🧭 Dashboard Summary

🏠 Dashboard 1,6: Landing Page

Acts as the navigation hub of the report.
Features:
Clickable cards for quick access to:
Overview Analysis
State Demographics
Political Landscape by State
Constituency Analysis
Home button on every page for easy return navigation.
Clean, responsive design optimized for multiple screen sizes.
Icon-based UI and hover effects for better interactivity.

📊 Dashboard 1: Overview Analysis

Provides a high-level summary of the overall election outcome.
Key KPIs:
Total Seats & % Share for:
NDA Alliance
I.N.D.I.A. Alliance
Independent & Other Parties
Party-wise seat distribution with logos.
Bookmark navigation to detailed grid views for each alliance.

Visuals Used:
KPI Cards
Clustered Bar Charts
Matrix/Grid Table with Drill-through Bookmarks
Party Logos for identification



🗺 Dashboard 2: State Demographic Analysis

Focuses on state-level and constituency-level insights.
Features:

1. State-wise Seat Distribution

Total seats, NDA seats, I.N.D.I.A. seats, and majority alliance by state.
Map visualization with tooltips.

2. Winning Candidate & Party by Constituency
Bubble Map showing each constituency (color-coded by alliance).
Drill-through to detailed tables.

3. Top Performing State
Highlights the state with the maximum seats won by either NDA or I.N.D.I.A. alliance.

Visuals Used:
Map Charts
Bubble Maps
Drill-through Tables



🧩 Dashboard 3: Political Landscape by State

Allows users to explore state-wise political distribution interactively.

Key Metrics:
Seats won by:
NDA Alliance
I.N.D.I.A. Alliance
Independent & Other Parties

Visuals Used:
State Map Chart (showing constituencies)
Party-wise Result Table (with alliance info)
Donut Chart (Party-wise Seat Share %)
Dynamic State Filter (slicer)

Use Case:
Helps analyze party dominance and alliance comparison within any selected state.



🗳 Dashboard 4: Constituency Analysis

Provides detailed insights at the constituency level.

Primary KPIs:
Total Votes cast
Total EVM Votes
Total Postal Votes
Total Candidates
Secondary KPIs:
Winning Candidate (Name, Party, Vote Share %)
Runner-Up Candidate

2nd Runner-Up Candidate
Visuals Used:
KPI Cards
Comparison Tables
Drill-through Button (to Details Grid)



📋 Dashboard 5: Details Grid

Acts as a data exploration and export dashboard.

Table Fields:
Constituency Name
Winning & Runner-Up Candidates
Winning Party & Alliance
EVM Votes, Postal Votes, Total Votes
Margin (Vote Difference)

Functionalities:

Drill-through from other dashboards
“Show All Data” bookmark button
Export to Excel feature



⚙ Tools & Technologies Used

Category	Tools/Technologies

Data Visualization	Microsoft Power BI
Data Source	Election Results Dataset (CSV/Excel)
Data Modeling	Power Query Editor (ETL), DAX Measures
Data Analysis	DAX Functions for KPIs & Calculations
Interactivity	Bookmarks, Drill-throughs, Buttons, Filters
Visualization Types	Map Charts, Donut Charts, KPI Cards, Matrix Tables, Bar Charts, Bubble Maps
Design Principles	Clean UI, Responsive Layout, Color-coded alliances (NDA, I.N.D.I.A., Others)



🧮 Key DAX Measures

Some of the main calculated measures include:
Total Seats Won (NDA / I.N.D.I.A. / Others)
% of Total Seats
Vote Share % per Candidate
Total Votes (EVM + Postal)
Margin = Winning Votes – Runner-Up Votes



📈 Insights Generated

NDA secured 292 seats (54%), forming the majority.

I.N.D.I.A. Alliance won 234 seats (43%).

Independent & Other parties secured 17 seats (3%).

State-wise insights show varying regional dominance between alliances.

Constituency-level data highlights voter turnout and competitiveness.



🧰 Project Highlights

✅ Fully interactive Power BI Report
✅ State and Constituency-level Drill-throughs
✅ Alliance-wise, Party-wise, and Candidate-level Insights
✅ Export and Bookmark Functionalities
✅ Professionally Designed Layout (optimized for HR/demo review)



🚀 How to Use

1. Open the Power BI .pbix file or hosted Power BI report link.
2. Navigate via the Landing Page.
3. Explore dashboards interactively using buttons, filters, and tooltips.
4. Use “Drill-through” or “Show Entire Data” for deeper insights.
5. Export data if required for further research.



📁 Folder Structure (Suggested for GitHub)

India-General-Election-Results-2024/
│
├── README.md
├── Dataset/
│   └── Election_Results_2024.csv
├── PowerBI_Report/
│   └── India_Election_Results_2024.pbix
├── Screenshots/
│   ├── Landing_Page.png
│   ├── Overview_Analysis.png
│   ├── State_Demographics.png
│   ├── Political_Landscape.png
│   ├── Constituency_Analysis.png
│   └── Details_Grid.png
└── Documentation/
    └── Problem_Statement.pdf





    
## 📊 SQL Project – India General Election Results Analysis (2024)

📌 Overview

This project focuses on performing an end-to-end SQL analysis of the India General Elections 2024 dataset.
The goal is to extract meaningful insights from constituency-level results, party performance, alliance comparisons (NDA / I.N.D.I.A / Others), voting patterns, and candidate-level details.

The dataset consisted of multiple connected tables:

partywise_results

constituencywise_results

constituencywise_details

statewise_results

states

The entire analysis was performed in SQL Server, including data cleaning, transformation, exploratory analysis, and advanced queries.


## 🔧 Data Cleaning & Preparation

Added a new field: party_alliance

Classified each party into:

NDA

I.N.D.I.A

OTHER

Standardized party names and alliances
Ensured consistency in constituency and state data


## 📈 Exploratory & Advanced Analysis

The project covers:

Total seats, state-wise seats, party-wise seats

Alliance-wise performance (NDA vs I.N.D.I.A vs Others)

Candidate-level votes, vote margins

EVM vs Postal vote breakdown

Winning vs runner-up analysis

State-level election summaries

Use of CTEs, Window Functions, ROW_NUMBER(), CASE WHEN, and Joins

Reusable Stored Procedures for dynamic querying


## ⭐ Key Problem Statements Solved

1. Total seats in India

Counted all parliamentary constituencies.

2. State-wise total seats

Calculated seats per state using multiple joins.

3. Total seats won by NDA

Dynamic calculation using the NDA party list.

4. Seats won by individual NDA parties

5. Total seats won by I.N.D.I.A Alliance

6. Seats won by individual I.N.D.I.A parties

7. Added party_allianz field

Mapped every party to the correct alliance.

8. Which alliance won the most seats?

NDA vs I.N.D.I.A vs Others comparison.

9. State + Constituency level winner details

   For any constituency (ex: Nashik, Maharashtra):

Winning candidate

Party

Alliance

Votes received

Winning margin

10. EVM vs Postal Vote Distribution

For each constituency:

Candidate

Party

EVM votes

Postal votes


11. Most successful party in each state

12. Alliance-wise seat distribution per state

13. Top 10 candidates by EVM votes

Using Window Functions.

14. Top 10 candidates by Postal votes

15. Winner & Runner-up per constituency

Implemented with CTE + ROW_NUMBER() OVER()

16. State Election Summary (Example: Maharashtra)

Includes:

Total seats

Total candidates

Total parties

Total votes

EVM vote sum

Postal vote sum


17. Created Dynamic Stored Procedures

GetConstituencyVotes

GetPartySeatsByState

GetTopCandidatesByState

GetElectionSummaryByState


## ⭐ Final Summary

This SQL project provides a complete, end-to-end analytical view of the India General Election Results 2024. It covers the entire workflow—from data cleaning and transformation to advanced querying and insight generation.

By integrating multiple datasets such as party-wise results, constituency details, and state-level summaries, the project delivers a structured and scalable analytical framework. Advanced SQL techniques including window functions, CTEs, conditional logic, joins, and stored procedures were used to extract actionable insights on party performance, alliance strength, candidate competitiveness, and voting patterns (EVM vs Postal).

The analysis supports a wide range of decision-making needs, enabling users to explore:

Overall and state-wise seat distribution

Alliance-wise performance (NDA vs I.N.D.I.A vs Others)

Candidate-level vote margins

Detailed constituency outcomes

State election summaries

High-performing parties and candidates


This project serves as a robust backend foundation for the accompanying Power BI dashboard, demonstrating strong skills in SQL data modeling, analytical logic, and election data interpretation. It highlights the ability to convert raw data into meaningful, structured insights that can support researchers, analysts, and data-driven applications.

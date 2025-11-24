# INDIA-GENERAL-ELECTION-RESULTS-ANALYSIS---2024
## 📊 1. Power BI Dashboard – India General Election Results 2024

📘 Project Overview

This Power BI project provides an interactive and comprehensive visualization of the 2024 Indian General Election Results.
It focuses on analyzing seat distribution, party performance, alliance dominance, and voter behavior at national, state, and constituency levels.
The dashboards are designed to help political analysts, researchers, policymakers, and citizens gain data-driven insights into the election outcomes.

🎯 Objectives

To visualize national-level election results for NDA, I.N.D.I.A., and Independent/Other parties.
To enable state-wise and constituency-wise performance analysis using interactive maps and visuals.
To provide drill-through analysis for deeper insights at granular levels.
To allow users to export election data for further analysis.

🧭 Dashboard Summary

🏠 Dashboard 6: Landing Page

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



    
## 🗄 2. SQL Analysis – India General Election Results 2024

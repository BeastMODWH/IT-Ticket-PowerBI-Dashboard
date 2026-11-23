# IT Support Ticket Performance Dashboard

## Project Overview
An interactive Power BI dashboard built to analyze IT support ticket performance, identify bottlenecks, and track escalation rates.

## Situation (The Problem)
IT support teams often rely on scattered spreadsheets to track ticket resolution times. Without a centralized view, it is difficult to identify which issue types cause the biggest bottlenecks or how often tickets are escalated.

## Task (My Role)
I acted as a Data Analyst to build a centralized, interactive Power BI dashboard using simulated IT support ticket data (30 records). The goal was to provide the IT Manager with a clear view of resolution efficiency and escalation rates.

## Action (What I Did)
* **Data Preparation:** Used Power Query to clean the dataset, ensure date formats were accurate, and remove duplicates.
* **Data Modeling:** Created a custom DAX measure (`Avg Resolution Hours`) using `AVERAGEX` and `DATEDIFF` to calculate the exact average time between ticket open and resolution.
* **Visualization:** Designed a 3-part dashboard:
    * A **KPI Card** to show the overall average resolution time (55.2 hours).
    * A **Bar Chart** to identify bottlenecks by issue type (VPN and Outlook take the longest).
    * A **Donut Chart** to show the escalation rate (26.17% escalated vs. 73.83% resolved).
* **Interactivity:** Added a Priority slicer to allow dynamic filtering.

## Result (The Insight)
The dashboard revealed that **VPN and Outlook tickets** are the biggest bottlenecks, taking over 60 hours on average to resolve—nearly double the time of Password Resets (32 hours). Additionally, **26% of tickets are escalated**, indicating a potential gap in first-line support training. 

## Business Value
By using this dashboard, an IT Manager can prioritize training for VPN and Outlook issues. If they reduce the VPN resolution time by just 20%, they could significantly improve overall team SLAs.

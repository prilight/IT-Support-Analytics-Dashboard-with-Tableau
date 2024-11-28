 # IT Support Analytics Dashboard

 ## Table of Contents
 - [Project Overview](#project-overview)
 - [Key Features](#key-features)
 - [Tools Used](#tools-used)
 - [Dataset](#dataset)
 - [Key Insights](#key-insights)
 - [Future Improvements](#future-improvements)
 - [Live Dashboard](#live-dashboard)
   
## Project Overview
This project leverages Tableau to analyze IT ticketing data with the goal of identifying key drivers of customer satisfaction and operational inefficiencies. The dashboard provides actionable insights for improving IT support services.

## Key Features
- **Heatmap:** Visualizes satisfaction and days open by requestor seniority to highlight disparities in support quality.
- **Scatter Plot:** Analyzes critical-severity tickets, showing trends between d hays open and satisfaction scores to identify inefficiencies.
- **Interactive Dashboard:** Allows users to filter by ticket type, severity, and requestor seniority for deeper analysis.

## Tools Used
- **Data Cleaning:** Excel
- **Visualization:** Tableau
- **Documentation:** Markdown (GitHub)

## Dataset
The dataset includes:
- `TicketID`: Unique identifier for each ticket.
- `Requestor`: The ID of the person raising the ticket.
- `RequestorSeniority`: The requestor's organizational level (Junior, Regular, Senior, Management).
- `ITOwner`: ID of the IT personnel assigned to the ticket.
- `FiledAgainst`: The department or system the ticket pertains to.
- `TicketType`: Whether the ticket is an Issue or Request.
- `Severity`: The severity level of the ticket (Minor, Normal, Critical, etc.).
- `Priority`: Priority assigned to the ticket (Low, High, Unassigned, etc.).
- `DaysOpen`: Number of days the ticket remained unresolved.
- `Satisfaction`: Customer satisfaction score for the ticket.

## Key Insights
- **Requestor Trends:** Junior-level employees experience the highest dissatisfaction and longest ticket resolution times.
- **Severity Insights:** Critical tickets receive the least satisfaction despite their importance, highlighting operational gaps.
- **Ticket Types:** Requests show higher satisfaction scores compared to Issues, indicating potential disparities in handling.

## Future Improvements
- Incorporate advanced regression analysis to quantify relationships between variables.
- Expand the dataset to include more metadata, such as ticket resolution methods or team workload.
- Automate the dashboard with real-time data feeds for continuous monitoring.
  
## Live Dashboard
Explore the live interactive dashboard on [Tableau Public](https://public.tableau.com/app/profile/precious.gift.joshua/viz/ITSupporttoImproveCustomerSatisfaction/Dashboard1).


# Agent Performance Dashboard

## Project Overview
This Power BI dashboard visualizes call center agent performance based on key metrics such as answered calls, resolved issues, call response speed, and customer satisfaction ratings. It provides insights to improve service quality and efficiency.

## Features
- Displays agent names and their call-handling statistics.
- Tracks answered and resolved calls using Yes/No indicators.
- Measures average speed of answering calls.
- Computes agent performance ratings based on customer feedback.

## Data Processing
### Power Query (M Code)
- Imports and cleans the dataset.
- Converts Yes/No responses to numerical values for analysis.
- Standardizes data types for accurate reporting.

### DAX Measures
- **Total Answered Calls**: Counts the number of answered calls.
- **Total Resolved Calls**: Counts the number of resolved cases.
- **Average Call Speed**: Computes the average response time.
- **Average Satisfaction**: Calculates the average customer rating.

## Visualizations
- **Table**: Displays agent-wise performance metrics.
- **KPIs**: Show key statistics like total answered and resolved calls.
- **Line Chart**: Illustrates call speed trends over time.
- **Bar Chart**: Compares agent satisfaction ratings.

## How to Use
1. Open the provided Power BI file (`Agent Performance Dashboard.pbix`).
2. Refresh the dataset to load the latest data.
3. Explore different visuals and filters to analyze agent performance.
4. Use insights to optimize call center operations.

## Requirements
- Microsoft Power BI Desktop
- Source data file (e.g., `AgentPerformanceData.xlsx`)

## Author
[@muddasanirajkumar]

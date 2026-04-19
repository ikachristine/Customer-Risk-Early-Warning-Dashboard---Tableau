# Customer Risk Early Warning Dashboard

## Project Overview

This project aims to identify early warning signals of customer churn using transaction recency and revenue contribution analysis.
Instead of waiting for annual churn, this dashboard focuses on behavioral signals — particularly inactivity (recency) — to proactively detect customers at risk of non-renewal.
The analysis builds a risk segmentation framework and identifies high-value customers that require immediate attention.

##  Business Problem

The company currently lacks:

- A clear definition of "at-risk" customers
- Visibility into revenue exposure from inactive customers
- Prioritization strategy for follow-up by Customer Success / Sales team

Without early detection, revenue loss risk increases.

##  Objectives

- Define customer risk based on transaction recency
- Segment customers into actionable risk buckets
- Identify High Value At Risk customers
- Measure revenue exposure
- Analyze potential risk drivers (discount & margin)
- Provide watchlist for retention action

## Risk Segmentation Framework

Customers are classified into 4 quadrants:

| Quadrant | Description |
|----------|-------------|
| High Value Active | High revenue, recently active |
| Low Value Active | Low revenue, recently active |
| High Value At Risk | High revenue, inactive beyond threshold |
| Low Value At Risk | Low revenue, inactive beyond threshold |

Risk threshold parameter is dynamically adjustable.

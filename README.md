# AI Jobs Trends Dashboard

This project analyzes digital and AI labor-market trends across a globally balanced group of countries by comparing indicators of workforce demand and workforce supply. It combines public development and labor data to build a practical dashboard that highlights where digital demand is rising faster than talent capacity.

## Overview

Organizations and policymakers need better ways to understand whether labor markets are keeping pace with digital and AI transformation. Because globally consistent AI job posting data is not always openly available, this project uses a reproducible proxy-based framework to estimate digital and AI demand versus supply.

The notebook pulls, cleans, merges, and analyzes public data to build a country-year view of labor-market readiness.

## Project Goal

The goal of this project is to create a decision-support dashboard that shows where digital and AI demand appears to be outpacing workforce supply, helping leaders identify skills gaps, talent bottlenecks, and workforce development priorities.

## Scope

The analysis uses a globally balanced set of countries across income levels, including examples such as:

- High-income countries
- Upper-middle-income countries
- Lower-middle-income countries

This allows for cross-country comparisons of digital readiness, employment capacity, and workforce gaps.

## Data Sources

This project uses public data sources, including:

- World Bank World Development Indicators (WDI)
- World Bank Data360 / ILO ICT employment data

These datasets are used to approximate labor-market demand and supply in a structured and reproducible way.

## Method

The notebook builds three main measures:

### Demand Index
A proxy for digital and AI demand using indicators such as:

- Internet users (% of population)
- Fixed broadband subscriptions
- ICT service exports
- High-technology exports

### Supply Index
A proxy for workforce capacity using indicators such as:

- ICT employment in services and manufacturing
- Tertiary enrollment

### Gap Index
The difference between demand and supply:

- **Gap Index = Demand Index − Supply Index**

This helps identify countries where digital demand may be growing faster than available talent capacity.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Requests
- Plotly / dashboard-style visualizations
- Jupyter Notebook

## What the Notebook Does

This project includes the following steps:

- Pulls public indicator data from online sources
- Cleans and restructures labor and development data
- Merges country-year indicators into a unified analytical dataset
- Standardizes variables and constructs composite demand and supply indices
- Computes a gap measure between labor demand and labor supply
- Produces visualizations and exports a dashboard view for interpretation

## Key Insights

This analysis is designed to highlight patterns such as:

- Countries where digital infrastructure and trade capacity are growing quickly
- Regions where workforce supply is not keeping up with digital demand
- Talent pipeline constraints that may limit future AI and digital growth
- Opportunities for workforce planning, education investment, and policy intervention

## Business and Policy Relevance

This project demonstrates how public labor and economic data can be transformed into a practical decision-support tool. It can help support:

- Workforce planning
- Skills gap analysis
- Economic development strategy
- AI talent pipeline discussions
- Cross-country benchmarking for digital readiness

## Next Steps

Potential future improvements include:

- Integrating direct job-posting data where available
- Adding occupation-level or skill-level analysis
- Expanding the dashboard to more countries and years
- Building a more interactive front-end experience
- Comparing labor-market gaps against business investment trends

## File

- `ai_job_trends_dashboard.ipynb` — notebook containing data collection, cleaning, index construction, visualization, and analysis

## Note

This project was originally developed as graduate coursework and is being shared as part of my technical portfolio to demonstrate applied analytics, labor-market analysis, dashboard thinking, and business-focused AI insight generation.

## Author

Christopher Paul

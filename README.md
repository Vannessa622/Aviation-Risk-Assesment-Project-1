# Aviation Risk Assessment Project
## Project Overview
This project aims to analyze historical aviation incident data to identify aircraft with the lowest risk for a company entering the aviation industry. The analysis focuses on key factors like aircraft make, flight purpose, weather conditions, and the number of engines to provide actionable insights for safe and strategic aircraft acquisition.

The findings from this project will assist the company’s aviation division in making informed decisions about which aircraft to purchase for commercial and private operations.

## Data Source
The dataset used for this project contains historical aviation incident data with the following key columns:

Event.Id: Unique identifier for each event

Investigation.Type: Type of investigation conducted

Accident.Number: Unique number for each accident

Event.Date: Date of the incident

Location: Incident location (City and State)

Injury.Severity: Severity of injuries (e.g., Fatal, Serious)

Aircraft.damage: Extent of damage to the aircraft

Make: Aircraft manufacturer

Model: Model of the aircraft

Number.of.Engines: Number of engines in the aircraft

Engine.Type: Type of engine used

Purpose.of.flight: Reason for the flight (e.g., Personal, Commercial)

Weather.Condition: Weather conditions during the incident

Total.Fatal.Injuries: Number of fatal injuries

Total.Serious.Injuries: Number of serious injuries

Total.Minor.Injuries: Number of minor injuries

## Process Overview

Data Cleaning: Handled missing values, removed redundant columns, and standardized formats (e.g., converting text to uppercase).

Data Exploration: Explored key patterns and trends in incident occurrences by aircraft make, weather conditions, and flight purpose.

Risk Analysis: Analyzed incidents by factors such as the number of engines, total injuries, and weather conditions to assess risk levels.

Visualizations: Created visualizations using Seaborn, Matplotlib, and Tableau to present the results, including:Incidents by aircraft make,
Risk by weather conditions,
Time series of aircraft incidents,
Total injuries by flight purpose and number of engines.

Dashboard: Built an interactive dashboard in Tableau to allow further exploration of the data and insights.

Here's the link:Here's the link: https://public.tableau.com/app/profile/vannessa.pamela/viz/AviationDataVisualization_17272875805400/AviationDataVisualization

## Key Insights
Personal Flight Risks: Personal flights had the highest occurrence of incidents, highlighting the need for further safety measures in this category.

Impact of Weather: Poor weather conditions significantly increased the risk of incidents, indicating that aircraft with advanced weather navigation systems may offer a lower risk.

Number of Engines: Aircraft with more engines generally showed fewer fatal injuries, suggesting multi-engine planes could be a safer investment.

## Future Improvements
Data Enrichment: Integrating more data sources such as pilot experience, maintenance records, or advanced weather data for improved risk modeling.

Predictive Models: Building predictive models to forecast risk based on historical data.

Real-Time Monitoring: Implementing systems to monitor real-time data on aviation incidents for proactive risk mitigation.

## Instructions for Running the Project
### 1. Prerequisites
Python 3.x

Libraries: Pandas, NumPy, Seaborn, Matplotlib, Tableau (for dashboard)
### 2. Running the Code

To replicate the analysis:

  1.Clone the repository to your local machine.

  2.Ensure the dataset is placed in the working directory.

  3.Install the required libraries via pip

  4.Run the Python scripts to perform data cleaning, exploration, and visualization.

## Contact Information
For further information or questions, feel free to reach out:

Vanessa Pamela

Data Analyst

Email: pamelavannessa131@gmail.com

Phone:0768237430













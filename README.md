# Phase1-project
## Project Overview:

This analysis aims to identify low-risk aircraft for a company venturing into the commercial and private aviation industry. In order to ensure a successful entry into this market, it is crucial to identify the aircraft with the lowest risk. The National Transportation Safety Board (NTSB) accident data (1962-2023) will be used to assess the risk profiles of various aircraft models.

## Goal:

Provide actionable insights to the head of the new aviation division for informed decision-making regarding aircraft acquisition.

Data Source:
National Transportation Safety Board (NTSB) accident data (1962-2023)

Analysis Approach:

Data Wrangling
    Import data using Pandas
    Address missing values
    Standardize date formats
    Identify and address potential outliers and inconsistencies
    Select revelant features:- 
        a) Aircraft Model and Type 
        b) Accident or Incident Type 
        c) Fatalities or Injuries 
        d) Weather conditions
        
Data Analysis
Accident rates: Calculate the accident rates per aircraft model. It is however noted that the total flight hours is missing in the data hence we will use alternative methods to check this analysis

Accident severity: Analyze distribution of accidents by servity for each model

Visualiztion: 
a) Bar charts comparing accidents cross models 
b) Scartterplots to explore relationship between accident types, weather conditions and aircraft models

Deliverables:

Report on aircraft models with the lowest accident rates and severity distribution.
Actionable recommendations for the aviation division head, considering:
    Safety data insights
    Operational needs (range, capacity, fuel efficiency)
    Manufacturer reputation and maintenance requirements
    
Limitations:
NTSB data may not include minor incidents or all contributing factors.
Accident rates are historical and might not predict future risk for newer models.

Next Steps:
Depending on data availability, refine analysis by:
    Including flight hours for accident rate calculations.
    Analyzing contributing factors to accidents for each model.
Explore additional resources: such as Manufacturer safety data and reports.


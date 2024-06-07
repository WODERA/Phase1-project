#  Analyzing Aviation Accident Data for Risk Assessment
## Project Overview:

This analysis aims to show aircraft risk levels based on accident history to give insights to a company venturing into the commercial and private aviation industry. In order to ensure a successful entry into this market, it is crucial to identify the aircraft with the low risk levels. The National Transportation Safety Board (NTSB) accident data (1962-2023) will be used to assess the risk profiles of various aircraft models.

## Goal:

Provide actionable insights to the head of the new aviation division for informed decision-making regarding aircraft acquisition.

## Data Source:
National Transportation Safety Board (NTSB) accident data (1962-2023)

## Analysis Approach

### Data Wrangling
* Import data using Pandas
* Address missing values
* Identify and address potential outliers and inconsistencies
* Select revelant features:- 
   - Aircraft Model and Type
   - Accident or Incident Type
   - Fatalities or Injuries 
              
### Data Analysis
* Accident Injury severity: Analyze distribution of accidents by servity for each model
* Visualiztion:
      - Bar charts comparing accidents count cross models
      - Bar charts and Hit Maps comparing injury severity for the aircraft makes and models

## Deliverables:

* Report on aircraft models with their severity distribution.
* Actionable recommendations for the aviation division head, with recommendations to consider additional information such as:
     - Safety data insights
     - Operational needs (flight range, capacity, fuel efficiency)
     - Manufacturer reputation and maintenance requirements
    
## Limitations:
* NTSB data may not vbe sufficient to give complete recommendations. Factors beyond accident data e.g aircraft maintainnce history,saftey record of specific airline, fuel efficiency, opertional costs, passenger capacity need to be considered
* The data is historical and might not predict future risk for newer models.

# Next Steps:
Depending on data availability, refine analysis by:
* Including flight hours for accident rate calculations.
* Analyzing contributing factors to accidents for each model by exploring additional resources such as Manufacturer safety data and reports.
* Include pilot experience and training in the aviation accident data

<Click here to view the dashboard "https://public.tableau.com/app/profile/wilbroda.odera/viz/AviationAccidentAnalysis_17177485953030/AviationAccidentAnalysis?publish=yes"> </a>


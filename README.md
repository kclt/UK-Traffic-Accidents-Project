# UK Traffic Accidents 2005 
Exploring the a use case of machine learning on UK Traffic Accident data set to classify accident severity

## Introduction
Historically, accidents insurance plans and payments are calculated using actuarial models. Now
with the boom of data collection in insurance industry, we should be able to leverage machine
learning to assist with the insurance industry.
The following project explores a potential usage of machine learning in the insurance industry - to predict the accident severity of a car accident

The target variable is thus accident severity which comes in 3 level:
1. Slight
2. Serious
3. Fatal

Thus we are dealing with a multi-class classification problem/analysis.

Using this prediction results, we can help insurance companies to:
1. Evaluate insurance claims payment
2. Evaluate the underwriting of insurance plan
3. Insurance claim fraud prediction/investigation

## Data 
The <a href = https://data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data> data set <a> is published by UK DoT (Department of Transport), the following analysis is done on a subset of data (Year 2005) as conducting classification analysis with time series becomes quite complex and due to the amount of data, we decided
just to analysis accident information that occurred in the Great Britain in 2005. 
 
 ### Metadata information
 | Variable | Description |
| --- | --- |
| `Accident Index` | Index identifier of accidents |
| `Longitude` | longitude coordinates of accident |
| `Latitude` | latitude coordinates of accident |
| `Accident Severity` | The severity of accident (1 – Slight, 2 - Serious, 3 – Fatal) |
| `Carriageway Hazard` | None - Other object on road - Any animal in carriageway - Pedestrian in carriage - Previous accident - Vehicle load on road    |
| `Date` | The date that accident that occurred in the format DD/MM/YYYY |
| `Day of Week` | The day of the week that accident occurred  |
| `Did Police officer attend scene of accident?` | 1 – No, 2 – Yes, 3, Yes with Ambulance  |
| `Junction Control` | Was there junction control at the location of accident  |
| `Light Conditions` | The lighting condition (Daylight, Darkness - no lighting, Darkness lights lit) |
| `Pedestrian crossing-human control` | Was there pedestrian crossing lights at accident |
| `Pedestrian crossing physical facilities` | Was there pedestrian crossing facilities at accident (e.g. cross-roads)  |
| `Number of Casualties:` | The number of causalities involved in accident |
| `Number of Vehicles:` | The number of vehicles involved in accident |
| `Road Surface Conditions` | The condition of the road during the accident  |
| `Road Type` | The road type where the accident occured (e.g.one way street)  |
| `Speed limit` | The speed limit where the accident occured  |
| `Urban or Rural Area` | Did the accident occur in urban or rural setting |
| `Weather Conditions` | The weather condition when the accident occured  |

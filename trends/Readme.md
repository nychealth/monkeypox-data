# trends/ 

This folder contains files with daily data shown across time. Note that these trend data are published by date of diagnosis, not by date of report. The Health Department recommends against interpreting daily changes to these files as one day’s worth of data, due to the difference between date of diagnosis and date of report.

## Files 

### cases-by-day.csv   
This file contains citywide and borough-specific daily counts of probable and confirmed cases. Cases are aggregated by the date of diagnosis. To address variation in the number of cases diagnosed per day, we have included a 7-day average (mean). This is calculated as the average of number of cases on that day and the previous 6 days.

This file includes data since May 19, 2022 based on the date that the Health Department classifies as the start of the mpox outbreak in NYC (i.e., date of the first laboratory-confirmed case). 

Indicators include: 

| Variable Name | Definition | Timeframe |   
|-----------------|----------------------------------------------------------------------------|------------------------------------------| 
| diagnosis_date | Week-ending date | day |       
| count | Number of people with a positive result on an antibody test | day  |     
| incomplete | Used for display purposes only |        
| case_count_7_day_avg | 7-day average of count of confirmed cases citywide	 | current day and previous 6 days |     
| total | Used for display purposes only | |    

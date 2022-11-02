# Flu-Season_Analysis
A data analytics project using Excel and Tableau to identify regional and seasonal trends of influenza in the US as a part of Data Analytics course at CareerFoundry.

## Objective
Scenario: To help a medical staffing agency prepare for the upcoming flu season by examining trends in influenza and how they can be used to proactively plan for clinic and hospital staffing needs across the country. The objective of this study is to develop insights to assist in preparation of staffing plan in the United States for upcoming influenza season by analyzing death trends and prioritizing states with vulnerable populations.

## Data 
Open source data:
- Influenza deaths by geography, time, age, and gender available [here](https://coach-courses-us.s3.amazonaws.com/public/courses/da_program/CDC_Influenza_Deaths_edited.xlsx), source [CDC](https://wonder.cdc.gov/ucd-icd10.html)
- Population data by geography available [here](https://coach-courses-us.s3.amazonaws.com/public/courses/data-immersion/A1-A2_Influenza_Project/Census_Population_transformed_202101.csv), source US Census Bureau
- Influenza lab test results by state available [here](https://coach-courses-us.s3.amazonaws.com/public/courses/data-immersion/A1-A2_Influenza_Project/CDC_Influenza_Visits.xlsx), source [CDC_Fluview](https://gis.cdc.gov/grasp/fluview/fluportaldashboard.html)

## Tools
- Excel – to analyze by coducting statistical analysis and hypothesis testing, find insights and prepare data for a [project interim report](https://github.com/Smologonova/Flu-Season_Analysis/blob/main/Interim%20report_Flu%20Season.pdf).
- Tableau - to turn data and insights into interactive storytelling, available [here](https://public.tableau.com/app/profile/iryna.smologonova/viz/Preparingforinfluenzaseason/PreparationtoupcominginfluenzaseasonintheUS).

## Result 
[Storytelling in Tableau](https://public.tableau.com/app/profile/iryna.smologonova/viz/Preparingforinfluenzaseason/PreparationtoupcominginfluenzaseasonintheUS?publish=yes)
- Focus on:
- 6 top states with the highest death rate: Alaska, Hawaii, Wyoming, District of Columbia, South and North Dakota, Vermont
- 5 top states with the highest elderly populations:California, Texas, Florida, New York and  Pennsylvania
- the influenza season months: Dec-Mar with a peak in Jan

## Key takeaways
- It is important to consider data limitations and assess the impact of it on the analysis and the result interpretation. As analysis progresses, data limitations may become apparent and should be added to the analysis plan.
- Data mapping helps to match variables between different data sets. Death data and population data by states were mapped using age variable on 10 years ranges starting from age of 5 years old.
- Normalization is a part of data preparation and allows data in different units to be compared using the same units. The flu deaths data was normalized according to state populations by deriving new variables representing flu deaths as a percentage of state population.

# Mid-term-Project
The idea of this project is to segment the neighborhoods of New York City into separate clusters based on total confirmed COVID-19 cases and total confirmed COVID-19 deaths per neighborhood. According to NYC health department, the data provided by Modified ZIP Code Tabulation Areas (MODZCTA) are for cases confirmed by a positive COVID-19 test. The readiness of each neighborhood to tackle the pandemic was also evaluated by examining the total number of beds and total number of ICU beds in Acute care hospitals per neighborhood. This was examined by clustering the neighborhoods based on number of beds and number of ICU beds per 1000 people. 

## Data Sources
1. Hospital bed data was downloaded from the New York State Health department website (New_York_State_Statewide_COVID-19_Hospitalizations_and_Beds.csv)
2. COVID-19 Case rate and Death rate by MODZCTA were obtained from the NYC OpenData Website
3. Population and ZIP Code of most neighborhoods were scrapped from their Wikipedia pages. For neighborhoods missing information on Wikipedia, Population and ZIP Code were gotten from Niche.com
4. Hospital neighborhood information was gotten from Foursquare API

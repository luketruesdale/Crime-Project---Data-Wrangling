# Data folder

## Folders

source data:
https://www.kaggle.com/datasets/michaelbryantds/crimedata
https://www.bls.gov/ 
https://www.usmayors.org/ 
https://www.ballotpedia.org/ 


### raw

Original, unmodified data after downloading, scraping, etc. 

### final

Data after all cleaning, processing, and analyzing.

---

# Data Dictionary

| **Column**                 | **Type**    | **Source**         | **Description**                                       |
|----------------------------|-------------|--------------------|-----------------------------------------------------|
| communityName              | Text        | crimedata.csv      | Name of the community                               |
| state                      | Text        | crimedata.csv      | State where the community is located                |
| population                 | Numeric     | crimedata.csv      | Total population of the community                   |
| householdsize              | Float       | crimedata.csv      | Average size of households in the community         |
| racepctblack               | Float       | crimedata.csv      | Percentage of Black residents                       |
| racePctWhite               | Float       | crimedata.csv      | Percentage of White residents                       |
| racePctAsian               | Float       | crimedata.csv      | Percentage of Asian residents                       |
| racePctHisp                | Float       | crimedata.csv      | Percentage of Hispanic residents                    |
| bulgaries                  | Numeric     | crimedata.csv      | Number of burglary incidents                        |
| larcenies                  | Numeric     | crimedata.csv      | Number of larceny incidents                         |
| arsons                     | Numeric     | crimedata.csv      | Number of arson incidents                           |
| ViolentCrimesPerPop        | Float       | crimedata.csv      | Violent crimes per capita                           |
| HouseholdIncome            | Float       | statistia.com      | Avg Household income of the community               |
| Mayor of Community         | Text        | usmayors.org       | Mayor of largest city by population in community    |
| PoliticalLeaningofMayor    | Text        | usmayors.org       | Political leaning of mayor                          |
| Unemployment Rate          | Float       | bls.gov            | Unemployment rate of largest city by population     |

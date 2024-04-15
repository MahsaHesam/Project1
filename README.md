# Crime Analysis in Victoria
This is a submission for Project 1 of the Data Analytics Boot Camp by Monash University and EdX.

Collaborators:
- AMIN, Muzaffar
- BUI, Vi
- HESAMPOUR, Mahsa
- LLANTO, Carla

## Contents
**EDIT LATER**

**Main**
- `.ipynb` file with main code for data visualisation

**Folders & Content**

Data
- Contains all the datasets used in this project

Presentation 
- Contains the main powerpoint presentation that includes all the information from this project

Visualisation Images
- Contains all the graphs generated

Written Report
- Contains the write-up of our analysis



## Introduction
Our project aims to uncover the patterns of crime rates in Victoria by Local Government Areas (LGAs) within the last 10 years (2014-2023), and explore potential links with economic indicators like unemployment and inflation rates. We hope to gain valuable insights that can help to inform crime prevention strategies and recommendation for the public security and safety.

![Victoria and its LGAs](https://github.com/MahsaHesam/Project1-Crime-Analysis-in-Victoria/assets/70048005/607fdc7f-0cdd-485a-9586-fe137641036e)

## Research Questions
Our research questions are:
- What is the distribution of crime rate by all LGAs in Victoria?
- Which LGAs have the highest crime rates and how has it changed over the past 10 years?
- What are the major divisions of crime in Victoria and how has it changed over the past 10 Years?
- Do economic factors, such as unemployment rate and inflation rate, affect crime rates? 

## Data Collection & Cleaning

### Data Resources
To answer our research questions, we decided upon a dataset that had information on the crime rates (per 100,000 population) of all the LGAs in Victoria from 2014 to 2023. That dataset also included information categorising the different crime divisions and the number of incidents recorded. Datasets showing inflation and unemployment rates for the desired years were also chosen.

The datasets used in this projects are:
- Crime Statistics Agency
  - [Data Tables LGA Criminal Incidents Year Ending December 2023](https://www.crimestatistics.vic.gov.au/crime-statistics/latest-victorian-crime-data/download-data)
- Australian Bureau of Statistics
  - [Labour Force, Australia, February 2024](https://www.abs.gov.au/statistics/labour/employment-and-unemployment/labour-force-australia/feb-2024#data-downloads)
  - [Consumer Price Index, Australia, December Quarter 2023](https://www.abs.gov.au/statistics/economy/price-indexes-and-inflation/consumer-price-index-australia/dec-quarter-2023#data-downloads)

### Data Cleaning
Datasets were converted to CSV files and then imported to Python in Jupyter Notebook. DataFrames were used to clean up the data and remove unecessary information. Some of the data had to be re-formatted so that calculations could be made (i.e., Pandas reading a float as an string). Appropriate graphs were made to aid in answering our research questions.

## Conclusions
### What is the distribution of crime rates by all LGAs in Victoria?
- Half of the top 10 LGAs with the highest crime rates are centred around Melbourne, while the other half are scattered across Victoria
  1. Melbourne (Urban) - 15,451
  2. Latrobe (Regional) - 11,063
  3. Mildura (Rural) - 10,514
  4. Yarra (Urban) - 10,406
  5. Port Phillip (Urban) - 8,869
  6. Greater Dandenong (Urban) - 8,816
  7. Horsham (Rural) - 8,769
  8. Ararat (Regional) - 8,327
  9. Greater Shepparton (Regional) - 8,237
  10. Maribyrnong (Urban) - 8,189

### Which LGAs have the highest crime rates and how has it changed over the past 10 years?
- Melbourne remains as the top LGA in terms of crime rates over the years 2014-2023
  - Crime rates have been decreasing throughout 2014-2023
- Latrobe and Yarra remains in the top 3, with the crime rate of Mildura rising in 2023
- There was a spike in crimes rates in 2016 in all LGAs (except Horsham and Ararat)
- A majority of the LGAs (i.e., 7 out of 10 LGAs) had a drop in crime rates in 2021

### What are the major divisions of crime in Victoria and how has it changed over the past 10 Years?
- The distribution of offence divisions in order from largest to smallest:
  1. Property and deception offences - 59.62%
  2. Crimes against the person - 17.36%
  3. Justice procedures offences - 15.02%
  4. Public order and security offences - 4.26%
  5. Drug offences - 3.57%
  6. Other offences - 0.16%
- The most common types of crimes (e.g., theft, forgery, burglary, graffiti, etc.) fall under the *'property and deception offences'* umbrella
  - May be why this division encompasses a large proportion of the total incidents
  - Theft is the most frequently occurring crime
- *'Other offences'* contain offences that do not fit into the major offence divisions

### Do economic factors, such as unemployment rate and inflation rate, affect crime rates? 
- The rate of unemployment and inflation does not affect crime rates
- The regression models do not show statistical significance in predicting crime rates
- There may be other factors that are driving the crime rates

# Project 1: Victorian Crime Analysis
Crime data for each Local Government Area (LGA) was collected and analysed to uncover crime trends in Victoria. Information regarding economical factors, such as inflation and unemployment, were also collected to find there is a correlation between the mentioned financial factors and the rates of crimes.

## Research Questions
1. Which LGAs have the highest crime rates and how has it changed over the past 10 years?
2. What are the major divisions of crimes in Victoria and how has it changed over the past 10 years?
3. Do economic factors, such as unemployment rate and inflation rate, affect crime rates? 

## Analysis of Crime Data

### Which LGAs have the highest crime rates and how has it changed over the past 10 years?

**Graph 1: Crime rates by LGAs in 2023**

![Crime rates of Victoria's LGAs](./Visualisation%20Images/crime%20rate%20all%20LGAs%202023.png)

**Graph 2: Top 10 LGAs by Crime Rates 2023**

![Top 10 LGAs 2023 by crime rates](./Visualisation%20Images/top%2010%20LGA%20crime%20rate%202023.png)

By sorting the LGAs in descending order, the top LGAs by crime rates in 2023 per 100,000 population are: Melbourne with the highest crime rate of 15,451, followed by Latrobe at 11,063 and Mildura at 10,514.

The rest of the top 10 are as follows:

4. Yarra - 10,406
5. Port Phillip - 8,869
6. Greater Dandenong - 8,816
7. Horsham - 8,769
8. Ararat - 8,327
9. Greater Shepparton - 8,237
10. Maribyrnong - 8,189

Looking at the locations of the LGAs, half of the LGAs in the top 10 are closer to the Victorian capital and are considered urban (i.e., Melbourne, Yarra, Port Phillip, Greater Dandenong, Maribyrnong), while the other half are further away and are considered regional (i.e., Latrobe, Ararat, and Greater Shepparton) and rural (i.e., Mildura, and Horsham). 

Another thing to note is that, while rural Mildura is ranked third overall, it is also the biggest LGA in terms of land area (followed by East Gippsland, which is ranked 14th). It is also on the border of two other states, which may play a role in the higher crime rate as compared to other rural areas. 

**Graph 3: Top 10 LGAs (2014-2023)**

![Top 10 LGAs from 2014 to 2023](./Visualisation%20Images/top%2010%20LGA%20crime%20rate%20over%20the%20period%202014-2023.png)

Looking at Graph 3, it is visible that the overall crime rates of Melbourne decreased over the years 2014 to 2023. For Latrobe and Yarra, there was an increase in 2016, and between 2018 and 2020, before decreasing back to around the same rate as in 2014. Tracking Horsham, there was a dip in crime rates in 2019 but it has started to increase again in recent years. Otherwise, for the other LGAs, there seems to be a slight increase from 2014 to 2023. 

In 2016, an increase to crime rates was observed in all of the top 10 LGAs, except for Horsham and Ararat. More information will need to be researched to understand why there was an increase specifically in 2016.

Overall, Melbourne has been first throughout this period, followed by Latrobe and Yarra. On the other hand, the remaining LGAs swap positions, while remaining in the top 10. Furthermore, there is also a possibility that a couple of LGAs drop out of the top 10 in some years due to decrease in crime rates.

### What are the major divisions of crimes in Victoria and how has it changed over the past 10 years?

**Graph 4: Distribution of offence divisions**

![Offence Divisions Distribution](./Visualisation%20Images/major%20division%20of%20offences%20for%202023.png)

Analysing Graph 4 will find that the offence division with the highest proportion of the incidents recorded is 'property and deception offences'. This division includes offences such as:
- Burglary
- Theft (including vehicle theft)
- Forgery
- Graffiti
- Deception/false information
- Property damage (including arson)

However, a good reminder is the fact that *'property and deception offences'* is a category that consists of many common crimes, whereas divisions like *'drug offences'* and *'public order and security offences'* are more specific. For example, *'drug offences'* includes the possession, use, manufacturing, and trafficking of drugs, while *'public order and security offences'* includes offences such as possession of firearms and explosives, offences relating to riots, and offensive behaviours and conduct.

Another point of interest that is worth investigating is the fact that the offences in *'property and deception offences'* are relatively easier to get evidence for and record as opposed to crimes relating to drugs or crimes against the person, where more in-depth investigations are usually carried out.

For *'justice procedures offences'* division, the offences that it covers partially involves people who have already commited other offences, so the population of people who would be able to be charged for these offences are relatively low. Such offences includes: escape custody, offences relating to prison regulation, breaching orders and bail conditions, as well as resist or hinder officers.

Meanwhile, the *'other offences'* division only includes crimes that could not be categorised into the other divisions, making this category somewhat negligible in the analysis of what crime divisions have the highest incidents recorded.

**Graph 5: Offence divisions in LGAs in 2023**

![LGAs' split in offence divisions in 2023](./Visualisation%20Images/stacked%20bar%20Chart%20for%20top%2010%20LGAs%20by%20offence%20division%20for%202023.png)

Looking at Graph 5, it can be observed that *'property and deception offences'* takes up more than 50% of most of the LGAs' total incidents. However, there are some LGAs where the distribution of offence divisions is more equal. For example, Horsham has the least number of *'property and deception offences'*, but the higher numbers of offences in the other division (namely *'justice procedure offences'* and *'crimes against the person'*) places it at 7th, above Maribyrnong, that has more incidents recorded in the *'property and deception offences'* division. 

Furthermore, Yarra has the second most *'property and deception offences'* but only ranks 4th because of the smaller amount of crimes committed in the other divisions. This is also the same with Maribyrnong having the third highest *'property and deception offences'* but only ranking 10th overall.

**Graph 6: Incidents recorded by offence divisions over the years (2014-2023)**

![Incidents recorded by offence divisions 2014-2023](./Visualisation%20Images/crime%20incidents%20by%20Offence%20Division%20over%20the%20period%202014-2023.png)

Regarding graph 6, there appears to be to a spike of *'other offences'* in 2020. Additionally, there was also a drop in *'property and deception offences'* during that year. These sudden increase and decrease (respectively) of the two divisions may be attributed to the lockdowns that happened in Victoria during that time period as a result of COVID-19. It could explain why there was a drop in *'property and deception offences'* as most people would be inside their homes and offences against property would be reduced. However, more research will need to be conducted for these time periods to solidify the correlation between COVID-19 and the decrease of *'property and deception offences'*.

On the other hand, the other offence divisions seem to have a steady amount of incidents over the years.

**Graph 7: Top 10 offence subdivisions in 2023**

![Top 10 offence subdivsions](./Visualisation%20Images/top%2010%20Offence%20subdivisions%20by%20incidents%20recorded.png)

The offence subdivision that has the highest number of recorded incidents is theft, which is under the *'property and deception offences'* division. More research will be needed to understand why theft has the highest number of incidents recorded. However, an inference can be made that theft is a relatively easy offence to commit, as well as a relatively easy offence to catch and charge someone for. Offences that are more specific (i.e., firearms and drugs) have lower incident numbers as the categories does not cover a large variety of offences. It is also possible that those categories have low numbers because it takes a lot of time and effort to investigate those offences, especially if it involves groups of people.


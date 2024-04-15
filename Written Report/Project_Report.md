# Project 1: Victorian Crime Analysis
Crime data for each Local Government Area (LGA) was collected and analysed to uncover crime trends in Victoria. Information regarding economical factors, such as inflation and unemployment, were also collected to find there is a correlation between the mentioned financial factors and the rates of crimes.

## Research Questions
1. Find the distribution of crime rate by all Local Government Area(LGA)s in Victoria?
2. Which LGAs have the highest crime rates and how has it changed over the past 10 years?
3. What are the major divisions of crime in Victoria and how has it changed over the past 10 Years?
4. Do economic factors, such as unemployment rate and inflation rate, affect crime rates? 

## Analysis of Crime Data

### (Q1) Find the distribution of crime rate by all Local Government Area(LGA)s in Victoria?

**Chart 1: Crime rates by LGAs in 2023**

![Crime rates of Victoria's LGAs](./Visualisation%20Images/crime%20rate%20all%20LGAs%202023.png)
This analysis provides insights into the distribution of crime rates across all LGAs in Victoria. The chart shows a complete snapshot of crimes rates per 100,000 pouplations accross all 79 LGAs in Victoria. Further analysis on the LGAs are completed in the next parts.

### (Q2) Which LGAs have the highest crime rates and how has it changed over the past 10 years?

**Chart 2: Top 10 LGAs by Crime Rates 2023**

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

**Chart 3: Top 10 LGAs (2014-2023)**

![Top 10 LGAs from 2014 to 2023](./Visualisation%20Images/top%2010%20LGA%20crime%20rate%20over%20the%20period%202014-2023.png)

Looking at Graph 3, it is visible that the overall crime rates of Melbourne decreased over the years 2014 to 2023. For Latrobe and Yarra, there was an increase in 2016, and between 2018 and 2020, before decreasing back to around the same rate as in 2014. Tracking Horsham, there was a dip in crime rates in 2019 but it has started to increase again in recent years. Otherwise, for the other LGAs, there seems to be a slight increase from 2014 to 2023. 

In 2016, an increase to crime rates was observed in all of the top 10 LGAs, except for Horsham and Ararat. More information will need to be researched to understand why there was an increase specifically in 2016.

Overall, Melbourne has been leading in crime rates throughout this period, followed by Latrobe and Yarra. On the other hand, the remaining LGAs swap positions, while remaining in the top 10. Furthermore, there is also a possibility that a couple of LGAs drop out of the top 10 in some years due to decrease in crime rates.

### (Q3) What are the major divisions of crimes in Victoria and how has it changed over the past 10 years?

**Chart 4: Distribution of offence divisions**

![Offence Divisions Distribution](./Visualisation%20Images/major%20division%20of%20offences%20for%202023.png)

Analysing chart 4 will find that the offence division with the highest proportion of the incidents recorded is 'property and deception offences'. This division includes offences such as:
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

**Chart 5: Offence divisions in LGAs in 2023**

![LGAs' split in offence divisions in 2023](./Visualisation%20Images/stacked%20bar%20Chart%20for%20top%2010%20LGAs%20by%20offence%20division%20for%202023.png)

Looking at Graph 5, it can be observed that *'property and deception offences'* takes up more than 50% of most of the LGAs' total incidents. However, there are some LGAs where the distribution of offence divisions is more equal. For example, Horsham has the least number of *'property and deception offences'*, but the higher numbers of offences in the other division (namely *'justice procedure offences'* and *'crimes against the person'*) places it at 7th, above Maribyrnong, that has more incidents recorded in the *'property and deception offences'* division. 

Furthermore, Yarra has the second most *'property and deception offences'* but only ranks 4th because of the smaller amount of crimes committed in the other divisions. This is also the same with Maribyrnong having the third highest *'property and deception offences'* but only ranking 10th overall.

**Chart 6: Incidents recorded by offence divisions over the years (2014-2023)**

![Incidents recorded by offence divisions 2014-2023](./Visualisation%20Images/crime%20incidents%20by%20Offence%20Division%20over%20the%20period%202014-2023.png)

Regarding graph 6, there appears to be to a spike of *'other offences'* in 2020. Additionally, there was also a drop in *'property and deception offences'* during that year. These sudden increase and decrease (respectively) of the two divisions may be attributed to the lockdowns that happened in Victoria during that time period as a result of COVID-19. It could explain why there was a drop in *'property and deception offences'* as most people would be inside their homes and offences against property would be reduced. However, more research will need to be conducted for these time periods to solidify the correlation between COVID-19 and the decrease of *'property and deception offences'*.

On the other hand, the other offence divisions seem to have a steady amount of incidents over the years.

**Chart 7: Top 10 offence subdivisions in 2023**

![Top 10 offence subdivsions](./Visualisation%20Images/top%2010%20Offence%20subdivisions%20by%20incidents%20recorded.png)

The offence subdivision that has the highest number of recorded incidents is theft, which is under the *'property and deception offences'* division. More research will be needed to understand why theft has the highest number of incidents recorded. However, an inference can be made that theft is a relatively easy offence to commit, as well as a relatively easy offence to catch and charge someone for. Offences that are more specific (i.e., firearms and drugs) have lower incident numbers as the categories does not cover a large variety of offences. It is also possible that those categories have low numbers because it takes a lot of time and effort to investigate those offences, especially if it involves groups of people.

### (Q4) Do economic factors, such as unemployment rate and inflation rate, affect crime rates? 

A multiple regression anaylysis was done for three different dependent variables with three diffrent regression outputs generated. The dependent variables include'Total crime rate', 'Property and deception offences rate', and 'Crime against the person rate'. The independent variables remained fixed in all three different analysis and they include 'average unemployment rate' and 'average inflation rate'. The following multiple regression was defined for the purpose of the analysis: 

Multiple regression equation:
Y= Eo + E1Xu + E2Xi + ε 

Y= Crime rate (dependent variable)
Eo= Intercept of the regression
E1, E2 = calculated coefficients from the regression
Xu = average unemployment rate (independent variable)
Xi = average inflation rate (independent variable)
ε = error term of the regression

Three different equations for the multiple regression analysis:
Y (Total crime rate) = E1Xu + E2Xi + ε
Y (Property and deception offences rate) = E1Xu + E2Xi + ε
Y (Crime against the person rate) = E1Xu + E2Xi + ε



# Crime Rate per 100,000 population as the dependent variable #
![Regression output for total crime rate](./Visualisation%20Images/Regression%20output%20for%20total%20crime%20rate.png)
![Regression chart for total crime rate](./Visualisation%20Images/Avg%20Unemployment%20and%20Inflation%20rate%20vs%20Total%20Crime%20Rate.png)

The following are core insights based on the results:

1. **Model Fit:**
   - R-squared (R²): 0.295 indicates that approximately 29.5% of the variance in the dependent variable is explained by the independent variables. This suggests a moderate level of explanatory power.
   - Adjusted R-squared (Adj. R²): 0.094, which is notably lower than R-squared. This indicates that after adjusting for the number of predictors in the model, the explanatory power decreases substantially.

2. **Coefficient Interpretation:**
   - The intercept (const) is 4872.7626, which represents the estimated Total Crime Rate per 100,000 population when both independent variables are zero.
   - The coefficient for 'Average unemployment rate (Annual %)' is -6.3830, but with a high p-value of 0.978. This suggests that the average unemployment rate is not statistically significant in predicting the Total Crime Rate.
   - The coefficient for 'Average inflation rate (Annual %)' is -136.2417, also with a high p-value of 0.320. This indicates that the average inflation rate is also not statistically significant in predicting the Total Crime Rate.

3. **Other Statistics:**
   - The F-statistic tests the overall significance of the model. With a p-value of 0.294, the model as a whole is not statistically significant at the conventional significance level of 0.05. This suggests that the independent variables, as a group, do not reliably predict the dependent variable.

4. **Conclusion:**
   Based on these results, it seems that the model with the current independent variables does not effectively explain the variation in the Total Crime Rate per 100,000 population. 

# Property and deception offences Rate per 100,000 population #
![Regression output for Property and deception offences rate](./Visualisation%20Images/Regression%20output%20for%20property%20and%20deception%20rate-1.png)
![Regression chart for Property and deception offences rate](./Visualisation%20Images/Avg%20Unemployment%20and%20Inflation%20rate%20vs%20Property%20and%20Deception%20offences%20Rate.png)

1. **Model Fit:**
   - R-squared (R²): 0.309 indicates that approximately 30.9% of the variance in the dependent variable is explained by the independent variables. This suggests a moderate level of explanatory power.
   - Adjusted R-squared (Adj. R²): 0.112, which is notably lower than R-squared. This indicates that after adjusting for the number of predictors in the model, the explanatory power decreases substantially.

2. **Coefficient Interpretation:**
   - The intercept (const) is 3604.9535, which represents the estimated Property and deception offences Rate per 100,000 population when both independent variables are zero.
   - The coefficient for 'Average unemployment rate (Annual %)' is 47.3109, but with a high p-value of 0.843. This suggests that the average unemployment rate is not statistically significant in predicting the Property and deception offences Rate.
   - The coefficient for 'Average inflation rate (Annual %)' is -121.5810, also with a high p-value of 0.391. This indicates that the average inflation rate is also not statistically significant in predicting the Property and deception offences Rate.

3. **Other Statistics:**
   - The F-statistic tests the overall significance of the model. With a p-value of 0.274, the model as a whole is not statistically significant at the conventional significance level of 0.05. This suggests that the independent variables, as a group, do not reliably predict the dependent variable.

4. **Conclusion:**
   Similar to the previous analysis, these results indicate that the model with the current independent variables does not effectively explain the variation in the Property and deception offences Rate per 100,000 population.


# Crimes against the person Rate per 100,000 population' dependent variable #
![Regression output for Crimes against the person rate](./Visualisation%20Images/Regression%20output%20for%20crime%20against%20the%20person%20rate.png)
![Regression chart for Crimes against the person rate](./Visualisation%20Images/Avg%20Unemployment%20and%20Inflation%20rate%20vs%20Crimes%20against%20the%20person%20rate.png)

1. **Model Fit:**
   - R-squared (R²): 0.457 indicates that approximately 45.7% of the variance in the dependent variable is explained by the independent variables. This suggests a moderate level of explanatory power.
   - Adjusted R-squared (Adj. R²): 0.302, which is lower than R-squared. After adjusting for the number of predictors in the model, the explanatory power decreases, but it's still moderate.

2. **Coefficient Interpretation:**
   - The intercept (const) is 1267.8172, which represents the estimated Crimes against the person Rate per 100,000 population when both independent variables are zero.
   - The coefficient for 'Average unemployment rate (Annual %)' is -53.6946 with a p-value of 0.068, which is slightly above the conventional significance level of 
   0.05. This suggests that the average unemployment rate may have some impact on predicting the Crimes against the person Rate, but it's not statistically significant at the usual threshold.
   - The coefficient for 'Average inflation rate (Annual %)' is -14.6625 with a p-value of 0.342, indicating that the average inflation rate is not statistically significant in predicting the Crimes against the person Rate.

3. **Other Statistics:**
   - The F-statistic tests the overall significance of the model. With a p-value of 0.118, the model as a whole is not statistically significant at the conventional significance level of 0.05. This suggests that the independent variables, as a group, may not reliably predict the dependent variable.

4. **Conclusion:**
   The model's R-squared indicates a moderate level of explanatory power, but the p-values for the individual coefficients and the F-statistic for the overall model suggest that the model may not be statistically significant in predicting Crimes against the person Rate per 100,000 population. 


## Summary/Conclusions

**Crime Rates by LGA**

•	Melbourne has the highest overall crime rate, followed by Latrobe and Mildura.
•	Half of the top 10 LGAs with the highest crime rates are urban, while the other half are regional or rural.

**Crime Divisions in Victoria**

•	Property and deception offences make up the highest proportion of crimes.
•	The distribution of offences varies across LGAs.
•	Theft is the most common sub category of offence.

**Crime rates over Time**

•  Melbourne's crime rate has decreased over the past 10 years and has had a stable trend from 2022 onwards , while other LGAs have seen an increasing trend from 2022  onwards. 
•  After a sharp increase in crimes rates in all LGAs in 2016, there was a decresing trend in crime from that year onwards.
•	There was a decrease in property and deception offences in 2020, which might be linked to COVID-19 lockdowns.
•  There has been an increasing trend in crime rates from 2022 onwards.

**Crime and Economic factors**

• All 3 regression models did not show statistical significance in predicting crime rates in Victoria.
• We do not reject the null hypothesis that the rate of unemployment and inflation does not influence crime rates in Victoria.
• Other factors (such as psychological, social, political, and self interest) may be what’s driving crime in Victoria than economic factors. 

## Recomendations ##

1. Focus on High-Crime LGAs:The analysis identified Melbourne, Latrobe, Mildura, Yarra, Port Phillip, Greater Dandenong, Horsham, Ararat, Greater Shepparton, and Maribyrnong as the LGAs with the highest crime rates. These areas should be a priority for resource allocation and crime prevention efforts. Also, implementing targeted strategies based on the specific crime types prevalent in each LGA. Property crime is dominant across most LGAs, but some have a higher proportion of crimes against the person or justice procedure offences. Also, better police resources should be deployed to LGAs that are experincing an increasing trend in crime rates.
2. Addressing Potential Socioeconomic Factors: While the initial analysis suggests a weak relationship between unemployment and inflation rates with overall crime rates, a more in-depth investigation might be necessary. Explore alternative socio-economic factors that might influence crime rates in different LGAs. Consider factors like income inequality, poverty rates, and social welfare programs.
3. Community Engagement and Crime Prevention: Collaborate with communities in high-crime LGAs to develop targeted crime prevention initiatives. This can include neighbourhood watch programs, public awareness campaigns, and improved lighting in high-risk areas.
4. Invest in Data-Driven Policing: Utilise the crime data to identify hotspots and patterns of criminal activity. Allocate police resources strategically to areas with the highest likelihood of crime occurrence.
5. Focus on Rehabilitation and Reintegration: Invest in programs that address the root causes of crime, such as social issues, mental health, and substance abuse. This can help reduce recidivism and create safer communities
6. Exploring additional economic variables such as change in RBA interest rate and real GDP over the years to study if there is any change in results.
7. Gaining access to a larger historic dataset for a more robust analysis on regressional analysis. 

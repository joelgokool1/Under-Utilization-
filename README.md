Introduction
New York City Transit (NYCT) is a public authority and one of seven agencies within the Metropolitan Transportation Authority (MTA) that operate public transportation in New York City (NYC). NYCT employs approximately 47,000 employees in various occupational groups.  Under Title VII of the Civil Rights Act of 1964, the Equal Employment Opportunity Commission requires public/private employers to report the composition of its workforce by sex and race/ethnic categories (eeoc.gov). According to the Equal Employment Opportunity Commission (EEOC) website, “Title VII of the Civil Rights Act as amended by the Equal Employment Opportunity Act of 1972 prohibits employment discrimination based on race, color, religion, sex and national origin.” In an effort to comply with EEOC guidelines, private and public employers are required to analyze internal and external workforce data to ensure that protected class employees are represented in their workforce.  (Note that: for the purposes of this analysis,  protected class employees are considered Females and Minorities (i.e., Black, Hispanic, Asian, Other Pacific Islander and Hawaiian Native)).  This utilization analysis compares the availability of females and minorities for each EEO- 4 Job Category (defined below) within the five boroughs of New York City (NYC) to New York City Transit’s (NYCT) current workforce representation of females and minorities to determine whether underutilization exists. Underutilization exist if the current workforce has fewer females or minorities than would be reasonably expected by their availability in the relevant job market (NYC). When a Job Category is deemed to be underutilized, appropriate remedies should be identified to increase the number of females and/or minorities workers. 
The Office of Federal Contract Compliance Programs (OFCCP) currently recognizes four tests to determine whether underutilization exists:  the any difference rule, the “one-person rule”, the “two standard deviation rule”, and the “80% rule”. This analyis will utilize the two standard deviation rukl to determine underutilization. 
Under the two standard-deviation rule, underutilization is inferred if the difference in a particular job group between the percentage of the protected class within NYCT and the percentage of similarly qualified workers in the NYC labor market is greater than two standard errors (standard deviations) of the difference’s estimate.

The Dataset

The datasets used in this analysis are the EEO Tabulation 2006-2010 data provided by the United States Census Bureau and the New York City Transit (NYCT) workforce information extracted from the PeopleSoft 9.2 database.  The EEO Tabulation 2006-2010 data is derived from American Community Survey (ACS) data, which consists of estimates on the population of New York City (NYC) by Standard Occupation Classification (SOC) cross-classified by race and sex.  The NYCT data consists of information on all employees working at NYCT by Sex, Ethnicity, EEO-4 Job Category and Occupational group. The EEO-4 job category column in the NYCT data set represents one or more positions having similar requirements, content, wage rates and opportunities for advancement.  

Census Dataset

The EEO Tabulation data can be found in the American Fact Finder page at: http://factfinder.census.gov/faces/nav/jsf/pages/searchresults.xhtml. To obtain the relevant labor market statistics for NYC, first select the EEO Occupation Codes option (at the bottom of the page) and then select the SOC codes applicable to NYCT. Next, click on the “Geographies” option, select the geographic type “County - 050”, select the state NYS, choose the five counties of NYC (i.e., Kings, Queens, New York, Richmond, and Bronx).  On the search result page, select the dataset named “EEO 2r. Detailed Census Occupation by Sex, and Race/Ethnicity for Residence Geography, Total Population”.  The subsequent generated table includes the number of eligible individuals in the relevant labor market by SOC. Finally, download the dataset to a CSV file. 
The Census data is bifurcated into Sex and Race groupings to highlight minority and female workforce estimates in the Utilization Report. The percentage of workers in each EE0-4 Job category for NYCT and NYC was calculated by Race and Sex. Underutilization for Race was determined by comparing the difference between the percentage of the protected class employees in a particular job group within NYCT from the percentage of similarly qualified workers in the NYC labor market is greater than two standard errors (standard deviations) of the difference’s estimate (two standard-deviation rule). 
Data wrangling 

A file with all NYCT Occupational Classification Code with the corresponding EE0-4 Description was joined to the EEO Census data by OCC code to include EE0-4 Description to the EEO Census data. EEO-4 Description was not originally included in the Census data and needs to be added to form a relationship to the NYCT dataset. Similarly, to EEO-4 description OCC is used to classify workers into occupational categories for the purpose of collecting and reporting data. The Race and Sex fields were different between the Census data and NYCT and were made consistent to calculate underutilization. 

Officials/Administrators Census Workforce 

The available workforce for Officials/Administrators is not only the geographic location of NYC but instead a combination of NYCT data and Census data.  The EEO-4 job group Officials/Administrators used by NYCT consists of various NYCT Occupational groups.  The total NYCT employees in the EEO-4 job category Officials/Administrators are 7,802. The number of "Operating Supervisors" that are in the EEO-4 Job Group Officials/Administrators is 5,219.  As such, 67% of the Officials/Administrators population is Operating Supervisors. 
The available workforce for Operating Supervisors (sub-group of the Officials/Administrators population) is not the geographic location of New York City but instead the NYCT occupational group called “Hourly Occupational”.  Hourly employees take a competitive exam to promote to an Operating Supervisor position. Further, the number of NYCT employees in the occupational group – Hourly Occupational is 38,346.  A weighted average of the two groups 67% of the Hourly Occupational group and 33% of the New York City workforce (Census data) was used in this analysis to  determine the total available workforce for the EEO-4 Job Group Officials/Administrators.  

Analysis for Two Standard Deviation Analysis 

Under the two standard deviation rule, underutilization may be inferred if the difference between the percentage of the protected class employees in a particular job group within NYCT and the percentage of similarly qualified workers in the NYC labor market is greater than two standard errors (standard deviations) of the difference’s estimate. The estimate of the standard error assumes what is called the Null Hypothesis: that New York City Transit is hiring on a random basis from an available qualified population, each person having an equal chance of being selected. Based on the null hypothesis, for a specific race, sex, or ethnic group within a given occupation, the proportion of workers at NYCT (p) is equal to the proportion of workers (Pm) in the NYC for that occupation, and that any deviation between p and Pm may be attributed solely to chance. The null hypothesis formula as follows:
                                                                              H0: p = pm
                                                          where:
                                                                                H0 = the null hypothesis
                                                                                p = NYCT workers
                                                                                Pm=  workers in NYC
                                                                                
Based on this assumption, for a specific race and sex in a given EEO-4 job group, the proportion of NYCT workers (p) will differ from the proportion of workers (Pm) in the NYC labor market by more than two standard errors less than 5% of the time. In other words, you can be greater than 95% confident that such a difference is not due to chance and reject the Null Hypothesis that hiring is on a random basis from the available pool.  When evaluating underutilization, the data for “p” and “Pm” is analyzed to determine whether to reject the null hypothesis. The null hypothesis may be rejected to the extent that “p” may differ from “Pm”.  The inferential statistical procedure used to test the hypothesis is probability, which is the likelihood that the observed samples are statistically significant or they are due to chance. The standard error used when analyzing the differences between “p” and “Pm” depends on the number of workers employed at NYCT in a given EEO-4 job group and the uncertainty of the Census data (relevant labor market availability). The Census data contains a certain amount of sampling variance as it is an estimate based on samples from the population.  
The formula for standard error is: 

                                    √((((p*(1-p))/n) + ((Pm * (1-Pm)/Nm))) )

Spm = Square root (((p*(1-p))/n) + ((Pm * (1-Pm)/Nm))) 
Where Spm = standard error of the difference between p and Pm 
n = total number of NYC workers in a given EEO Job group 
Nm = total number of qualified workers in the relevant labor market
 p = proportion of workers in a given EEO job group in NYCT 
Pm = proportion of workers in the group in the relevant labor market.  

In statistics, the z-score is used to represent the number of standard deviations an observation is from the mean.  The statistical significance is attained when the inferred p-value (probability of the observed data) is less than the significance level of 5%. The formula for the z score is: 
                                      (p-Pm)/Spm
The .05 level of significance (5%) used for this analysis corresponds to a z-score whose absolute value is greater than 1.96. The z-score calculation is compared to the critical value (1.96) to determine if the null hypothesis will be rejected. For example, the percentage of NYCT’s “Other” Office/Clerical workers is 2% of the 4,366 Office/Clerical workers and the Census data (relevant labor market) consist of 12% of the 638,921 Office/Clerical workers. When calculating the standard error and converting it to a z score the significant difference between the percentages of Hispanic Office/Clerical workers in NYCT and NYC can be determined. 

                                    Spm = √(((.02*(1-.02))/4,366) + ((.12*(1-.12)/638,921)))   

                                     Spm = .0022
                                          Calculating z:
                                          z=((X-μ))/σ
                                          
                                         Or
                                         
                                      (p-Pm)/Spm
                                      z = (.02-.12)/(.0022)= -46.28


                                    .05 (|z|>=2 -- two standard deviations from the mean)
                                     z = -46.28                                
NYCT would reject the null hypothesis that p=pm as the computed z score (-46.28) is less than -1.96 and conclude that the percentage of Hispanic Office/Clerical workers at NYCT differ from the expected value in NYC.  Therefore, an inference of underutilization (“Yes”) can be made for Hispanic Office/Clerical workers at NYCT since the difference between p and Pm cannot be attributed solely to chance.

Conclusion 

Chart Analysis of Two Standard Deviation Rule with Confidence Intervals 

The charts above illustrate the various EEO job groups cross classified by race and gender. The red and blue plots below represent the percentage of NYCT employees in a particular job group and race/gender relative to the relevant workforce (NYC). Moreover, reflects underrepresentation for the given EEO job groups by race and sex. The vertical black line on each graph represents a difference of 0% between the NYCT workforce and the available. Only the differences between the NYCT and available workforce were plotted relative to this line.  The calculation for the line is the NYCT EEO job group and race/gender data less the available NYC workforce, which represents the underrepresentation threshold. The horizontal bar for sex and race illustrates the confidence interval. For example, the percentage difference of Female Protective Services employed by NYCT from the proportion of the group in the available workforce of NYC. However, the available workforce estimate remains within the 95% confidence interval, so we cannot state with 95% confidence that underrepresentation exist. When it cannot be seen, the interval is smaller than the data point shape. 

Underutilization exists for the following EEO-4 Job Groups: Officials/Clerical Officials/Administrators, Paraprofessional, Professionals, Protective Service, Service Maintenance, Skilled Craft, and echnician. The charts above provides details on which Gender and Race are underrepresented for a given Job group.

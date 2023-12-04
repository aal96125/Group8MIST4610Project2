# Group 8 MIST 4610 Project 2

# Team Name: 
29704 Group 8

# Team Members: 
1. Clara Wilt [@clarawilt](https://github.com/clarawilt)
2. Jaelin Cummings [@jcummings1](https://github.com/jcummings1)
3. Colby Fielding [@cpf40265](https://github.com/cpf40265)
4. Backam Nguyen [@bn51725](https://github.com/bn51725)
5. Aiman Lalani [@aal96125](https://github.com/aal96125)

# Dataset Description 
The dataset obtained from data.gov comprises a substantial amount of data related to tobacco use, specifically targeting middle and high school students in America. It includes 31 distinct columns and encompasses a total of 10,601 rows, indicating a comprehensive collection of data points. Each column represents a different aspect or characteristic relevant to the study of tobacco use among this demographic. Here's a detailed description of the dataset:
1. Year: The year when the data was collected or pertains to.
2. LocationAbbr: Abbreviation of the location (likely states or territories) where the data was collected.
3. LocationDesc: Full description of the location, providing more detail than the abbreviation.
4. TopicType: The general category or type of topic the data pertains to, which in this case is likely related to tobacco use.
5. TopicDesc: Detailed description of the topic, offering specifics on what aspect of tobacco use or cessation is being addressed.
6. MeasureDesc: Description of the measurement taken or the data point collected, such as the rate of tobacco use, the frequency of use, etc.
7. DataSource: The source from which the data was obtained, which could include surveys, studies, or other data collection methods.
8. Response: Likely refers to the response obtained in a survey or study, possibly relating to attitudes or behaviors concerning tobacco use.
9. Data_Value_Unit: The unit of measurement used for the data values, such as percentages, numbers, etc.
10. Data_Value_Type: The type or nature of the data value, such as an average, median, total, etc.
11. Data_Value: The actual data or numerical value recorded.
12. Data_Value_Footnote_Symbol: Symbols used in footnotes that explain or provide additional context to the data values.
13. Data_Value_Footnote: The footnotes themselves that accompany data values for further explanation or clarification.
14. Data_Value_Std_Err: Standard error of the data value, indicating the precision of the measurement.
15. Low_Confidence_Limit & High_Confidence_Limit: These columns provide the lower and upper bounds of the confidence interval for the data value, reflecting the reliability of the estimates.
16. Sample_Size: The size of the sample from which the data was drawn, which impacts the generalizability of the findings.
17. Gender: The gender of the respondents or subjects in the study.
18. Race: The race of the respondents, important for understanding demographic variations in tobacco use.
19. Age: Age of the respondents, crucial since the dataset focuses on middle and high school students.
20. Education: Educational background or level of the respondents, if applicable.
21. GeoLocation: Geographical coordinates or location details where the data was collected.
22. TopicTypeId, TopicId, MeasureId: These likely refer to specific identifiers for categorizing and referencing topics and measurements within the dataset.
23. StratificationID1, StratificationID2, StratificationID3, StratificationID4: These columns probably relate to specific ways the data is stratified or broken down, such as by age group, gender, race, etc.
24. SubMeasureID: Identifier for sub-measurements or specific aspects within a broader measurement.
25. DisplayOrder: The order in which the data is arranged or should be displayed for analysis or reporting.


# Questions
1. How many middle schoolers from 1999-2017 in each state claim to use smokeless tobacco products?
   
   Monitoring usage over an extended period (1999-2017) allows for the analysis of trends and the effectiveness of past public health     interventions. It also provides a valuable dataset for academic and medical research into the effects of early tobacco use.

2. Does gender play a role in using vs quitting tobacco use in youth across America?
   
   Gender-specific patterns in tobacco use and cessation can have significant implications for public health. If one gender is more       susceptible to starting or less likely to quit tobacco, targeted interventions can be developed to address these disparities.          Understanding these patterns helps in designing gender-sensitive prevention and cessation programs, which are more effective in        reducing tobacco use among young people.

# Manipulations Applied to the Data
We added an extra column called ‘Count’ which converted the data value percentage into a numerical count based on sample size. We removed ‘TopicType’, ‘DataSource’, ‘Data_Value_Unit’, ‘Data_Value_Type’, ‘Data_Value_Footnote_Symbol’, ‘Data_Value_Footnote’,  ‘Data_Value_Std_Err’, ‘Low_Confidence_Limit’, ‘High_Confidence_Limit’, ‘Race’, ‘Age’, ‘TopicTypeId, and  ‘StratificationID2’. We removed ‘Data_Value_Footnote_Symbol’ ‘Data_Value_Footnote’, and ‘Data_Value_Unit’ because the data was not compatible with Tableau and we removed all other columns because they were not relevant to our analysis. 

# Analysis and Results 
Our first visual shows the number of middle schoolers by state who use smokeless tobacco products. Based on the survey, Florida was the state with the highest count of 30,280 middle schoolers. This shows that any prevention measures or programs in place across Florida school systems are ineffective and a lack of regulations. 

Our second visual compares tobacco use vs cessation by gender from 1999-2017. Tobacco use and cessation rate are both declining in this time period, following peaks in 2002. females are quitting at a higher rate than males. On the other hand, males are using tobacco more than females. The price of cigarettes increased approximately by 88% in 1997-2002. However the spending on tobacco industry marketing doubled which reduced the impact of public health campaigns. 


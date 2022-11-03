# GA_Project_1
 General Assembly Project 1
### Brief Background
The SAT is a standardized tests that many colleges and universities in the United States require for their admissions process. This score is used along with other materials such as grade point average (GPA) and essay responses to determine whether or not a potential student will be accepted to the university.
 intended to measure literacy, numeracy and writing skills that are needed for academic success in college. Similarly to data, they argued that the SAT is a predictive analysis of students success in college. Some states in the US also have a mandatory requirement for high school students to take the SAT. https://mindfish.com/blog/which-states-require-the-sat/. As of fall 2022, majority of univerisities no longer require SAT https://www.compassprep.com/college-profiles/

### Problem statement
In 2018, top ivy universities such as Havard dropped the SAT requirement for university application, how did it affect the total SAT scores and participation rates?

### Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|str|SAT|The states in the US corresponding to the scores| 
|participation_19|float|SAT|Percentage of students participating in SAT per state in 2019| 
|participation_18|float|SAT|Percentage of students participating in SAT per state in 2018| 
|participation_17|float|SAT|Percentage of students participating in SAT per state in 2017| 
|total_19|int|SAT|Average sum of EBR and Math in 2019(Min: 400 Max: 1600)| 
|total_18|int|SAT|Average sum of EBR and Math in 2018(Min: 400 Max: 1600)| 
|total_17|int|SAT|Average sum of EBR and Math in 2017(Min: 400 Max: 1600)| 

### Summary
From 2017 to 2019, there was a decrease in the means of the total scores. (2017 : 1126 , 2018 : 1120 , 2019 : 1113 ) From 2017 to 2019, there was an increase in means of the participation rates. (2017 : 0.398 , 2018 : 0.457 , 2019 : 0.491). This supports the problem statement that there was some influence on the total scores and participation rates.

North Dakota has the lowest participation rates in both 2018 and 2019 of SAT scores. In 2017, the states with the lowest participation are Iowa, MIssissippi and North Dakota. In 2019, Rhode Island, Illinosis, Michigan, Colorado and Connecticut had the highest participation rates. In 2018, Colorado, Connecticut, Delaware, Idaho and Michigan had the highest participation rates. In 2017, Connecticut, Delaware, District of Columbia and Michigan had the highest participation rates.

### Conclusion and Recommendations
There was a dropped in the average total score of SAT scores when top ivy univerisities dropped their SAT requirements however there was an increase in means of the participation rates.
From 2017 to 2019, there was a decrease in the means of the total scores. (2017 : *1126* , 2018 : *1120* , 2019 : *1113* )
From 2017 to 2019, there was an increase in means of the participation rates. (2017 : *0.398* , 2018 : *0.457* , 2019 : *0.491*)
At least 5 top Ivy Universities such as Harvard dropped the SAT requirements which might have influenced the total scores, however there is also an increased in particpation.
A possible reason for an increase in SAT participation rates could be the accessbility of fee waivers. As the SAT costs 60USD, some students are not able to afford it. However, the fee waival has changed over the years, allowing more students to take the SAT. https://satsuite.collegeboard.org/media/pdf/sat-fee-waiver-student-brochure.pdf
Another possible reason is that some states might instate mandatory SAT.
It is recommended to conduct further data analysis into other external factors that might affect the SAT total scores such as the pandemic that occured in the later part of 2019, any possible changes to the learning structure and changes in the political background.
As of 2022, majority of universities have dropped the SAT requirement and more notable changes to the total scores and participation rate might be observed to further investigate the influence of universities admissions on total SAT scores.
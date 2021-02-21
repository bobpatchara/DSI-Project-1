# DSI-Project-1

 - [Problem Statement](#Problem-Statement)
 - [Project Objectives](#Executive-Summary)
 - [Data Dictionary](#Data-Dictionary)
 - [Data Analysis](#Data Analysis)
 - [Conclusions & Recommendations](#Conclusions-&-Recommendations)

## Problem Statement
I am working as a data analyst at Niche company which is a market leader in connecting colleges and schools with students and families and helps million of students and families find and enroll in the right school for them. My project is "to help Niche company gaining more brand awareness by collaborating a new project “University Scholarship” with Global Standardized Test Organization like SAT or ACT, to provide an examination fee and give a free education consulting to scholarship students"

## Project objectives:
- To analyze the SAT and ACT Tests taken in 2017, 2018 and 2019
- To analyze the trend of aggregated scores and participation rates for each state in United States.
- To provide recommendations to Data Analytic of Niche team and marketing team whether or not to choose collaborating with SAT or ACT to help them improve participation rates for future tests and also increase both brand awarenesses  

## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|Final_sat_act_2017_to_2019|Names of all US states and the District of Columbia|
|**sat_participation_17**|*float*|Final_sat_act_2017_to_2019|The percentage of 2017 graduating seniors who took the SAT|
|**sat_reading_and_writing_17**|*int*|Final_sat_act_2017_to_2019|The mean score of the Evidence-Based Reading and Writing (ERW) category of the SAT in 2017 (score range: 200-800)|
|**sat_math_17**|*int*|Final_sat_act_2017_to_2019|The mean score of the Math category of the SAT in 2017 (score range: 200-800)|
|**sat_total_17**|*int*|Final_sat_act_2017_to_2019|The sum of the mean scores of ERW and Math in the SAT in 2017 (score range: 400-1600)|
|**sat_participation_18**|*float*|Final_sat_act_2017_to_2019|The percentage of 2018 graduating seniors who took the SAT|
|**sat_reading_and_writing_18**|*int*|Final_sat_act_2017_to_2019|The mean score of the Evidence-Based Reading and Writing (ERW) category of the SAT in 2018 (score range: 200-800)|
|**sat_math_18**|*int*|Final_sat_act_2017_to_2019|The mean score of the Math category of the SAT in 2018 (score range: 200-800)|
|**sat_total_18**|*int*|Final_sat_act_2017_to_2019|The sum of the mean scores of ERW and Math in the SAT in 2018 (score range: 400-1600)|
|**sat_participation_19**|*float*|Final_sat_act_2017_to_2019|The percentage of 2019 graduating seniors who took the SAT|
|**sat_reading_and_writing_19**|*int*|Final_sat_act_2017_to_2019|The mean score of the Evidence-Based Reading and Writing (ERW) category of the SAT in 2019 (score range: 200-800)|
|**sat_math_19**|*int*|Final_sat_act_2017_to_2019|The mean score of the Math category of the SAT in 2019 (score range: 200-800)|
|**sat_total_19**|*int*|Final_sat_act_2017_to_2019|The sum of the mean scores of ERW and Math in the SAT in 2019 (score range: 400-1600)|
|**act_participation_17**|*float*|Final_sat_act_2017_to_2019|The percentage of 2017 graduating seniors who took the ACT (0.9810 means 98.1%)|
|**act_english_17**|*float*|Final_sat_act_2017_to_2019|The mean score of the Reading category of the ACT in 2017 (score range: 1-36)|
|**act_math_17**|*float*|Final_sat_act_2017_to_2019|The mean score of the Math category of the ACT in 2017 (score range: 1-36)|
|**act_reading_17**|*float*|Final_sat_act_2017_to_2019|The mean score of the Reading category of the ACT in 2017 (score range: 1-36)|
|**act_science_17**|*float*|Final_sat_act_2017_to_2019|The mean score of the Science category of the ACT in 2017 (score range: 1-36)|
|**act_composite_17**|*float*|Final_sat_act_2017_to_2019|The mean score of the categories English, Math, Reading, and Science on the ACT in 2017 (score range: 1-36)|
|**act_participation_18**|*float*|Final_sat_act_2017_to_2019|The percentage of 2018 graduating seniors who took the ACT (0.9810 means 98.1%)|
|**act_english_18**|*float*|Final_sat_act_2017_to_2019|The mean score of the Reading category of the ACT in 2018 (score range: 1-36)|
|**act_math_18**|*float*|Final_sat_act_2017_to_2019|The mean score of the Math category of the ACT in 2018 (score range: 1-36)|
|**act_reading_18**|*float*|Final_sat_act_2017_to_2019|The mean score of the Reading category of the ACT in 2018 (score range: 1-36)|
|**act_science_18**|*float*|Final_sat_act_2017_to_2019|The mean score of the Science category of the ACT in 2018 (score range: 1-36)|
|**act_composite_18**|*float*|Final_sat_act_2017_to_2019|The mean score of the categories English, Math, Reading, and Science on the ACT in 2018 (score range: 1-36)|
|**act_participation_19**|*float*|Final_sat_act_2017_to_2019|The percentage of 2019 graduating seniors who took the ACT (0.9810 means 98.1%)|
|**act_english_19**|*float*|Final_sat_act_2017_to_2019|The mean score of the Reading category of the ACT in 2019 (score range: 1-36)|
|**act_math_19**|*float*|Final_sat_act_2017_to_2019|The mean score of the Math category of the ACT in 2019 (score range: 1-36)|
|**act_reading_19**|*float*|Final_sat_act_2017_to_2019|The mean score of the Reading category of the ACT in 2019 (score range: 1-36)|
|**act_science_19**|*float*|Final_sat_act_2017_to_2019|The mean score of the Science category of the ACT in 2019 (score range: 1-36)|
|**act_composite_19**|*float*|Final_sat_act_2017_to_2019|The mean score of the categories English, Math, Reading, and Science on the ACT in 2019 (score rane: 1-36)|


## Data Analysis
- SAT has a large group of very low-end participation rates (<10%), and a cluster of states with participation in the 50–75% range, and then a group of states with 100% participation. The ACT, by contrast, has almost no states with lower than 10% participation, has a cluster of states in the 15–35% range, only a small number of states in the mid to high range, and then a large group of states with at or near 100% participation. In this way the three distributions almost mirror each other.
- Mean scores on a given test are highly negatively correlated with participation rate on that test (-0.8). 
Lower participation typically means higher mean scores, and vice versa, due to higher achieving students on average taking the test.
- If a state performs well on the SAT because they have low participation or simply because they are higher achieving, it’s likely they perform well on all sections. 
This holds across years too, as most states have similar profiles in 2019 as they did in 2018 and 2017. “Participation rates for the same test across years are highly correlated.”
- Mean scores on sections of the SAT are moderately negatively correlated with mean scores on ACT, and vice versa.
- Participation rate on a given test is moderately positively correlated with scores on the opposite test (0.6).
This is simply due to higher participation on SAT > lower participation on ACT > higher ACT scores. So, positive correlation between SAT participation and ACT scores.

## Conclusions & Recommendations 
SAT has a large group of very low-end participation rates (<10%), and a cluster of states with participation in the 50–75% range, and then a group of states with 100% participation. The ACT, by contrast, has almost no states with lower than 10% participation, has a cluster of states in the 15–35% range, only a small number of states in the mid to high range, and then a large group of states with at or near 100% participation. In this way the three distributions almost mirror each other.

We need to collaborate with “College Board/ SAT” which has a very strong presence internationally because of these reasons;
- Upward trends of SAT Participation rate year-on-year (2017 - 2019 : 3.5% per year)
- SAT has a large group of very low-end participation rates (<10%)
- ACT Participation slightly drops year-to-year (2017 - 2019 : -3.5% per year)
and so College Board can use this as a strength and dominate more over ACT.Thus, Niche Marketing team and College Board should promote campaign of ‘University Scholarship Project’ at top 5 lowest participation states, including: North Dakota, Mississippi, Lowa, Wyoming, and South Dakota. 








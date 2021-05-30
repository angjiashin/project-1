# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

## Problem Statement

Since the new format of the SAT exam was introduced in 2016, SAT exam participation rate have fluctuated in 2017 and 2018. Some states have decided to introduced statewide participation of ACT exam while there are other states that do not participate in the SAT exams.To further promote the new SAT exam to states in the US, I seek to find out some of the factors that are influencing SAT participation rates statewide and suggest ways to improve SAT participation rates for a state of interest.

## Executive Summary


### Contents:
- [2017 Data Import & Cleaning](#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Data Visualization](#Visualize-the-data)
- [Descriptive and Inferential Statistics](#Descriptive-and-Inferential-Statistics)
- [Outside Research](#Outside-Research)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)



## Data dictionary


|Feature|Type|Dataset|Description|
|---|---|---|---|
|**State**|*string*|sat_2017, sat_2018, act_2017, act_2018|The name of the state in the United States.| 
|**s17_part**|*float*|sat_2017|The participation rate of each state in SAT 2017 exam (units calculated in percentage)| 
|**s17_ebrw**|*float*|sat_2017|The mean score result for each state in the SAT 2017 Evidence-Based Reading and Writing exam.| 
|**s17_math**|*float*|sat_2017|The mean score result for each state in the SAT 2017 Math exam.| 
|**s17_total**|*float*|sat_2017|The mean total SAT score for each state in the SAT 2017 exam.| 
|**s18_part**|*float*|sat_2018|The participation rate for each state in SAT 2018 exam (units calculated in percentage)| 
|**s18_ebrw**|*float*|sat_2018|The mean score result for each state in the SAT 2018 Evidence-Based Reading and Writing exam.| 
|**s18_math**|*float*|sat_2018|The mean score result for each state in the SAT 2018 Math exam.| 
|**s18_total**|*float*|sat_2018|The mean total SAT score for each state in the SAT 2018 exam.| 
|**a17_part**|*float*|act_2017|The participation rate for each state in ACT 2017 exam (units calculated in percentage)| 
|**a17_eng**|*float*|act_2017|The mean score for each state in the ACT 2017 English exam.| 
|**a17_math**|*float*|act_2017|The mean score for each state in the ACT 2017 Math exam.| 
|**a17_read**|*float*|act_2017|The mean score for each state in the ACT 2017 Reading exam.| 
|**a17_sci**|*float*|act_2017|The mean score for each state in the ACT 2017 Science exam.| 
|**a17_comp**|*float*|act_2017|The Composite score is the average of the four test scores(english, Maths, Reading, science) in each state for the ACT 2017 exam.| 
|**a18_part**|*float*|act_2018|The participation rate for each state in ACT 2018 exam (units calculated in percentage)| 
|**a18_eng**|*float*|act_2018|The mean score for each state in the ACT 2018 English exam.| 
|**a18_math**|*float*|act_2018|The mean score for each state in the ACT 2018 Math exam.| 
|**a18_read**|*float*|act_2018|The mean score for each state in the ACT 2018 Reading exam.| 
|**a18_sci**|*float*|act_2018|The mean score for each state in the ACT 2018 Science exam.| 
|**a18_comp**|*float*|act_2018|The Composite score is the average of the four test scores(english, Maths, Reading, science) in each state for the ACT 2018 exam.| 

## Conclusion

SAT and ACT exam participation rate are inversely proportionate to their sub test scores. States tend to have higher scores with low participation rate and lower scores with high participation rate in their respective tests.
It is likely that states administering only ACT test have very high scores in SAT test as these students who attempted SAT exam were independent, confident and well-prepared.

Most states with statewide participation rate in any exams were implented as such due to state policies. States would want to be accountable to all of their students and constantly seek reviews in their education sector. This includes reviewing exams and having competitive bids to companies to earn state contracts for it. The best exams would be ideally aligned to the state's education interest. Hence, we can see states changed from statewide ACT exams to the statewide newly revamped SAT exam.(post 2016)

## Recommendation

Noted that Alaska have a total participation rate of 76% in either SAT or ACT exams in year 2018.
From 2017 to 2018, Alaska had a 32% decrease in ACT exam participation rate. However this only translated to a 
less than proportionate increase in SAT exam participation rate in that same year.(5% increase)
 
Hence, there may be a significant number of students in Alaska who did not take ACT or SAT exams.
Further noted from external sources that The Alaska state government currently do not administer ACT or SAT exams.
[which-states-require-students-to-take-the-sat-or-act](https://www.edweek.org/teaching-learning/which-states-require-students-to-take-the-sat-or-act)
This provides an opportunity for CollegeBoard to introduce ideas to raise SAT participation rates in Alaska.

To increase participation rate in SAT exam, we can suggest to the Alaska state government to make SAT part of their high school curriculum test. With regards to the cost of the SAT exam, Collegeboard can introduce subsidies for the exam. Students would be able to take the SAT exam for free if it was part of their high school curriculum test.
TO further encourage participation in the SAT exam, Collegeboard can also offer free online PSAT and SAT exam resources to junior high school students from Alaska. PSAT exam is a preliminary exam which is easier in difficulty as compared to the SAT exam. This will help students to be conditioned to the difficulty of the SAT exam in their senior year. 

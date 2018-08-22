## Summary 

You can access  details of analysis from the Pretest&Interim_Data_Exploration&Analysis.ipynb notebook .
### Task 1
#### Questions?

*  i. By how many points did the Alliance wide average Lexile score grow from Pretest to Interim test?
*  ii. By how many points did each school’s average Lexile score grow from Pretest to Interim test in each grade and school wide (all grades)?
*  iii. For how many students (alliance wide) did we have the Pretest score but not the Interim test score? How did you treat these students in your analysis?
#### Answers
* İ) Alliance wide average Lexile score grow from   845.4 to 878.62 which is exacly 33.22 points.
* İİ) School’s average Lexile score grow  3.93 percent from Pretest to Interim test in each grade and school wide.
* İİİ) 130 students have got their pretest score  but not interim score. For Students that didn't have Interim score, we can either drop them so that our data will not be skewed or we can replace them its Interim Score from NULL to the Interim MEAN Values or Min or Max values.

### Task 2
#### Question?
*  What percentage of English Learners at each school grew at least one Lexile level from the Pretest to the Interim Test? 
#### Answer
*  English Learners at each school 16.0 percent grew at least one Lexile level from the Pretest to the Interim Test.


### Task 3
#### Question?
*  What percentages of students receiving special education services at each school achieved either Grade-Level or College-Ready Lexile Levels on the Interim test? 
#### Answer
*  10.65 percentages of students receiving special education services at each school achieved either Grade-Level or College-Ready Lexile Levels on the Interim test.
## Task4:
#### Questions?
*  i. Step wise detail of your approach in answering the above questions and any assumptions you made in cleaning/analyzing the data. Please provide this task wise for each task stated above (Task 1-3). You should provide clearly annotated code (optional: you can also provide your log file as additionally).


*  ii. Your key takeaways from the data (assume the audience for this portion is our Board of Directors) and evidence/charts to support your conclusions. Assume that your audience is keen on understanding overall trends and not diving deep into any statistical terms.


*  iii. The additional analysis you would like to do if you had an additional few days to work with the data and why the additional analysis would be important.


*  iv. If applicable, any additional data you would like to have which would allow you to explore additional implications of the data.

#### Answers
*   i. I used python and its library(pandas) to discover(compare files, figure out missing data), clean  and analyze the data(Details can be seen through the Pretest&Interim_Data_Exploration&Analysis.ipynb file).While exploring data I assumed that students id's were unique.

*   ii. To provide concise result  I mainly focused on data engineering part .Such as , instead of just manually correcting missing value from the excell file I code to prove my hypothesis and answer the questions(Why's  , how's). It took a little longer than I expected but the code now can be used over and over again when we had the same problem . 
        Basically I was trying to find permenant solutions to the problem so that we would not spend the same amount of time for the next time whe we had the same problems . Rather than data engineering we could focus on visulazition to simplfy our result for the board of director.
*   iii. If I had  a few additional days to work , I could have visualized my analysis using Tablaeu or other tools to provide visually appealing insights.

*   iv.  if I would have had additional time and data (such as school's latitude  and longtitude or just address) It would be interested to check correlation between student's success and school's socio-cultural environment.

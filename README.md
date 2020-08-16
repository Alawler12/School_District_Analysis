# PyCitySchools – School District Analysis

## Analysis Overview
The purpose of this analysis was to evaluate the individual schools in a given district to find patterns in spending and testing performance.  The original analysis was completed in the weekly Module, while this Challenge required a re-analysis given a new circumstance; it was found that the 9th graders at Thomas High School had cheated on their exams.  Consequently, their data had to be removed and all of the THS data re-evaluated relative to the other schools in the district.  The goal of this project was to understand what difference the change in 9th grade data made to the analysis overall.

## Results
Over the course of this Challenge, it became clear that there might be an error within the starter code we were given.  Logically, a removal of an entire grade’s worth of testing data, should show a significant change in the overall testing percentage, but there was little observable difference in the data.  In some cases, there was some change in outcome compared with the Module, but within the scope of the challenge, it was difficult to observe a significant difference.  I will try to evaluate any difference for each metric below.

### Key Metrics
**School District Summary**
- There was no change in the summary for the school district as a whole.  

**School Summary**
-  When the data for the THS 9th graders was removed from the DataFrame, Thomas High School’s passing data dropped from the 90’s to the 60’s.  But when the data was recalculated for just the 10th-12th grade scores, THS passing data returned back to the 90’s with statistically insignificant changes.
- The passing scores for THS: 
    - Module: Math – 93.27%, Reading – 97.31%, Overall - 90.94%
    - Challenge: Math - 93.19%, Reading - 97.02%, Overall - 90.63%
- So there was a very small change between the Module and Challenge, so recalculating without the 9th graders had some effect. However, the change is less than .5% and can hardly be recognized as significant.
    
    
 **Module Per School Summary**   
![Module_per_school_sum.PNG](https://github.com/Alawler12/School_District_Analysis/blob/master/Resources/Module_per_school_sum.PNG)
**Challenge Per School Summary**
![Challenge_Per_School_recalculated_percents.PNG](https://github.com/Alawler12/School_District_Analysis/blob/master/Resources/Challenge_Per_School_recalculated_percents.PNG)


**THS compared to other schools**
- There was no real change in Thomas High School’s performance relative to other schools in the district.  THS remained as the second best school even with the adjusted data.  Again, any change from the Module analysis is less than .5%

**Module Top Schools**
![Module_top_schools.PNG](https://github.com/Alawler12/School_District_Analysis/blob/master/Resources/Module_top_schools.PNG)

**Challenge Top Schools**
![Challenge_top_schools.PNG](https://github.com/Alawler12/School_District_Analysis/blob/master/Resources/Challenge_top_schools.PNG)


**Math and Reading Scores by Grade**
- Math and reading scores showed that the values for THS 9th graders had been replaced by ‘nan’ but there was no change in other grades or compared to other schools.

**Math Scores by Grade**

![Challenge_score_by_grade_math.PNG](https://github.com/Alawler12/School_District_Analysis/blob/master/Resources/Challenge_score_by_grade_math.PNG)

**Reading Scores by Grade**

![Challenge_score_by_grade_reading.PNG](https://github.com/Alawler12/School_District_Analysis/blob/master/Resources/Challenge_score_by_grade_reading.PNG)


**Scores by School Size**
-There was no change is how schools were evaluated by size, as the number of students enrolled in each school did not change.

**Scores by School Type**
- There was no change in score by school type, as all school types remained the same regardless of the number of cheating students who attend it.

## Summary
There were no major changes observed in the updated district analysis after the reading and math scores for 9th graders at THS had been replaced with NaNs.  There should have been an observable change in reading, math, and overall percentages for THS when the data was adjusted, but there was not.  It can only be concluded that there was an error in the starter code, because following all directions for the challenge did not yield the results that were expected.  This is a good lesson in allowing the data to guide the outcome instead of the expectation of what the data will say.  I’m confident that someday when I have more experience, I will be able to find the mistake in the solution, but at present, these are my conclusions.

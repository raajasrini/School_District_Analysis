# School_District_Analysis

## Overview : 
  
  ####  The School district Anlaysis is to provide insigths of performance trends and patterns to help school district board to take strategic decisons on the budget and improvements. The student funding and student test score analysis is to provide summary view of the following 
  
  * School district , school spendings, school summary with type and size, per school summary view of reading and match scores aveerage and overall passing scores. 
  
  * To accomodate Thomas Schoool change request to replace the math and reading scores NaNs for 9th grade while keeping the rest of the data intact.
  
  * Refactor to provide Thomas school summary view of 10th to 12th grades and repeat overall school distrct analysis.
  
  * To provide summary view of school spending , school size and school type.
  
## Results:

 ### [School Analysis Result](https://github.com/raajasrini/School_District_analysis/blob/main/analysis/election_analysis.txt) report provides details overivew.

* The district summary has been affected after the change has been implemented in the ninth grade score for Thomas High School. The [snapshot](https://github.com/raajasrini/School_District_Analysis/blob/main/Resources/1_sd_NaN-9thGrade.png) provides the 9th grade scores updated to NaN. 

  
* The [district summary](https://github.com/raajasrini/School_District_Analysis/blob/main/Resources/2_DistrictSummary.png) view provides the following changes after repalce of 9th grade to NaN for Thomas high school. 
  * The **Average Math score** is reduced to 78.9 from 79.0
  * Slight reduction in **% Passing Math** (74.80% from 74.98) and **% Passing Reading** ( to 85.7 from 85.81)
  * **Overall Passing Percentage** reduced to 64.9 from 65.17.

  
* Thomas High School details are below after the replacement of ninth grade score to NaN.
  * Number of 10th-12th graders from Thomas High School (THS) :  1174
  * Number of the passing students from the 10th-12th grade from Thomas High School :  1064
  * All the students passing math from THS :  1094
  * All the students passing reading from THS :  1139
  * Number of all the students passing math and reading from THS :  1064
  
* The [school summary view](https://github.com/raajasrini/School_District_Analysis/blob/main/Resources/3.Schools_Summary.png) provides the performance relative to other school after replacing the ninth grader's math and reading scores
  * The **Average Math score** is increased to 78.9 from 79.0
  * Scores elevated in **% Passing Math** ( **93.18** from 66.90) and **% Passing Reading** ( to **97.01** from 69.66)
  * **Overall Passing Percentage** increased to **90.63** from 65.07.
  
* How does replacing the ninth-grade scores affect the following:
* [Math and reading scores by grade](https://github.com/raajasrini/School_District_Analysis/blob/main/Resources/5.Math_Read_Scores%20by%20Grade.png) provides the view of math and reading grades by schools.
    * Reading scores are in the range of 80 and above for all grades
    * Cabrera , Griffin , Holden , Pena , Shelton , Wilson and Wright high schools are in the above 80% in math scores for all grades.
    * Thomas high school 9th grade score is NaN for both math and reading scores.

* [Scores by school spending](https://github.com/raajasrini/School_District_Analysis/blob/main/Resources/7.Scores_School_Pending.png) ( per student) view provides the summary of **Avergare math and read Score ,  % Passing in math and reading and Overall Percentage**
    * Wilson high scole scores 90% in overall passing score in the Large school size and spending per student is in the range of <$584
    * Medium school size has overall passing score of 90% and above.
    * Two small schools in size has 89% and above overall passing scores.
    
* [Scores by school size](https://github.com/raajasrini/School_District_Analysis/blob/main/Resources/6.Scores%20by%20School%20Size.png)
 *  Small and Medium schools scores 90% and above in ** % Passing in math and reading and Overall Percentage** and average read  & math score are above 83%
 * Large schools %passing math score is 70% and overall passing score is 58% which needs an improvement. 
 
* [Scores by school type](https://github.com/raajasrini/School_District_Analysis/blob/main/Resources/8.ScoresbySchoolType.png)
    * Charter schools have good scores above 83% in average math & read and % passing scores of math and read are above 90%. Overall passing score is 90%.
    * District schools needs an improvement and focus on **overall passing score of 58% and % passing in math is 67%**

##  Summary: 
   ###
   The school district analysis provides the view of the reading and math scores caluclations and potential impacts replaced with NaN in Thomas high school 9th grade. 
   *
   * Gradewise **Read and Math** average scores depicts the reading scores are good but needs a focus in math score in all the grades.
   * Small & Medium size schools scores good based on the scores by spending 
   * Large schools size needs an improvement in overall passing score though the spending is high in the range of above 585.
   * District schools needs to be focus on improvement when compared to Charter schools. 

# School_District_Analysis

## Overview of the school district analysis

We are tasked with analyzing data over standardized math and reading test scores. Overall, we want to prepare all standardized test data for analysis, recording, and presentations to provide an insight about performance trends and patterns. More specifically, we want to see how the school's test scores are impacted by spending bugdets, school size, and type of school as these affect making decisions regarding school budgets and priorities. 

In addition to the above, we have been notified by the school board that there is evidence of academic dishonesty. Specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. We have taken these scores out of the analyzation and reporting on how these changes affected the overall analysis, including the specified analysis for each category mentioned in the above paragraph. 

## Results: 
*	How is the district summary affected?
  
    Comparing the two charts below, we can see that removing Thomas High School 9th grade students decreases the Average Math Score, Percent Passing Math, Percent Passing Reading, and Percent Overall Passing by 0.1 up to 0.3 points, where Average Reading score remained the same. 

    With all students:
    ![District_Summary_Module](/Images/District_Summary_Module.PNG)
  
    Removing THS 9th grade students:
    ![District_Summary_Challenge](/Images/District_Summary_Challenge.PNG)

*	How is the school summary affected?

    In removing the THS 9th grade students, clearly the only school that will have changes is Thomas High School. We notice between 0.1 and 0.3 changes in all categories in Thomas High School, most of them decreasing; but the Average Reading School actually increased. 
    
    With all students: ![Per_School_Summary_Module.PNG](/Images/Per_School_Summary_Module.PNG)
  
    Removing THS 9th grade students: ![Per_School_Summary_Challenge_THS](/Images/Per_School_Summary_Challenge_THS.PNG)
  
*	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

    Thomas High School scores 2nd place in Percent Overall Passing compared to other schools, no matter whether the 9th graders are included or not included. 
    
    With all students: ![Top_5_Module.PNG](/Images/Top_5_Module.PNG)
    Removing THS 9th grade students: ![Top_5_Challenge](/Images/Top_5_Challenge.PNG)
  
*	How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade
        
        The only changes from the original data, is that there are no scores recorded for 9th grade THS students since those were removed. 
        
        Math scores and the left and Reading scores on the right: 
        
        ![Math_Scores_Grade_Challenge](/Images/Math_Scores_Grade_Challenge.PNG)  ![Reading_Scores_Grade_Challenge](/Images/Reading_Scores_Grade_Challenge.PNG)
    * Scores by school spending
        
        No changes, since this removing THS 9th graders score's doesn't impact how much money was budgeted. 
        
        ![Spending_Ranges_PerStudent_Both](/Images/Spending_Ranges_PerStudent_Both.PNG)
    * Scores by school size
        
        No changes, since this removing THS 9th graders score's doesn't impact how many students attended the school.  
        
        ![Spending_Ranges_PerStudent_Both](/Images/Spending_Ranges_PerStudent_Both.PNG)
    * Scores by school type
        
        No changes, since this removing THS 9th graders score's doesn't impact what the school type was.  
        
        ![School_Type_Both.PNG](/Images/School_Type_Both.PNG)
  
## Summary:

We notice subtile changes in each of the categories from Thomas High School after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
1. The Average Math score went from 83.41 to 83.35. 
2. The Average Reading Score went from 83.85 to 83.89
3. The Pecent Passing Math went from 93.27 to 93.19
4. The Percent Passing Reading went from 97.31 to 97.02
5. The Percent Overall Passing went from 90.95 to 90.63

Overall, if there was a situation of academic dishonesty, I would expect there to be more subtile changes than a 0.1 to 0.3 change in the categories mentioned above. I would expect each of the catergories to decrease more significantly. We also notice that the Average Reading Score increased very slightly, which would be unusal if there was a sitatuion of academic dishonesty. 

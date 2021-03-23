# School District Analysis

## Overview

The purpose of this analysis is to aggregate the data and showcase trends in school performance. This analysis helps the School Board and Superintendent in making decisions regarding school budgets and prorities.

Unfortunately after completion of the analysis, it was learned that one school(Thomas High) has been dishonest in submitting the 9th grade scores. This discrepancy has to led to a revaluation of the analysis and here's the findings.

## Results
**1. Impact on District Summary**

   Cleaning up the student data by removing the dishonest scores has luckily had no impact on the Overall District Summary. The omition of a particular school's 9th grade scores were negligible, when scores from 15 schools were aggregated on District level. 
   <p><img src="https://github.com/yazhcodes/School_District_Analysis/blob/main/Challenge/Resources/Images/District%20Analysis.png"></p>

**2. Impact on Thomas High School Summary**
   
   However when drilled down to school level, Thomas High School's Average Scores and Passing Percentages have take a minor dip after eliminating the dishonest entries.
   
   **Before Clean Up:**
   
   <p><img src="https://github.com/yazhcodes/School_District_Analysis/blob/main/Challenge/Resources/Images/Thomas%20High%20School%20Analysis%20(Before).png"></p>
   
   **After Clean Up:**
   
   <p><img src="https://github.com/yazhcodes/School_District_Analysis/blob/main/Challenge/Resources/Images/Thomas%20High%20School%20Analysis%20(After).png"></p>

**3. Impact on Thomas High School's relative performance**

   More good news for Thomas High School authorities! The school is still the ***second best*** in the District based on Passing Percentages, just after Cabrera High school. 
   
   **Before Clean Up:**
   
   <p><img src="https://github.com/yazhcodes/School_District_Analysis/blob/main/Challenge/Resources/Images/THS%20Performance%20Comparison%20(Before).png"></p>
   
   **After Clean Up:**
   
   <p><img src="https://github.com/yazhcodes/School_District_Analysis/blob/main/Challenge/Resources/Images/THS%20Performance%20Comparison%20(After).png"></p>

**4. Other Impacts:** 
       
 * **Math and reading scores by grade**
     The scores of 9th graders in THS have been set to NaN (NULL). This gives us no scope to analyze this category of scores, but the scores of remaining grades (10th - 12th) remain intact and are available for analysis.
     
   **Math Scores:**
   <p><img src="https://github.com/yazhcodes/School_District_Analysis/blob/main/Challenge/Resources/Images/THS%20Grade%20wise%20Math%20Scores.png" width=300></p>
   
   **Reading Scores Scores:**
   <p><img src="https://github.com/yazhcodes/School_District_Analysis/blob/main/Challenge/Resources/Images/THS%20Grade%20wise%20Reading%20Scores.png" width=300></p>
 
 * **Scores by school spending**
         
      The Average Per Capita Budget of Thomas High School is $638, which falls into the Budget Range $630-644. Upon comparing the outcomes of the range $630-644 before and after cleaning up the data, it is found that there is no impact of unclean data on this analysis.
   <p><img src="https://github.com/yazhcodes/School_District_Analysis/blob/main/Challenge/Resources/Images/Scores%20by%20School%20Spending.png"></p>
 
 * **Scores by school size**
     
     Similarly, there is no impact of the dishonest data on the Report based on School Size. Thomas High School is a Medium sized school, and the scores against this category have remained the same before and after cleaning up the data.
     
   <p><img src="https://github.com/yazhcodes/School_District_Analysis/blob/main/Challenge/Resources/Images/Scores%20by%20School%20Size.png"></p>
 
 * **Scores by school type**
   
   Lastly the Report based on School Type is also unimpacted by this discrepancy! Thomas High is a Charter school, whose scores are the same before and after removing the incorrect 9th grade scores.
   
   <p><img src="https://github.com/yazhcodes/School_District_Analysis/blob/main/Challenge/Resources/Images/Scores%20by%20School%20Type.png"></p>
    
## Summary
Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

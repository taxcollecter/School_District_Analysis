# School_District_Analysis

## Overview of the school district analysis
    In this exercise, we reviewed student performance on standardized test by multiple factors (School Size, Type, Funding) while excluding the 9th grade of Thomas High School due to concerns of Academic dishonesty. To perform this analysis, we aggregated data from the student level to show underlying trends in school performance. This work was done to aid the school board in the allocation of funding and budgeting. 

## Results
-How is the district summary affected?
    In review of the data at the district level while excluding Thomas High School, it appears as if Reading and Math scores were impacted. Math scores went from a mean of 79.0% to 77.0%. Reading scores went from a mean of 81.9% to 81.0%.  

### District Analysis
![District Visual](https://github.com/taxcollecter/School_District_Analysis/blob/3bc561296932cbc55de75f8335c1b167a3541840/Resources/District_Analysis.png)
 
-How is the school summary affected?
    The School Summary does show a slight impact as Thomas High School (THS) is among the higher performing schools from a scores perspective. Naturally by removing an entire grade from the dataset, the overall scores are negatively impacted.

-How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
     Comparing THS' performance against its peer Charter schools (Shelton, Wilson, Cabrera, Griffin) after our data augmentation does show that the scores were negatively impacted. However, the school still hovers confidently in the 83 percentile for both measures. 

-How does replacing the ninth-grade scores affect the following:
     -Math and reading scores by grade
        
        
-Scores by school spending

-Scores by school size

-Scores by school type

## Summary
    In summary, by removing the 9th grade scores of Thomas High School we are seeing an overall negative impact to the School district's Math and Reading scores. If academic dishonesty is at the root of variance, we will need to work with the faculty to ensure this does not happen again and confirm student's confidence in performing during these test. Prior to the data augmentation, the 9th graders at THS led the other grades in Math scores and were 2nd in Reading scores to the 12th graders. By removing the 9th graders scores via this excercise, these 4 data points at a District and School level are visibly impactful. To maintain the school's trend in potential performance, the dishonesty will need to be rooted out. 

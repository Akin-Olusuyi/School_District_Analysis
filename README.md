# School_District_Analysis

## Overview
The purpose of the analysis is to generate a summary school district report based on several key metrics such as but not limited to:
  - Average scores (math & reading) across schools in the district
  - Budget
  - School Type
  - School Size
  - Passing percentage 

## Results
Here is the link to the code used for this analysis ![Code](https://github.com/Akin-Olusuyi/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)

Below are key points to highlight as a result of analyzing the school district data:

- **How is the District Summary Affected after the 9th grade math and reading scores for Thomas High School were replaced with NaN?**
  - The Average Math Score drops by 0.1%
  - The Average Reading Score remained the same.
  - The percentage of students passing math increased by 0.9%.
  - The percentage of students passing reading increased by 1.0%
  - The Overall percentage of student passing both math and english combined increased by 0.8%.

Here is an image of the district summary dataframe ![District Summary DataFrame](https://github.com/Akin-Olusuyi/School_District_Analysis/blob/main/Resources/district%20summary%20dataframe.png)

- **How is the School Summary affected after the 9th grade math and reading scores for Thomas High School were replaced with NaN?**
  - The average math and reading scores increased by less than 0.1%.
  - The % passing math decreased by less than 0.1%
  - The % passing reading decreased by 0.3%.
  - The % overall passing decreased by 0.3%.

- **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
  - There was no change in the performance of Thomas High School relative to other schools

- **How does replacing the ninth-grade scores affect the following:**
  - Math and reading scores by grade
      - There were no changes to both scores for grades 10-12. Only grade 9 scores were affected
      
  - Scores by school spending
      - No changes
  
  - Scores by school size
      - No changes

  - Scores by school type
      - No changes


## Summary

In summary, after replacing 9th grades for THS with Nan, there were some changes as it can be seen in the District Summary and School Summary dataframes. However, this were minor changes around scores, ranging from 0.1% to a maximum of 1.0%. I have detailed out those changes in the result section above. 

      
 

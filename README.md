# School_District_Analysis

# Overview of School District Analysis
Aggregate data provided to showcase trends in school performance to assist the school board and superintendent in making decisions regarding the school budgets and priorities.  Assisting Maria, we will analyze data on student funding and students' standardized test scores to provide insights about performance trends and patterns which will be used to inform discussions and strategic decisions at the school and district level.

Evidence of academic dishonesty was found in the data file; specifically in math and reading grades for Thomas High School ninth graders.  We have been tasked to replace the scores for THS ninth graders with NaNs while keeping the remaining data intact and reperform the analysis.  

# Results
\* Tables below:

**Original** signifies data before THS ninth grade scores replaced with NaN

**Clean** signifies data after THS ninth grade scores replaced with NaN

- ## District Summary
  - Replacing the student grades in math and reading from THS had a small effect in lowering the Overall Passing percentage by only 0.1%; as well as lowering Passing Math (0.2%) and Reading (0.3%) percentages.

#### Original
![o-district summary](https://user-images.githubusercontent.com/74840026/126019171-847213be-3303-4979-82c3-f89871670211.PNG)
#### Clean
![c-district summary](https://user-images.githubusercontent.com/74840026/126019169-3719721f-45f8-412d-96a8-fa5fb563a4c8.PNG)
 
- ## School Summary
  - Comparing the original and clean DataFrames of the School Summaries, the only school affected was THS.  Once cleaned, Overall Passing percentages went down by 0.31% with Math (0.09%) and Reading (0.29%) percentages being lower as well.  Coincidentally, Average Reading scores for THS increased slightly (0.05) with the replacement of the ninth grade scores.

#### Original
![o-school summary](https://user-images.githubusercontent.com/74840026/126019973-8460b31f-1fbc-40d0-88c3-bd9332d44e49.PNG)
#### Clean
![c-school summary](https://user-images.githubusercontent.com/74840026/126019972-8b36d030-d1fe-4df6-a891-9c428caa5d5e.PNG)

- ## Thomas High School
  - Replacing the ninth-grade scores for THS had little effect in the overall performance of the school when compared to the rest of the schools.  THS remained as the third worst performing school after the data was cleaned.

- ## Ninth Grade

    - ### Math and Reading Scores
      - Replacing THS ninth grades scores with NaN showed a significant drop in the total ninth grade math and reading averages for the district.  Math averages were lowered by 5.57 points and Reading averages were lowered by 5.58 points. 
    - ### Scores by School Spending
      - Replacing THS ninth grade scores with NaN showed no significant change in the Scores based by Spending per Student.  Since the student count did not change, only scores, it did not affect this metric.
    - ### Scores by School Size
      - Replacing THS ninth grade scores with NaN showed no significant change in the Scores based by School Size.  Since the student count did not change, only scores, it did not affect this metric.
    - ### Scores by School Type
      - Replacing THS ninth grade scores with NaN showed a slight lowering of Scores based by School Type.  Overall Passing percentages were lowered by 0.04%, Math Passing percentage was lowered by 0.01% and Reading Passing percentage was lowered by 0.04%.
      #### Original
      ![o-school type](https://user-images.githubusercontent.com/74840026/126022805-b6b68218-9be1-4267-97db-614f27451bc8.PNG)

      #### Clean
      ![c-school type](https://user-images.githubusercontent.com/74840026/126022814-3ce97b76-b331-4e2e-903a-014a09a323e0.PNG)

# Summary
- In summary, replacing the scores of THS ninth graders with NaN due to inaccuracies did not have a major effect on the overall outcomes from the analysis.  With only 1% of the total student grades being replaced, it did show slight changes in the following metrics:
1. District summary Overall Passing percentage
2. School summary Overall Passing percentage
3. Thomas High School Overall Passing percentage
4. Ninth Grade scores in both Math and Reading
- Removal of the offending students from the total student count would have resulted in a slightly different outcome.

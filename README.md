# School_District_Analysis

# Overview of School District Analysis
Agrigate data provided to showcase trends in school performance to assist the school board and superintendent in making decisions regarding the school budgets and priorities.  Assisting Maria, we will analyze data on student funding and students' standardized test scores to provide insights about performance trends and patterns which will be used to inform discussions and strategic decisions at the school and district level.

Evidence of academic dishonesty was found in the data file; specifically in math and reading grades for Thomas High School ninth graders.  We have been tasked to replace the scores for THS ninth graders with NaNs while keeping the remaining data entact.  

# Results

- ## District Summary
Replacing the student grades in math and reading from THS had a slight affect in lowering the Overall Passing percentage by only 0.1%; as well as lowering Passing Math(0.2%) and Reading(0.3%) percentages.

**Original**
![o-district summary](https://user-images.githubusercontent.com/74840026/126019171-847213be-3303-4979-82c3-f89871670211.PNG)
**Clean**
![c-district summary](https://user-images.githubusercontent.com/74840026/126019169-3719721f-45f8-412d-96a8-fa5fb563a4c8.PNG)
 
- ## School Summary
Comparing the original and clean DataFrames of the School Summaries, the only school affected was THS.  Once cleaned, Overall Passing percentages went down by 0.31% with Math(0.09%) and Reading(0.29%) percentages being lower as well.  Coincidentally, Average Reading scores for THS increased slightly(0.05) with the replacement of the ninth grade scores.

**Original**
![o-school summary](https://user-images.githubusercontent.com/74840026/126019973-8460b31f-1fbc-40d0-88c3-bd9332d44e49.PNG)
**Clean**
![c-school summary](https://user-images.githubusercontent.com/74840026/126019972-8b36d030-d1fe-4df6-a891-9c428caa5d5e.PNG)

- ## Thomas High School

- ## Ninth Grade

    - ### Math and Reading Scores

    - ### Scores by School Spending

    - ### Scores by School Size

    - ### Scores by School Type

# Summary

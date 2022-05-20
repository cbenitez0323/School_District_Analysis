# School_District_Analysis

## Overview of the school district analysis: 
The purpose of the analysis was to observe the changes to the school's reading and math score after removing the score of Thomas High School's ninth graders. Therefore the analysis consists of altering the data and running a summary analysis consisting of determining the average score, the passing scores, and the overall passing grades of Thomas High School and then comparing it to the other schools.  

## Results: 

- After taking away the reading and math score of the ninth graders at Thomas High School, the district summary that displays the aveerage test scores and score pecentages had a slight decrease overall. This is to be expected as there are less scores and it was suspected that the scores taken out were higher. Then the overall statistics across all the schools would go slightly down. 

<img width="923" alt="district_summary_df" src="https://user-images.githubusercontent.com/102255823/169585003-4149987d-d31b-4bda-bbb0-9fd3e2af6889.png">

<img width="922" alt="distric_summary_df_challenge" src="https://user-images.githubusercontent.com/102255823/169585021-b9da9c71-2f01-42b3-bad9-d137dcfcf253.png">

How is the school summary affected?

- In the school summary, the schools total student population and spending per student were affected by removing the ninth graders because there are less students and therefore with the budget remaining the same, the estimation of spending per student went up. The averages and percentages of the passing scores were also affected and subsequently went down.

<img width="987" alt="per_school_summary_challenge" src="https://user-images.githubusercontent.com/102255823/169587514-f3ae1b7d-930f-481b-a300-c80cd7e27db0.png">

- After filtering the school summary by having the dataframe be sorted by descending overall passing percentage, Thomas High School was still after Cabrera High School. The overall percentage for Thomas High went slightly up but not enough to still surpass Cabrera. 

<img width="985" alt="high_low School" src="https://user-images.githubusercontent.com/102255823/169588441-541d99bc-4b6b-42da-83d2-524192a2d459.png">

<img width="781" alt="highlow_school_challenge" src="https://user-images.githubusercontent.com/102255823/169588454-1a300202-d4a8-435f-8050-e2c1552f404e.png">

-The math and reading scores were affected when comparing the original analysis results and the results after removing the ninth grade scores. Overall, the scores for Thomas High School went up which means the ninth grade score were brining the average down.

<img width="419" alt="reading scores by grade_challenge" src="https://user-images.githubusercontent.com/102255823/169618897-b6b3dbcf-3f47-4138-8d12-f4a21beb2fff.png">

<img width="415" alt="math scores by grade_challenge" src="https://user-images.githubusercontent.com/102255823/169618972-2fb8d553-c13e-4da4-9de1-9ce9f2fc0909.png">

- The summary based on school spending per student shows no changes after excluding the ninth graders. This is likely due to the fact that the ninth grade class being removed would have such a small impacts because of how small the ninth graders at THS are
 compared to the the thousands of other students in the school district. Therefore the impact would be less. 

<img width="839" alt="spending summary" src="https://user-images.githubusercontent.com/102255823/169589464-0f4bb56d-ca2f-4976-b3cd-6564db66dd89.png">

<img width="814" alt="spending summary_challenge" src="https://user-images.githubusercontent.com/102255823/169589483-fdaff4c4-b5e2-4efb-b236-73c5c1b84d2d.png">


- The summary based on school size did not change after removing the ninth graders. This is ideal as the lack of scores should not interfere with the numbers concerning other aspects of the school like budget, sizing, or school type
<img width="829" alt="size summary" src="https://user-images.githubusercontent.com/102255823/169589741-61eae5ee-4046-47a3-847f-34ab4477741f.png">

<img width="747" alt="size summary_challenge" src="https://user-images.githubusercontent.com/102255823/169589755-cc238f0a-3dbc-49ca-b70d-0e30be25925c.png">

- There weren't any changes to the summary based on school type. The numbers stayed consistent and it was likely due to the fact that the difference in removing the ninth graders didnt make a big impact in the averages. On top of that, the numbers were rounded to the nearest whole and therefore it was be harder to notice any smaller changes. 
<img width="797" alt="type summary" src="https://user-images.githubusercontent.com/102255823/169589793-1d3bcf73-1b05-4ec9-8576-7f6ef044bd7f.png">

<img width="705" alt="type summary_challenge" src="https://user-images.githubusercontent.com/102255823/169589813-5c9d3e21-8d16-42f3-a4ed-edaf2a0693b2.png">

## Summary: 
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

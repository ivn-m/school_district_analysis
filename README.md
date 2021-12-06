# School District Analysis

## Purpose
The purpose of this analysis was to calculate school district math and reading scores after evidence of academic dishonesty. To address the academic dishonesty suspected, we removed the math and reading scores of 9th graders at Thomas High School.

## Results

### Changes to district summary
Disclaimer: No data was deleted from the analysis. Values where academic dishonesty was suspected were altered to null values.

The effect of changing the math and reading scores of the 9th graders at Thomas High School to null values changed the underlying base population count, and thus changed figures in our analysis. The total number of null values in our analysis changed from 0 to 461, which in turn reduced the total number of student scores in the analysis from 3,9170 to 38,709. This additionally reduced the number of scores for Thomas High School from 1635 to 1174. This in turn effected the average score calculation, 
    - Number of 10th graders at Thomas High School: 421
    - Number of 11th graders at Thomas High School: 415
    - Number of 12th graders at Thomas High School: 338

Including 9th graders at Thomas High School's reading and math scores:
![image](https://user-images.githubusercontent.com/93107507/144776598-bd327287-4db5-486d-af85-2cddca7b46ce.png)


Excluding 9th graders at Thomas High School's reading and math scores:
![image](https://user-images.githubusercontent.com/93107507/144776277-5a236eef-bb00-422b-81d9-1cf4a1dd87a4.png)


### Changes to school summary
By removing the faulty 9th grade reading and math scores, this caused the average scores for Thomas High School to increase-- which is reasonable considering the scores for the 9th graders were low. The following are the average math and reading scores for Thomas High School with and without the 9th graders part of the calculation:


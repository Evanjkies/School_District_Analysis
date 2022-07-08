# School_District_Analysis

## Overview of the School District Analysis
With this project the goal was to take a dataset that contained math and reading scores from various high schools and remove a compromised section of scores from the data. After this compromised section was removed, the passing grade percentages, as well as the other figures mentioned in the dataset, were recalculated. The data was also filtered and sorted to show broad picture results on a per school and per grade basis.

## Resources
- Data Source: schools_complete.csv , students_complete.csv
- Software: Python 3.7.6, Anaconda, Jupyter Notebook 

## Results
- After the data for Thomas High School 9th graders was nulled, the district summary saw the following changes (pictured below as well):
  - Average Math Score: 79 to 78.9
  - Average Reading Score: 81.9 to 81.9
  - Percent Passing Math: 75% to 74.8%
  - Percent Passing Reading: 86% to 85.7%
  - Percent Overall Passing: 65% to 64.9%

![New_District_Summary](https://user-images.githubusercontent.com/107013312/177903539-9b4f8bae-843d-4b9a-9685-d9361cb8a9b1.png)
![Original_District_Sumamry](https://user-images.githubusercontent.com/107013312/177903555-3f70342c-8b53-4814-9470-95fc9112ff86.png)

- After removing the 9th graders scores from Thomas High School, the outcomes were affected as such:
  - Average Math Score: 83.4 to 83.4
  - Average Reading Score: 83.8 to 83.9
  - Percent Passing Math: 93.3% to 93.2%
  - Percent Passing Reading: 97.3% to 97%
  - Percent Overall Passing: 90.9% to 90.6%

- Replacing the 9th grade Thomas High School scores also affected:
   - Scores by school spending
   - Scores by school size
   - Scores by school type
## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
After the 9th grade math and reading scores for Thomas High School had been marked with NaNs, the average reading score increased, while the percent passing reading went down. This suggests that among the 9th grade scores, there was a few percentage of the grade scoring highly but a higher percentage of the grade, compared to the other grades, were scoring above passing level. The *percent overall passing* fell from 90.9% to 90.6% which makes sense given the drop in *percent passing math* described above and the drop from 93.3% to 93.2% in *percent passing math*. The *average math score* didn't change.

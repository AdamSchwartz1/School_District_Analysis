# School_District_Analysis
## Overview
The purpose of this analysis was to modify the results from the original findings due to some students mis-reporting their scores. It was determined that some of the math and reading scores for 9th graders from Thomas High School were fraudulent so I had to change all of those scores to NAN and then re-run the analysis.

## Results
Using bulleted lists and images of DataFrames as support, address the following questions

- How is the district summary affected?
    - The district summary was not affected a lot. Math and reading scores both slightly dropped but the overall passing percent only dropped by .3%
- How is the school summary affected?
    - All other school remained the same since I only modified Thomas High School. For Thomas High, the passing math percentage, passing reading percentage, and overall passing percentage all dropped by roughly .1%, .3%, and .32% respectively. So again, not a large impact
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    - Replacing these scores did not have an overall impact when ranked against other schools. Although the overall passing percentage dropped by roughly .32%, they still had the second highest overall passing percentage out of all schools.
- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade - Since I only removed the scores for 9th grade students from Thomas, the only change was that those scores show as 'nan'. All other scores remained the same
    - Scores by school spending - Since the percentage of scores barely changed for Thomas High, the scores by school spending was unaffected due to the inclusion of the other schools in            that range.
    - Scores by school size - Since the percentage of scores barely changed for Thomas High, the scores by school size was unaffected due to the inclusion of the other schools in                that range.
    - Scores by school type - Since the percentage of scores barely changed for Thomas High, the scores by school type was unaffected due to the inclusion of the other schools in                that range.

## Summary
Overall, removing the ninth grade reading and math scores for Thomas High School from our analysis barely affected the results. Here are four takeaways that I had:
    1. There were either very few scores altered or Thomas high performed pretty similar across all grades. Looking at the breakdown of reading and math scores by grade level prior to removing the 9th grade totals, I'm leaning towards the latter. All four grades at Thomas High performed very similarly so when the 9th grade was removed, their average scores and percentages weren't affected much.
    2. The breakdown of scores by school spending, school size, and school type weren't affected at all.
    3. The overall district summary didn't see much of an affect. The overall passing percentage only dropped by .3%.
    4. When it came to ranking schools based on overall passing percentage, Thomas still had the second highest percentage. Their percentage dropped from 90.95% to 90.63 % but that wasn't enough to drop them from the second highest performing school.
This analysis took a fair amount of work to remove the 9th grade scores from Thomas High and didn't yield any substantial changes, but I was able to provide the accurate numbers while upholing the district's standards of academic honesty.

Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

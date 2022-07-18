# School_District_Analysis
## Purpose
The main purpose of this analysis to replace ninth graders' math and reading grades at Thomas High School with NaN and see the overall average and passing rate for THS, see what changes, effects are made to the data by removing their grades from the dataset.

###Results
-District Summary: As we can see from the following charts, number of students did not change since students information are still there, but grades are replaced with NaN; ![original district summary](https://github.com/dilnigar1007/School_District_Analysis/blob/main/Resources/original%20district%20summary.png)
![adjusted district summary](https://github.com/dilnigar1007/School_District_Analysis/blob/main/Resources/adjusted%20district%20summary.png) Passing math and reading percentages both went down by 0.1%. For example, % passing math went from 74.98 to 74.8 and % passing reading went from 85.80 to 85.7; and overall passing percentage dropped by 0.27%, from 65.17 to 64.9. 
-Thomas High School performance relative to the other schools: THS average math, reading and passing percentages all dropped. For example, average math score went from 83.41 to 83.35; average reading score went from 83.84 to 83.90; % passing math dropped from 93.27% to 93.19%; % passing reading dropped from 97.31 to 97.02%; and overall passing going from 90.95% to 90.63%. These decreases are not significant. Even after changing the scores with NaN for the 9th graders, Thomas High School still considered as the second best school since the overall passing % is still high. 
-Scores by school spending: ![original spending summary](https://github.com/dilnigar1007/School_District_Analysis/blob/main/Resources/original%20spending%20summary.png)
![adjusted spending summary](https://github.com/dilnigar1007/School_District_Analysis/blob/main/Resources/adjusted%20spending%20summary.png)
Thomas High School is under $631-$645 bin, and if we look at these charts, we can conclude that replacing these grades dropped the scores by 0.01-0.02 which is a slight change. 
-Scores by school size: Result shows that there is a slight change to the medium size school category (1,000-1,999)
-Scores by school type: Result indicates there are 0.01-0.05 point drops to charter schools' scores.

###Summary
Replacing ninth grade's grades with NaN had a slight impact on all the categories we had in this dataframe: average math score, average reading score, passing math percentage, passing reading percentage, and overall passing rate. These all dropped when we replaced the grades because we don't have any grades for anyone in the 9th grade, which lowered the scores by less than 1 point. We can say that the effect was not significant because Thomas High School's passing percentages for both reading and math were above 90% even after dropping some scores from the dataframe, and it was still included in the top five schools list. 

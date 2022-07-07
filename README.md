# School_District_Analysis_Challenge

## Purpose
After analyzing data for a school district, it came to the attention of the school board that some of the data may have been compromised. There is suspicion that the grades for the 9th grade class for Thomas High School may have been altered; they have asked me to replace those grades with NaNs and recalculate the previous results I submitted. Below are my results and an analysis of what may have changed in the results by removing potentially dishonest test scores. 

## District Summary
There seems to be very little effect on the district summary. There are very small changes (less than 1%):

Original: 

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/district_summary_df_og.png)

Adjusted:

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/district_summary_df_adjusted.png)


## School Summary
When reviewing the adjusted data compared to the original, there is a significant drop in Thomas High School's % Passing Math, Reading and Overall Passing scores. With the compromised data, their scores were in the 90's, but when the compromised data is extracted and recalculated - their scores drop significantly into the 60's.

Original: 

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/school_sumary_og.png)

Adjusted:

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/school_sumary_adjusted.png)

## School Type
There was not a significant movement in data when reviewing the Type of School. Even when we rounded out to the next decimal - it would have no real effect on changing the overall percentages of the passing numbers. 

Original:

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/School_type_og.png)

Adjusted:

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/School_type_adjusted.png)

## Size of the School
The only noticeable difference on the bins for the size of the schools, was a very small decrease in the % Passing for Reading. It dropped from 96.8 to 96.7. This again would not effect the overall number when rounding so does not have a noticeable difference on the results.

Original:

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/school_size_og.png)

Adjusted:

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/school_size_adjusted.png)

## Spending Ranges
Thomas High School falls into the bin of $631-645 in terms of Spending Ranges (per Student). When reviewing the original data against the adjusted data - there is a very small decrease from 84.4% in the % of Passing Reading to 84.3% in the adjusted data.

Original:

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/spending_ranges_og.png)

Adjusted:

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/spending_ranges_adjusted.png)

## By Grades for Each School
Now that we have replaced the data in the new analysis, the grades for reading and math will appears as NaN's instead of displaying the original data they populated. 

Original Math Scores: 

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/by_grade_og_math.png)

Adjusted Math Scores:

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/by_grade_adjusted_math.png)

Original Reading Scores: 

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/by_grade_og_reading.png)

Adjusted Reading Scores:

![this is an image](https://github.com/eneubauer2022/School_District_Analysis/blob/main/Resources/by_grade_adjusted_reading.png)

## Summary
Thomas High Schools overall passing percentage dropped significantly once we removed the suspicious data of the 9th grade test scores. 
The data also shows us a decrease in percentage of students passing math and reading for Thomas High School. 
When we removed the 9th grade test scores, Thomas High School also lost its status as in the Top Five of the school district based on the Overall Passing Percentage. 
It does seem, however that even removing the population of the 9th grade from a whole high school, had very little effect on the total numbers for the school district. Even when we recalculated back in the test scores for the other grades for Thomas High School, they seemed to be inline and back into the 90's. We should exercise caution though when removing such a large amount from a data set without properly reviewing all the effects it may have on the data. 

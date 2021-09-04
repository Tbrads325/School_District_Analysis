# School_District_Analysis
## Overview
After performing the school district analysis for Maria and her supervisor evidence of academic dishonesty 
appears within the reading and math scores of 9th grade students at Thomas High School. As a result, this Challenge 
tasks us with replacing the mentioned scores with NaNs and performing the district analysis again to see any 
changes. 

## Results

- How is the district summary affected?
The district summary is not really affected with the Average Scores, and Passing Percentages remaining relatively
the same with any changes most likely occuring in the 10th and 100th decimal places. This can be seen below in the 2 dataframes:

### Challenge District Summary

![Name](url)

### Module District Summary

![Name](url)

- How is the school summary affected?
Once again school summary is barely influenced after removing the 9th grade reading and math scores of Thomas High School.
The changes occur within the 10th and 100th decimal places again as shown in the two dataframes show below in the Thomas High School Rows.

### Challenge School Summary

![Name](url)

### Module School Summary 

![Name](url)

- How does replacing the ninth graders' math and reading scores affect Thomas High School's performance
relative to other schools?

Even after removing their 9th graders' math and reading scores Thomas High School still ranks 2nd overall with its overall passing % within
the district. (However if the academic dishonesty is proven true it could potentially make the district question the other scores of the school)
As mentioned previously the actual percentages and average scores barely changed for Thomas High School following the removal of the 9th graders scores.

### Challenge Top 5

![Name](url)

### Module Top 5

![Name](url)

- How does replacing the ninth-grade scores affect the following:

	- Math and reading scores by grade

	All that was affected in these dataframes were that the cell for Thomas High School 9th grade scores were replaced with a NaN.
	The other grades were unaffected and stayed the same.  

	- Scores by school spending

	Thomas High School falls in the 3rd bin $630-644 so if any change were to occur it would happen in this row. However, as with the whole of this
	new analysis the scores and percentages barely changed at all and after performing formatting not change can be noticed at all. 

	- Scores by school size

	Thomas High School falls in the 2nd bin of Medium size schools so if any change were to occur it would happen in this row. However, once again after
	formatting the scores and percentages are the same as before implying that the changes occured in the 10th and possibly 100th decimal places after removing the 
	ninth grade scores.

	- Scores by school type

	Thomas High School is a Charter school so any change would happen in this row of the scores based on type dataframe. However, due to formatting once again their exists no significant change
	in these scores/percentages. 
	
	
## Summary

Thomas High School Changes:

### With 9th Grade
![Name](url)
### Without 9th Grade
![Name](url)

Average Math Score: Dropped from 83.418349 to 83.350937
Average Reading Score: Increased from 83.848930 to 83.896082
% Passing Math: Dropped from 93.272171 to 93.185690
% Passing Reading: Dropped from 97.308869 to 97.018739
% Overall Passing: Dropped from 90.948012 to 90.630324





# School_District_Analysis
Project involving Python, Pandas Library, Jupyter Notebook to analyze school district data and showcase trends in school performance.

## Overview of the analysis
Given data for students in 15 local high schools, we want to analyze the data to determine facts about math and reading scores for each school based on the grade, size of the school, type of school, and budget or spending for the school. The school board found evidence of academic dishonesty for the ninth grade Thomas High School students in reading and math. Therefore, in the analysis, we replace these grades with no score (NaN) and perform the analysis based on the new dataset.

## Results
Using bulleted lists and images of DataFrames, answer the following:
-How is the district summary affected? The only district summary changes are in the total students because the average math and reading scores are different by only hundredths or thousandths. So the average scores and the percentages are not different when rounded to 1 decimal or a whole number.
-How is the school summary affected? Initially, the only difference in the school summary is for THS we had included the 9th graders in the percentages of passing math, reading, and overall. Once we correct this total number of students by only calculating the scores for 10th-12th grade at THS, the results are similar to our original school summary.
-How does replacing the 9th graders math and reading scores affect THS performance relative to the other schools? THS data did not change much. The percentages of math, reading, and overall passing scores varied by about three tenths lower with the clean data over the original data which included the 9th graders. THS is still in the top five, second to be exact, of all schools based on overall passing percentage.
-How does replacing the 9th grade scores affect:
	- Math/reading scores by grade: It only affects the THS 9th grade score for both math and reading which now says nan
	- Scores by school spending: data stayed the same here
	- Scores by school size: data stayed the same
	- Scores by school type: data stayed the same

## Summary 
Summarize 4 changes in the updated school district analysis after reading and math scores for 9th grade at THS have been replaced with NaNs.
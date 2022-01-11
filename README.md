# School_District_Analysis
Project involving Python and using the Pandas Library with script written in Jupyter Notebook to analyze school district data and showcase trends in school performance.

## Overview of the analysis
Given data for students in 15 local high schools, we want to analyze the data to provide a summary of the key metrics for each school in the district. This includes average math and reading scores for each school based on the grade, size of the school, type of school, and budget or spending for the school. Also, we will determine the top and bottom performing schools based on the overall passing percentage of students. One problem with the original data is that the school board found evidence of academic dishonesty for ninth grade Thomas High School students in reading and math. Therefore, in our new analysis, we replace these grades with no score (NaN) and perform the analysis based on the new student data.

## Results
These are the results based on the data without any math or reading scores from 9th graders at Thomas High School (due to evidence of academic dishonesty). We compare the new findings to the results when the 9th graders scores from THS were included in the data.

- District Summary: The only district summary changes are in the total students because the average math and reading scores differ by only hundredths or thousandths of a point. Thus, the average scores and percentages for math and reading are not different when rounded to 1 decimal place or the nearest whole number.

- Screenshot of district summary: ![District Summary](https://github.com/kmaluccio/School_District_Analysis/blob/main/Resources/Clean_District_Summary.png)

- School Summary: In this summary, the only school affected is Thomas High School. Since the 9th grade scores were removed from this school, the average math and reading scores were not greatly affected. However, the percentages were in the high 60's because they were still including the 9th graders. Once we correct this total number of students by only calculating the percentages for 10th-12th grade at THS, the results are similar to the original school summary. Therefore, there are not any significant changes in the school summary with the updated student data.

- Screenshot of school summary:  ![School Summary](https://github.com/kmaluccio/School_District_Analysis/blob/main/Resources/school_summary.png)

- Relative to other high schools, replacing the 9th grade scores at THS did not cause significant impact. The percentages of math, reading, and overall passing scores varied by about three tenths of a percent, lower with the clean data over the original data which included the tainted 9th grade scores. THS is still in the top five, second to be exact, of all schools based on overall performance.

- Impact of replacing the 9th grade scores at THS:
	- Math/reading scores by grade: The THS 9th grade score for both math and reading reads as nan and this is the only change
	- Scores by school spending, scores by school size, and scores by school type:
		-Data stayed the same (since the change in average scores and overall passing was less than one point and less than one percent), see the results in the tables below

![Scores by Spending](https://github.com/kmaluccio/School_District_Analysis/blob/main/Resources/scores_by_school_spending.png)
![Scores by Size](https://github.com/kmaluccio/School_District_Analysis/blob/main/Resources/scores_by_school_size.png)
![Scores by Type](https://github.com/kmaluccio/School_District_Analysis/blob/main/Resources/scores_by_type.png)

- Top five and bottom five schools:
![Top 5 Schools](https://github.com/kmaluccio/School_District_Analysis/blob/main/Resources/Top5Schools.png)
![Bottom 5 Schools](https://github.com/kmaluccio/School_District_Analysis/blob/main/Resources/Bottom5Schools.png)

## Summary 
The changes in this school district analysis include having no data for 9th graders at THS when we view the school summary by grade; the average math and reading scores by grade has changed to NaN for 9th graders at THS; the total number of students has changed since we have removed all 9th graders from THS from the count; and the math, reading, and overall passing percentages decreased by about 0.3%. Overall, the changes did not strongly affect the school district analysis. To run the script for this analysis, see the file named PyCitySchools_Challenge.ipynb to answer any remaining questions.


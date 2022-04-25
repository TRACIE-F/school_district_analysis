# School District Analysis for PyCity Schools

## Overview of the school district analysis: Explain the purpose of this analysis.
The following analysis digs into the PyCity Schools, focusing on student performance in math and reading and district spending. The analysis dives into the impact of removing the 9th graders of Thomas High School from the datat to determine the impact on the school's overall rank and performance.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.
Original data is presented with yellow highlights. The data with the 9th graders of Thomas High School dropped is presented with green highlights.


**District Summary**
 *  In the District Summary, the changes appear small, with indications that the 9th grade class of Thomas High School (THS) is slightly above average. Their results do bring the district averages up slightly, when they are impacted.
 *  Average math and average reading scores are extremely close, if not identical.
 *  Passing percentages for math and reading were also very close. Without them included, both scores decreased by approximately 0.01%, which does indicate the THS 9th graders of were able to nudge those percentages up a bit.
 *  The overall pass rate for the district is lower without the THS, which again indicates the freshmen at THS scored well enough to impact the overall data by 0.27%.
*Old Data*
![district_summary_old](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/district_summary_ogdata.png)
*New Data*
![district_summary_new](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/district_summary_newdata.png)

**Per School Summary**
  * The Per School Summary indicates similar findings to the District Summary - THS has a solid freshman class that brings their overall scores up, but they do appear to show stronger scores in math and bring overall scores down in reading.
  * Average math and reading scores are relatively similar again, but average reading scores do go up slightly without the 9th graders of THS. 
  * The same trend from above continues for the passing percentages. Reading percentages go up without the 9th graders, but math percentages go down.
  * Overall passing percentages are higher with the 9th grade class included. 
*Old Data*
![school_summary_old](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/perschool_summary_ogdata.png)
*New Data*
![school_summary_new](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/perschool_summary_newdata.png)

**THS Comparison**
 * THS does not appear to lost its standing in the district, even without its 9th grade class, although Griffin High School did surpass a few categories and come much closer in others.
*Old Data*
![top5old](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/top5_olddata.png)
*New Data*
![top5new](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/top5_newdata.png)

**Math and Reading by Grade**
 * The breakdown of math and reading scores by grade validates all assumptions prior in the analysis. The 9th grade class at THS excels at math...

*Old Data*
![math old](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/readingscores_by_grade_olddata.png)
*New Data*
![math new](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/mathscores_by_grade_newdata.png)

 * ...and the 9th grade class at THS is the second lowest scoring class in reading.

*Old Data*
![reading old](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/readingscores_by_grade_olddata.png)
*New Data*
![reading new](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/readingscores_by_grade_newdata.png)

**Scores by School Spending**
 * Removing the 9th graders of THS had zero impact on the scores by school spending.
*Old Data*
![spending old](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/spending_summary_ogdata.png)
*New Data*
![spending new](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/spending_summary_newdata.png)

**Scores by School Size**
 * Removing the 9th graders of THS had zero impact on the scores by school size.
*Old Data*
![size old](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/size_summary_ogdata.png)
*New Data*
![size new](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/size_summary_newdata.png)


**Scores by School Type**
 * Scores per the type of school appear unaltered by the abesnce of the 9th graders of THS.
*Old Data*
![type old](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/type_summary_ogdata.png)
*New Data*
![type new](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/type_summary_new_dta.png)

## Summary
While the changes in the data did not seem major, the following changes made clear:

 * THS freshmen are better at math than reading (See **Per School Summary**):
  * THS math scores dropped without the 9th grade class
  * THS reading scores went up without the 9th grade class 
 * Overall, THS freshmen are passing at a rate higher than their peers (See **Per School Summary**)
  * THS freshmen are passing at a high rate, overall 
 * The fremen at THS had scores high enough to make a positive impact in the district, especially in math and overall scoring (See **District Summary)

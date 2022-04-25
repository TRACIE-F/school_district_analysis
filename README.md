# School District Analysis for PyCity Schools

## Overview of the school district analysis: Explain the purpose of this analysis.
The following analysis digs into the PyCity Schools, focusing on student performance in math and reading and district spending. The analysis dives into the impact of removing the 9th graders of Thomas High School from the datat to determine the impact on the school's overall rank and performance.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.
Original data is presented with !yellow highlights. The data with the 9th graders of Thomas High School dropped is presented with +green highlights.

  * District Summary
    *  In the District Summary, the changes appear small, with indications that the 9th grade class of Thomas High School (THS) is slightly above average. 
    *  Average math and average reading scores are extremely close, if not identical.
    *  Passing percentages for math and reading were also very close. Both decreased by approximately 0.01%, which does indicate the THS 9th graders of were able to nudge those percentages up a bit.
    *  The overall pass rate for the district is lower without the THS, which again indicates the freshmen at THS scored well enough to impact the overall data by 0.27%.
 How is the district summary affected?
![district_summary_old](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/district_summary_ogdata.png)
![district_summary_new](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/district_summary_newdata.png)

How is the school summary affected?
![school_summary_old](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/perschool_summary_ogdata.png)
![school_summary_new](https://github.com/TRACIE-F/school_district_analysis/blob/main/Resources/perschool_summary_newdata.png)



How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

How does replacing the ninth-grade scores affect the following:

Math and reading scores by grade

Scores by school spending

Scores by school size

Scores by school type

Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

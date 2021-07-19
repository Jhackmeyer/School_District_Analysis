# School_District_Analysis
An analysis of school testing and funding. Python, Pandas, and Jupyter Notebook.

## Overview

While analyzing schools and student performance data, we are told that some data is compromised due to academic dishonesty.  As a result, we nullify the affected data, and reapply the analysis to determine performance with respect to grade, spending (per student), size of school, and type of school.


## Results

- In the District Summary, looking at both outcomes rounded to the tenths place, the adjusted data seems to be slightly lower.  The Average Math Score and % Passing Reading are about 0.1 less, % Math Passing is 0.2 less, and % Overall Passing is 0.3 less.
- In the School Summary, again results seem to differ by some tenths of a point.  Math scores are about the same, while reading scores actually go up about 0.1 points.  % Passing Math fell by 0.1, and % Passing Reading and Overall % Passing both fall by 0.3.
- Thomas High, however, is still in 2nd place amongst the top performing schools, based upon overall passing percentage.

  - By grade, the only scores affected are the 9th graders'.  As their score was higher than the average for their grade, dropping that data reduced the average score for all 9th graders in the district.  This affected average math by 0.3 and average reading by 0.1.
 
  - By school spending, only the bin $630-644 changed, though none of the changes were significant to our specifications: 3 significant figures for Average scores and 2 significant figures for percentages.

  - By school size, only the bin for medium-sized schools changed, though none of the changes were significant to our specifications: 3 significant figures for Average scores and 2 significant figures for percentages.

  - By school type, the charter schools' % passing data also falls, but the differences are, again, statistically uninteresting to 3 significant figures for Average scores and 2 significant figures for percentages.

## Summary

It seems removing the Thomas High 9th grader data from the data set reduced scores across the board, in average math score and % passing either or both subjects. The exception of average reading score across all schools suggests Thomas High 9th graders were scoring blow average amongst their school for reading scores, but still passing.  Outside of reading, their performance is pretty consistently above average and passing.

However, these differences are very slim, and when looking with respect to school type, school size, and school spending per student, these differences are almost unnoticeable.  This is evidenced, too, seeing that Thomas High still holds 2nd place for overall passing students.

Having to excise a chunk of data from an analysis is not ideal.  There is always a challenge, going back through and managing which analyses and conclusions are affected by the change.  Spending per student should not be different, but certainly average grade must be calculated with a different student total, for example.

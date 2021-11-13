# School_District_Analysis

Analyzing School District Test Scores

## Overview of Analysis:

The analysis of the school district reading and math scores
included a district summary, a school summary, the high and low performing
school’s summary, a summary for overall math and reading scores, a school
budget summary, a summary by school size and lastly, a summary of scores by
school type.

## Purpose of Analysis:

Math and reading test scores are used to measure a school's
performance. The district wants to understand how some of the key metrics may
be affecting the math and reading scores so that they can make decisions
surrounding the high schools they are responsible for. By studying these
metrics district officials will be able to make better decisions about how to
improve the district’s school performance. They explore the scores to identifying
key metric anomalies.

## Results:

During the first run of results, it was apparent to the
district officials the ninth grade reading and math scores were skewed. It was
necessary to remove all Thomas High School's 9th grade math and reading scores
to get an accurate picture of what was happening at each high school.

This didn't affect district results more than a percent.
Below is the before and after for the District Summary.

##### Before:

![](Resources/DistrictSummaryBefore.png)

##### After:

![](Resources/DistrictSummary.png)

The school summary shows that the Thomas High School's
percentages went up significantly, around 30%.

![](Resources/THSBeforeAfter9thRemoval.png)

### Key Metrics :

#### Scores by school spending:

This shows a positive correlation between the amount of
money a school spends per student and the student’s math and reading scores. The more money spent per student, the higher the scores seem to be.

![](Resources/ScoresBySchoolSpending.png)

#### Scores by school size:

This shows a correlation between the number of students and
the student’s math and reading scores. The smaller the school size is, the
higher the scores seem to be.

![](Resources/ScoresBySchoolSize.png)

#### Scores by school type:

This shows a correlation between the type of school and the student's
math and reading scores. Charter schools seem to perform around ten points
higher for each average and each percent measured.

![](Resources/ScoresBySchoolType.png)

#### Math and Reading Scores (by grade):

We can see the only difference in the before and after run of the analysis is THS' ninth grade scores.

- Math Scores:
![](Resources/MathScoresByGradeBeforeAndAfter.png)

- Reading Scores:
  ![](Resources/ReadingScoresByGradeBeforeAndAfter.png)

#### High and Low Performing Summary:

We can see below before changing the high and low summaries THS was ranked #2 in the top five performing schools; and, that it only took removing THS' ninth grade  scores to eliminate them from the top five schools.
Before:
![](Resources/HighBefore.png)
After:
![](Resources/High.png)

We can also see that THS wasn't in either the before or after summary of the five lowest performing schools.

Before:
![](Resources/LowBefore.png)
After:
![](Resources/Low.png)


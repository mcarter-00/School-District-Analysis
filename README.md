# School District Analysis
Performing an analysis using school funding and standardized test scores to inform a school district on their budget and priorities.

---
# Challenge
The school district discovered that the standardized test scores for ninth grade students at Thomas High School were incorrect, and requested for updated data summaries. After further discussion, it was best to only replace the ninth grade math and reading scores at Thomas High School while keeping all other data associated with this student group intact. 

Both math and reading scores were replaced with "NaN", which represents a "Not-a-Number" value, for 461 student records. Although this may seem like a significant number, these score replacements did not affect data summaries significantly overall.

When assesssing average scores and passing percentages among the 15 high schools in the school district, the average math score dropped .1, the average reading score stayed the same, the percentage passing math dropped 1%, tbe percentage passing reading dropped 1%, and the overall passing percent dropped 1%.
### School District Summary
![School District Summary](IMG1_DistrictSummaryDF.png)


When assessing school summaries, the score replacements did affect the ranking of the top five performing schools. Thomas High School ranked second place in the top five performing schools with a 91% overall passing. After replacing both math and reading scores, Thomas High School was taken out of the top five category since they now display a 65% overall passing. On the plus side, these changes did not place Thomas High School among the bottom five performing schools. Those ranks remained the same. Per the revised School Summary, Thomas High School ranks 8th place among 15 schools in the district.
### School Summary
![School Summary](IMG2_PerSchoolSummaryDF.png)

### Top Five Performing Schools
![Top Five Performing Schools](IMG8_TopFiveSchools.png)

### Bottom Five Performing Schools
![Bottom Five Performing Schools](IMG9_BottomFiveSchools.png)


Another plus side from this data replacement is that it did not change the math and reading scores by grade. Granted, both the average math and reading score summaries were stratisfied by school and grade level. As showed in the images below, the summary tables display "NaN" for ninth grade at Thomas High School. 
### Average Math Scores by Grade & School
![Average Math Scores by Grade & School](IMG6_AvgMathScores_byGrade&School.png)
### Average Reading Scores by Grade & School
![Average Reading Scores by Grade & School](IMG7_AvgReadingScores_byGrade&School.png)


When reviewing the School Spending summary, this data change did not impact the spending ranges for either the average math scores or average reading schools. However, this data change did impact the spending ranges for passing percentages. According to the image below, there is a 6% decrease in % passing math, a 7% decrease in % passing reading, and a 6% decrease in % overall passing in the $630-644 spending range.
### School Spending Summary
![School Spending Summary](IMG3_SchoolSpendingSummaryDF.png)


When reviewing the School Size summary, removing the ninth grade scores did not affect the average math and reading scores, but it did affect the passing percentages for medium-sized schools (1,000-2,000). In this category, % passing math, % passing reading, and % overall passing dropped 6% each. Before the data change, the School Size summary showed that medium-sized school had a high performance (91% overall passing) compared to small (90% overall passing) and large schools (58% overall passing). Given the data change, medium size school are the second in performance (85% overall passing).
### School Size Summary
![School Size Summary](IMG4_SchoolSizeSummaryDF.png)


In reviewing the last summary on School Types, this data change also affected the passing percentages that compared charter and district schools. Fortunately, it did not affect the average scores for these two school types. Removing the scores resulted in a reduction in charter school's passing percentages. Before the data change, charter schools had very high passing percentages: 94% passing math, 97% passing reading, 90% overall passing. After the data change, charter schools now have a 90% passing math, 93% passing reading, 87% overall passing. On the plus side, these rates are still far superior when compared to district schools.
### School Type Summary
![School Type Summary](IMG5_SchoolTypeSummaryDF.png)

# School_District_Analysis
The school board notified Maria and her supervisor that there was evidence of some academic dishonesty amongst the 9th graders at Thomas High School. Maria has reached out to me to replace the 9th grade Thomas High School math and reading scores with NaNs while keeping the rest of the data intact. Maria would then like me to rerun the analysis and write up how these changes on how it affected the overall original analysis.
## Results
### How is the district summary affected?
Original Analysis:
![District original analysis](https://github.com/backwater-graphics/School_District_Analysis/blob/main/Images/District%20Summary/originals-district.png)
---
After suspected dishonesty from the 9th graders at Thomas High School the math and reading scores were turned into null data, which then kicked off an analysis to recalculate the percentages of the passing math, reading, and overall scores but did not change the total count of students as it was based off the student ids and not grades.
Re-Analysis:
![District reanalysis analysis](https://github.com/backwater-graphics/School_District_Analysis/blob/main/Images/District%20Summary/rework-district.png)
---
After comparing the two charts and removing the Thomas High School 9th grade scores it had only a very little impact on the 39,170 students’ data set. The change was calculated to less than 1% difference with the numbers still rounding to the same whole numbers

### How is the school summary affected?
Before the dishonesty issue was raised by the school board the Thomas High School had a 91% overall passing rate and was 2nd in list of the top 5 schools.
Original Analysis: 
![School original analysis](https://github.com/backwater-graphics/School_District_Analysis/blob/main/Images/School%20Summary/school-summary-original.png)
---
Re-Analysis:
 ![School reanalysis analysis](https://github.com/backwater-graphics/School_District_Analysis/blob/main/Images/School%20Summary/school-summary-rework.png)
---
After removing the 9th grade reading and math scores from the Thomas High School grades and recalculating the grades with just the 10th through 12th grade students we noticed that it had a huge impact by dropping the overall passing rate from 91% to 65%.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Before replacing the 9th grade math and reading scores at Thomas High school, the school ranked number 2 in the district which raised concerns with the school board. The school board made the decision to have all 9th grade reading and math scores from Thomas High School replaced with NaNs.
Original Analysis:
![School originalMath analysis](https://github.com/backwater-graphics/School_District_Analysis/blob/main/Images/Math%20and%20reading%20scores%20by%20grade/original-math%20scores%20by%20grade.png)
--- 
![School originalReading analysis](https://github.com/backwater-graphics/School_District_Analysis/blob/main/Images/Math%20and%20reading%20scores%20by%20grade/original-reading%20scores%20by%20grade.png)
--- 
After replacing the 9th grade data, we see that Thomas High School fell to the bottom of the rankings within the district.

Re-Analysis:
 ![School reworkMath analysis](https://github.com/backwater-graphics/School_District_Analysis/blob/main/Images/Math%20and%20reading%20scores%20by%20grade/rework-math-scores.png)
--- 
![School reworkReading analysis](https://github.com/backwater-graphics/School_District_Analysis/blob/main/Images/Math%20and%20reading%20scores%20by%20grade/rework-reading-scores.png)
--- 

### How does replacing the ninth-grade scores affect the following:
*Math and reading scores by grade

   
 Math & Reading scores before

When we look at the Thomas High School scores, they had an 83.6 math average and an 83.7 reading average for the 9th grade tests prior to removing those scores.

  
Math & Reading Scores after 
*Scores by school spending
Original Analysis:
 
 
Re-Analysis:

 
 

We notice that Thomas High School fell into the $630-644 spending bucket. When we removed the 9th grade scores it reduces the "% Passing Math", "% Passing Reading" and "% Overall Passing" scores for spending bucket "$630-644" as we can see the results above. we also noticed that we had to have the decimal point to the hundredths place is order to see the nominal impact there was by removing the 9th grade scores.
*Scores by school size
Original Analysis:
 
Re-Analysis:
 
Thomas High School is a medium sized school that again we need to have the decimal point to the hundredths place is order to see the nominal impact there was by removing the 9th grade scores.
*Scores by school type
Original Analysis:
 
Re-Analysis:
 
Thomas High School is a charter school that again we need to have the decimal point to the hundredths place is order to see the nominal impact there was by removing the 9th grade scores.

## Summary
Here are the four changes that we saw happen when the school board asked to have the Thomas high school 9th grade reading and math scores replaced with NaNs: 
The first change that we noticed was that the overall passing rate for the Thomas High school changed from 91% to 65%.
The second change that we noticed is once the grades were removed the Thomas High school went from 2nd in the district to 13th in the district out of 15 schools.
The third change that we noticed was that the 9th Grade reading and math scores changed to NaNs on the report.
The fourth change that happened was in addition to the overall passing rate, the math and reading averages and passing percentages all saw some shifts in numbers.
The major changes will be seen at the lower views of the disaggregated data with minor impact to the larger data views.



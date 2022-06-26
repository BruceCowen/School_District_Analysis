# School_District_Analysis
school analysis python
## Overview of the School District Analysis
The purpose of this analysis was to inport the data based on 15 different schools in a county and analyze the data to get the math and reading scores for each schools and compare them. We utilized jupyter notebook to write our script and read the data. Each school was also catagorized based on the size, school type, and budget of each schools to see if we could see a change based on these factors. For Thomas High School some of the scores for 9th grade were changed so we had to clean the data and replace it all with an NaN.
## Results
### District Summary
When comparing the first District summary to the new district summary with Thomas High School, the scores are about the same as they were with the whole data set. The scores for the new dataframe were a little lower but it was not very significant.
### School Summary
When we look at individualschool summaries the only one affected by the change is Thomas High School. There was a drop in the in the passing math percentage, the passing reading percentage, and the overall passing percentage. This is because the ninth grade students altered their scores for better grades. 
### Math and Reading by Grade
Since the whole ninth grade of Thomas High School was dropped we dont see a change of the overall summary for each school by grade level. If we took the average of each grade level for each grade level and combined them into a single list we would only see that the total ninth grade would be lower.
### School Spending
When we group the new data by school spending and compare it to the old we dont see much of a change in the data. The section which Thomas High school is in is a little lower but not by much.
### School Size
Grouping by school size also leads to no big change. the data looks pretty much the same.
### School Type
When grouped by school type we see that the charter schools out performed the district schools greatly. As for the before and after data we see a drop in charter scores because Thomas High School was a charter school and there grades dropped overall. the District school's data is unaffected.
## Summary
After replacing the ninth grade of Thomas High School with NaNs we see an overall drop in catagories that Thomas High School is in. When looking at the ninth grade overall scores we see a drop in there passing percentages. Looking at the School Type we see a drop in charter schools passsing percentages. Looking at Thomas high school singulary we see a drop in their passing percantages. Overall, droping the ninth grade of Thomas high school had little affect on the data.

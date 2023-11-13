# School District Analysis with Pandas and Jupyter Notebook

## Introduction
This project involves analyzing school district data using the Pandas library in a Jupyter Notebook environment. The analysis covers various aspects such as district summary, school summary, performance comparison between schools, average scores by grade, and breakdowns based on spending, school size, and school type.

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## Tasks Completed

### 1. District Summary
- Calculated key metrics for the entire district.
- Created a DataFrame to provide a high-level snapshot of the district's performance.

### 2. School Summary
- Computed key metrics for each school.
- Generated a DataFrame summarizing the performance of each school.

### 3. Top and Bottom Performing Schools
- Identified the top 5 and bottom 5 performing schools based on overall passing percentage.
- Created DataFrames ("top_schools" and "bottom_schools") to store the results.

### 4. Math and Reading Scores by Grade
- Calculated average math and reading scores for students in each grade at each school.
- Presented the results in separate DataFrames.

### 5. Scores by School Spending
- Grouped schools into spending ranges per student.
- Calculated mean scores and passing percentages for each spending range.
- Compiled the results into a DataFrame ("spending_summary").

### 6. Scores by School Size
- Grouped schools into size categories (small, medium, large) based on total students.
- Created a DataFrame ("size_summary") to display school performance based on size.

### 7. Scores by School Type
- Utilized the per_school_summary DataFrame to analyze school performance based on school type.
- Created a DataFrame ("type_summary") for this purpose.



1. **Impact of School Size:**
   - Smaller schools tend to have higher overall passing percentages compared to larger ones.
   - Students in smaller schools may benefit from more personalized attention and resources.

2. **Effect of Spending per Student:**
   - Schools with lower spending per student often show higher overall passing percentages.
   - Efficient allocation of resources might be a contributing factor to academic success.


# Observable Trends
In analyzing the district data encompassing 15 schools, a notable observation is the discrepancy in passing rates between reading (85.81%) and math (74.98%), with only 65.17% passing both subjects. This suggests a potential area of improvement in math education across the district.

## Individual School Performance
Examining individual schools, the top five performers based on overall passing rates are **Cabrera High School**, **Thomas High School**, **Griffin High School**, **Wilson High School**, and **Pena High School**. Conversely, the lowest performers include **Rodriguez High School**, **Figueroa High School**, **Huang High School**, **Hernandez High School**, and **Johnson High School**. It's crucial to note that the poorer performing schools generally have significantly fewer students than their higher-performing counterparts.

## Impact of School Size
A closer look at overall passing rates based on school size reveals that while there isn't a substantial difference in average scores for individual subjects, there is a marked increase in passing rates for smaller to medium-sized schools compared to larger ones. This highlights potential advantages in fostering a more intimate learning environment.

## School Spending Effects
Analyzing scores based on school spending demonstrates that both insufficient and excessive spending per student correlate with lower overall passing rates. Notably, spending over $1.70 million per student is associated with a drastic decrease in scores, indicating the importance of effective resource allocation.

## School Type Comparison
The scores categorized by school type reveal a significant disparity, with **charter schools** outperforming **district schools**. Charter schools exhibit an overall passing rate approximately 40% higher than that of their district counterparts, emphasizing the potential benefits of the charter school model.

In conclusion, this analysis provides valuable insights into various factors influencing school performance. Addressing the observed disparities in math scores, considering the impact of school size, optimizing spending per student, and exploring the successful practices of charter schools can contribute to informed decision-making for enhancing overall student success. For a detailed walkthrough of the analysis, refer to the Jupyter Notebook file in this repository.






## Conclusion

This analysis provides valuable insights into the performance of schools within the district. It highlights trends related to school size, spending, and type that can inform decisions for improving overall student success. The use of Pandas and Jupyter Notebook facilitated efficient data manipulation and visualization, making the analysis process seamless and insightful.

For a detailed walkthrough of the analysis, please refer to the Jupyter Notebook file provided in this repository.

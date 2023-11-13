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

## Observable Trends

1. **Impact of School Size:**
   - Smaller schools tend to have higher overall passing percentages compared to larger ones.
   - Students in smaller schools may benefit from more personalized attention and resources.

2. **Effect of Spending per Student:**
   - Schools with lower spending per student often show higher overall passing percentages.
   - Efficient allocation of resources might be a contributing factor to academic success.

## Conclusion

This analysis provides valuable insights into the performance of schools within the district. It highlights trends related to school size, spending, and type that can inform decisions for improving overall student success. The use of Pandas and Jupyter Notebook facilitated efficient data manipulation and visualization, making the analysis process seamless and insightful.

For a detailed walkthrough of the analysis, please refer to the Jupyter Notebook file provided in this repository.

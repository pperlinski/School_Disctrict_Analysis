# School District Analysis

## Summary

The purpose of this project was to use Pandas dataframes to organize and condense facets of school district standardized testing data and to extract various tables of information from it. In our scenario, a section of our dataset was suspected to have been tampered with, so we had to nullify the suspicious data, and build our tables so that the suspicious data does not alter or corrupt our findings or the rest of the dataset.

## Analysis and Conclusions

Before the 9th grade scores were replaced, the overall passing percentages looked like this:
![before](https://user-images.githubusercontent.com/105957781/176891235-35061138-5181-4df6-acc3-67a25e9fda06.png)

Thomas High School, despite being a Charter School, ranks among other district schools with its math and reading scores. Its overall passing percentage barely breaks 65%. Once 9th grade scores are excluded, however, Thomas High School's numbers begin to look closer to what is typical for other charter schools:

![after](https://user-images.githubusercontent.com/105957781/176891232-281a4026-c902-4cda-a6e3-b9ba3751dd8f.png)

After 9th grade scores were nullified, Thomas High School's passing math % becomes 93.87%, passing reading % becomes 97.01, and passing percent overall is revealed 90.63%. This is a significant difference from the original scores and showed that the 9th graders likely bombed their tests somehow, severely bringing down the average for the school overall. 

After replacing the 9th graders scores:

- District summary statistics are not significantly affected, as only 461 out of 39,170 students are modified in the data (1.25% overall)
- Effects on the school summary are most noticable in % passing math, % passing reading, and % passing overall
- Thomas High School becomes the #2 top performing school behind Cabrera High School.
- Thomas High Schools falls in the Medium tier for school spending.
- Thomas High Schools falls below the average for the medium tier for scores by school size.
- Thomas High School's passing scores by type are more typical for a charter school than the district school level performance it had before.

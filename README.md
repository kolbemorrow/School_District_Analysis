# School District Analysis

### Overview of School District Analysis:
An analysis of city district schools was conducted on math and reading scores, comparing average scores with the school spending budget, size and type of school. Due to academic dishonesty, reading and math grades for Thomas High School 9th graders were removed from the data set and a new analysis was conducted.

## School District Results:
### District Summary:
Before the data removal the district summary of total schools, students, school budget, average math and reading scores, percentage passing math and reading, and percentage of overall passing students displayed:
![MODdistrict_summary](https://user-images.githubusercontent.com/99298165/163697541-b8456422-a8a6-4031-a979-ce9e5195315c.png)
The results after removing the compromised data and recalculating the summary:
![CHALdistrict_summary](https://user-images.githubusercontent.com/99298165/163697933-573671a8-5323-42a7-9328-2003b44d4ac5.png)
From these calculations it is apparent had the Thomas High School 9th grade scores remained, the performance of the district average math scores would be 0.1% higher.
### School Summary:
Before the data removal the Thomas High School summary of average math and reading, percent passing math and reading, and overall passing rate displayed:
![MODschool_summary](https://user-images.githubusercontent.com/99298165/163699096-19bc7170-68e0-4e12-9bac-0a283eff92d8.png)

After data removal and recalculation:
![CHALschool_summary](https://user-images.githubusercontent.com/99298165/163699098-446bbe9b-cb5e-43b4-8677-4b0bd7050213.png)
Based on these DataFrames the removed data would have increased all values by less than 1%, besides the percent passing reading which would have increased by around 4%. 
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Replacing the ninth grade scores did not dramatically change Thomas High School's performance, most of it's metrics remained with less than 1% difference to the original calculations.

## 1) Average Score by Grade
Average score by grade before data removal:

Math

![MODmath_score_grade](https://user-images.githubusercontent.com/99298165/163699613-cbbf5fb2-2c90-4822-b0e9-03aef6071588.png)

Reading

![MODreading_score_grade](https://user-images.githubusercontent.com/99298165/163699619-9bd2f776-5abd-40f2-b984-e94e00424f4d.png)

Average score by grade after data removal:

Math 

![CHALmath_score_grade](https://user-images.githubusercontent.com/99298165/163699629-babc55f9-78a4-4c89-aaa5-a80a56f0d956.png)

Reading

![CHALreading_score_grade](https://user-images.githubusercontent.com/99298165/163699638-ab35c5b6-0583-411a-8f10-b42a35a5ac6a.png)

The calculated average score per grade was unchanged, however the ninth grade value has been replaced with nan to represent the data removal.

## 2) Scores by School Spending

Average scores by school spending before data removal:

![MODspending_summary](https://user-images.githubusercontent.com/99298165/163700026-44c1aacc-07e9-4347-8882-14094b3da567.png)

Average scores by school spending after:

![CHALspending_summary](https://user-images.githubusercontent.com/99298165/163700036-96e4a76e-76de-42c8-803a-e11117261f0e.png)

All reading score percentages for each spending range increased as a result from the data removal.

## 3) Scores by School Size

Average scores by school size before data removal:

![MODschool_size](https://user-images.githubusercontent.com/99298165/163700144-feb22bea-d091-4212-b02d-6b2f49fb0bec.png)

Average scores by size after:

![CHALschool_size](https://user-images.githubusercontent.com/99298165/163700147-16cafd0d-7f8d-487f-bff1-504dcf529a64.png)

Similar to the school spending analysis, all reading score percentages for each size range increased as a result from the data removal.

## 4) Scores by School Type

Average scores by school type before data removal:

![MODtype_summary](https://user-images.githubusercontent.com/99298165/163700251-8ca1cc5f-f715-44e0-bad8-ddc81eba7f18.png)

Average score by type after:

![CHALtype_summary](https://user-images.githubusercontent.com/99298165/163700270-4d6805cb-bf7c-4e2c-86f1-9c1d28fb2eaa.png)

The average passing reading scores for district schools increased after the data removal.

### Summary:
In conclusion, The removal of data decreased the whole district's overall math average compared to the original, all reading score percentages for each spending range and size range increased, and the overall district reading score average increased. Overall, because of the dramatic affect on statistics for the district a re-test of Thomas High School ninth graders should be considered.

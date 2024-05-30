# Students-Test-Scores-Analysis
![marking](https://github.com/HafshaWahab/Students-Test-Scores-Analysis/assets/152807534/2043c79b-4760-4a8a-be04-713915624432)

## About Dataset

This dataset includes scores from three test scores of students at a (fictional) public school and a variety of personal and socio-economic factors that may have interaction effects upon them. The original dataset generator creator is Mr.Royce Kimmons.
[Data Source](https://www.kaggle.com/datasets/desalegngeb/students-exam-scores)

## Data Dictionary

1. Gender: Gender of the student (male/female)

2. EthnicGroup: Ethnic group of the student (group A to E)

3. ParentEduc: Parent(s) education background (from some_highschool to master's degree)

4. LunchType: School lunch type (standard or free/reduced)

5. TestPrep: Test preparation course followed (completed or none)

6. ParentMaritalStatus: Parent(s) marital status (married/single/widowed/divorced)

7. PracticeSport: How often the student practice sport (never/sometimes/regularly))

8. IsFirstChild: If the child is the first child in the family or not (yes/no)

9. NrSiblings: Number of siblings the student has (0 to 7)

10. TransportMeans: Means of transport to school (school bus/private)

11. WklyStudyHours: Weekly self-study hours(less than 5hrs; between 5 and 10hrs; more than 10hrs)

12. MathScore: math test score(0-100)

13. ReadingScore: reading test score(0-100)

14. WritingScore: writing test score(0-100)

## Goals

1) What factors (features) affect test scores most? (Analysing the demographics of the students and their parents.)

2) Are there interacting features which affect test scores? (Analysing all the different parameters that can influence the test performance of the students.)

## Insights

**1) Scores-**
-	Maths: 275 students scored 100 (highest) and 1 student scored 0 (lowest)

-	Reading: 344 students scored 100 (highest) and 1 student scored 10 (lowest)

-	Writing: 484 students scored 100 (highest) and 1 student scored 4 (lowest)

**2) Gender Analysis-** The count of male and female students is 15217 and 15424 respectively. 
In the test, females had much better scores in Reading and Writing tests than the boys, whereas boys performed better in Maths test.

**3) Parents’ Educational background:**

-	The count of parents who have just completed their college is the highest and the lowest is that of Masters’ degree.

-	From the heatmap analysis it has been analyzed the relationship between parents' education & students' scores, we found that the educational level of the parents has a significant role to play in their kids' test scores as the kids whose parents have Masters’ degrees have performed much better as compared to others.

**4) Parents’ Marital Status-** The marital status of parents has a negligible impact on the test scores of the students.

**5) Ethnicity:**

-	Maximum students are from the Group C

-	But students from Group E have performed much better in the test.

**6) Role of Sports Practice-** The students who practice sports regularly or practice sometimes perform better in analytical subjects (Maths and Writing) as compared to those who do not practice sports at all.

**7) Test Prep Strategy-** It is found that only 34.55% of students have completed the test prep and they are the ones who have performed better than their peers as well.

**8) Weekly Study Hours**- Further, it is seen here that the students who study 5-10 hours or more than 10 hours have performed decently in their tests.

**9) Role of Lunch Given by School-** It is seen that the students receiving standard meals from school have performed comparatively much better than the ones who got free or reduced meals.

**10) Role of Transport means-** The transport means as such has no impact on the student's performance in their tests.

**11) Impact of having Siblings-** Mostly all the kids who either have any siblings or not, they have performed very well in their Reading, followed by Writing and lastly in their Maths tests.

**12) Impact of being firstborn-** There is no significant difference in the test scores on the basis of whether the kid is firstborn or not.

## Conclusion

-	Kids whose parents have ***Masters’ degrees and are from Group E*** ethnic group have performed well.

-	***Regular sports practice, test preps, lunch, and weekly study hours*** are the influencing factors in affecting kids’ test scores.

-	***Parents’ marital status, transport means, and no. of siblings*** have negligible impact on students’ performance.

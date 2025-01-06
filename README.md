# Students_365datascience.com
**Customer Engagement Analysis in Excel Project**
## Case Description
In 2022, there were high expectations for the growth of the 365 company and increased student engagement based on the introduction of new website platform features. Some of these features included,
1. An XP system that enabled students to track their progress, level up, and earn rewards by completing various learning objectives. 

2. The platform also offered in-app coins that could be exchanged for special awards, a leaderboard where students could compete for top positions in different divisions, earning weekly rewards and advancing up the ladder, and streaks to motivate students to maintain consistent learning habits. 

These enhancements were anticipated to positively impact the student experience, create an effective strategy for customer engagement, and contribute to the company's success in the coming year. With this Customer Engagement Analysis in Excel project, as a data analyst I must analyze whether the new additions to the platform have increased student engagement.

## Raw Data And Details:
Columns names with corresponding details:
1. student_id – the unique identifier for each student in the dataset. The field contains IDs for students who used the 365 Data Science platform with free or paid accounts in Q4 2021 (October 1, 2021 – December 31, 2021, both included) and Q4 2022 (October 1, 2022 – December 31, 2022, both included).

2. student_country – identifies the country of each student. The field provides information about students’ geographic location and can help analyze regional differences or conduct country-specific analyses.

3. Paid – indicates whether a student had a paid account during the specified period. It is a binary variable, where '1' represents a paid account and '0' represents a free or unpaid account. It helps differentiate between students who have access to additional features or content through a paid subscription.

4. minutes_watched_21 – represents the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2021.

5. minutes_watched_22 – denotes the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2022.

## Parts And Tasks 
The Excel file 'Engagement Project.xlsx' consists of four worksheets: Task 1 and 2, Task 3, Task 4, and Task 5. Each sheet contains specific information regarding the project's tasks and corresponding data. 

Whole case study project is devided into three major parts:

### Part 1. Descriptive Statistics (Task 1 and 2)
Task 1: 
After checking the data and doing needed calculations using Excel functions/formulas interpretaion of results are as follows: 
**Paid-Plan Students**

![Screenshot 2025-01-06 210255](https://github.com/user-attachments/assets/1fd7c5d3-f740-4eb2-9d81-649449802a1e)

**Mean**: Among students who watched between 1 and 100 minutes in 2021, the average minutes watched by paid-plan students increased significantly from Q4 2021 to Q4 2022, from approximately 33.80 minutes to about 273.02 minutes. This suggests a substantial increase in engagement among this group of initially low-engagement-paid-plan students.

**Median**: The median minutes these low-engagement-paid-plan students watched increased from Q4 2021 to Q4 2022, from 26.33 minutes to 40.28 minutes. While this increase is not as dramatic as the increase in the mean, it indicates that the typical student in this group (i.e., the student in the middle of the distribution) also increased their engagement. This suggests that the increase in engagement was more widespread among paid-plan students and not solely driven by a few outliers.

**Standard Deviation**: The standard deviation for these low-engagement-paid-plan students increased substantially from 28.21 minutes in Q4 2021 to 854.58 minutes in Q4 2022. This indicates a much larger variability in the minutes watched by these students in Q4 2022 compared to Q4 2021. This could be due to a broader range of engagement levels among the students in Q4 2022, with some students watching very little content and others watching a lot of content.

These results suggest that paid-plan students who were initially **low-engagement in 2021** significantly **increased their engagement in 2022**. But the increased standard deviation indicates a broader range of engagement levels among these students in 2022. Understanding the reasons behind this variability could provide valuable insights for further boosting engagement. For instance, the factors that motivated the students who significantly increased their engagement **might be leveraged to encourage increased engagement among other students**.

**Free-Plan Students**

![Screenshot 2025-01-06 210321](https://github.com/user-attachments/assets/0264fc3e-92bf-403d-9e73-66ab3fceb2eb)

**Mean**: Among students who watched between 1 and 100 minutes in 2021, the average minutes watched by free-plan students increased from about 25.39 minutes in Q4 2021 to about 117.64 minutes in Q4 2022. This suggests that overall engagement among these initially low-engagement-free-plan students increased during this period. But the extent of this increase is less than what was observed for similar low-engagement-paid-plan students, suggesting that while these free-plan students are watching more content, they're still not as engaged as the equivalent group of paid-plan students.

**Median**: Interestingly, the median minutes watched by these low-engagement-free-plan students decreased from Q4 2021 to Q4 2022, from 14.17 minutes to 11.83 minutes. This indicates that engagement decreased for the typical student in this group (i.e., the student in the middle of the distribution). The increase in the mean might be driven by a small number of free-plan students who significantly increased their engagement in Q4 2022, while the majority did not increase their engagement or even reduced it.

**Standard Deviation**: The standard deviation for the low-engagement-free-plan students increased from 26.23 minutes in Q4 2021 to 468.93 minutes in Q4 2022. This indicates a more significant variability in the minutes watched by these students in Q4 2022 compared to Q4 2021. The behavior of these students then became more diverse in Q4 2022, with some watching a lot of content and others watching very little.

### 3. Confidence Interval
Task 3

### 5. Hypothesis Testing
Task 4 and Task 5


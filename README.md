# Students_365datascience.com
**Customer Engagement Analysis in Excel Project**
## Case Description
In 2022, there were high expectations for the growth of the 365 company and increased student engagement based on the introduction of new website platform features. Some of these features included,
1. An XP system that enabled students to track their progress, level up, and earn rewards by completing various learning objectives. 

2. The platform also offered in-app coins that could be exchanged for special awards, a leaderboard where students could compete for top positions in different divisions, earning weekly rewards and advancing up the ladder, and streaks to motivate students to maintain consistent learning habits. 

These enhancements were anticipated to positively impact the student experience, create an effective strategy for customer engagement, and contribute to the company's success in the coming year. With this Customer Engagement Analysis in Excel project, as a data analyst I must analyze whether the new additions to the platform have increased student engagement.

## Raw Data And Details:
**Note**: Raw file is by name 'Engagement Project_Raw.xlsx' is attached above with this project. 

Columns names with corresponding details:
1. student_id – the unique identifier for each student in the dataset. The field contains IDs for students who used the 365 Data Science platform with free or paid accounts in Q4 2021 (October 1, 2021 – December 31, 2021, both included) and Q4 2022 (October 1, 2022 – December 31, 2022, both included).

2. student_country – identifies the country of each student. The field provides information about students’ geographic location and can help analyze regional differences or conduct country-specific analyses.

3. Paid – indicates whether a student had a paid account during the specified period. It is a binary variable, where '1' represents a paid account and '0' represents a free or unpaid account. It helps differentiate between students who have access to additional features or content through a paid subscription.

4. minutes_watched_21 – represents the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2021.

5. minutes_watched_22 – denotes the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2022.

## Parts And Tasks 
The Excel file 'Engagement Project_Raw.xlsx' consists of four worksheets: **Task 1 and 2**, **Task 3**, **Task 4**, and **Task 5**. Each sheet contains specific information regarding the project's tasks and corresponding data. 

Whole case study project is devided into three major parts:

### Part 1. Descriptive Statistics (Task 1 and 2)
**Task 1**: After checking the data and doing needed calculations using Excel functions/formulas interpretaion of results are as follows: 
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

These results suggest a complex picture for the **initially low-engagement-free-plan students**. While the mean minutes watched increased—signifying an increase in overall engagement—the **median minutes watched decreased**, indicating that the typical student in this group did not increase their engagement. This discrepancy and the increased standard deviation suggest that a small number of students within this group m**ight significantly increase their engagement while the majority did not**. This might imply the need for targeted strategies **to boost engagement among the broader population** of initially low-engagement-free-plan students.

**Paid vs Free-Plan Students**

On average, low-engagement-paid students initially **increased their watching time** more significantly than the free-plan students from Q4 2021 to Q4 2022. This could suggest that **paid-plan students find more value in the platform**, possibly due to premium features or content that are available to them. In contrast, the median watch time decreased for free-plan students, suggesting that the **typical free-plan student in this group did not increase their engagement**. This discrepancy might indicate that the strategies or features designed to increase engagement are **more effective for paid-plan students**. It could also suggest that the **monetary investment leads to increased usage** due to a desire to get their money's worth.

Based on the findings, the platform is **more successful in increasing engagement among students who make a monetary investment** (i.e., paid-plan students). But the increased variability, especially among paid-plan students, indicates that there are likely differences in how individual students are responding to the platform's offerings. Therefore, **personalized approaches might be beneficial in boosting engagement**, and further analysis could help understand the factors that **drive increased engagement among paid- and free-plan students**.

**Task 2** You can find the solution to this problem in the Descriptive Statistics – tasks 1-2.xlsx file: After checking the data and doing needed calculations using Excel functions/formulas interpretaion of results are as follows: 

**Skewness** is a fundamental measure of probability distribution asymmetry in a dataset. It reveals whether the observations are concentrated more on one side of the distribution. This metric helps us understand how the data deviates from a normal distribution and provides insights into its underlying structure. A positive skewness value (higher than 0) indicates a right-skewed distribution, while a negative skewness value (lower than 0) points to a left-skewed distribution. A symmetrical distribution has a skewness value of 0, indicating a balanced data spread around the mean.

For **paid-plan students**, the skewness increased from 0.63 in Q4 2021 to 7.07 in Q4 2022.

![Screenshot 2025-01-06 212331](https://github.com/user-attachments/assets/54840fd0-dc06-4b0e-a026-2ab46a663264)

The skewness for **free-plan students** increased from 1.17 in Q4 2021 to 15.06 in Q4 2022, indicating positive skewness.

![Screenshot 2025-01-06 212347](https://github.com/user-attachments/assets/bc43fda8-53ed-456b-92d1-b67cf7efd883)

**Positive skew (right-skew)** occurs when the data is not symmetrical around the mean, forming a long tail on its right side. This signifies that most of the distribution's observations are concentrated to the left of the peak. Positive skewness can have several implications.

The mean is larger than the median in a right-skewed distribution because the distribution tail pulls the mean to the right. This observation is confirmed by the mean and median values in the two years. An increasing skewness suggests that more students watch significantly more content than most over time, pulling the mean upwards.

**In both cases, the mean is higher than the median (33.80 > 26.33 in 2021 and 273.02 > 40.28 in 2022).**

As a result, the mean is no longer a good central tendency indicator, and it cannot accurately reflect the typical value of the dataset. Note that skewness tells us the direction of outliers but doesn’t indicate the number that occurs.

**Kurtosis** measures the degree of tailedness—the weight of the tails relative to the rest of the distribution. In other words, it shows how much of the data is in the tails compared to the center. Located farthest from the center, the tails represent the regions where data points are more dispersed—suggesting the presence of more extreme values. If a distribution is heavy-tailed—i.e., more data in the tails—it exhibits high kurtosis. Meanwhile, a low kurtosis occurs when the data is more evenly distributed between the tails and the center or the distribution is light-tailed.

For **paid-plan students**, the kurtosis increased from -0.85 in Q4 2021 to 58.48 in Q4 2022.

![Screenshot 2025-01-06 213103](https://github.com/user-attachments/assets/c00b3403-0ec4-4e0a-8282-e3ccf22ccf2f)

The kurtosis increased for free-plan students also—from 0.36 in Q4 2021 to 315.76 in Q4 2022. 

![Screenshot 2025-01-06 213113](https://github.com/user-attachments/assets/f1556067-607f-44e2-983f-d245d0cb7754)

The increase in kurtosis over time suggests **more extreme cases in the data in Q4 2022 than in Q4 2021, particularly for free-plan students**. Overall, the increasing skewness and kurtosis for both groups from Q4 2021 to Q4 2022 suggest a **growing number of students watching significantly more content than the majority**. This is especially true for **free-plan students** with a higher skewness and kurtosis in Q4 2022 than **paid-plan students**.

### 2. Confidence Interval
**Task 3**
Comparing the four groups, I observed the following:

**Paid-Plan Students**:

![Screenshot 2025-01-07 130555](https://github.com/user-attachments/assets/7f49d408-bf84-4790-b1f2-222a82f2488a)  ![Screenshot 2025-01-07 130618](https://github.com/user-attachments/assets/fc9f3f4f-dddd-4a82-a8ed-9a4adb5a4c41)

For paid-plan students, there's an increase in engagement from Q4 2021 to Q4 2022. The confidence interval for the average minutes watched by paid-plan students increased from Q4 2021 (316.25 to 348.76 minutes) to Q4 2022 (351.91 to 384.72 minutes). This suggests that we can be 95% confident that the true average minutes watched by all paid-plan students in the population increased from Q4 2021 to Q4 2022.

**Free-Plan Students**:

![Screenshot 2025-01-07 130918](https://github.com/user-attachments/assets/30bc9d97-6b45-4c57-b396-a54d6c1fc8e5)  ![Screenshot 2025-01-07 130942](https://github.com/user-attachments/assets/1f8da3e2-0f9a-4c0d-97e6-2526f024077d)

Among free-plan students, there's a decrease in engagement from Q4 2021 to Q4 2022. The confidence interval for the average minutes watched decreased from Q4 2021 (129.92 to 137.95 minutes) to Q4 2022 (67.71 to 70.59 minutes). We then can be 95% confident that the true average minutes watched by all free-plan students in the population decreased from Q4 2021 to Q4 2022.

**Comparison between Paid- and Free-Plan Students (Q4 2022)**

Students with a paid-plan subscription watch substantially more than those without. The confidence interval for the average minutes watched in Q4 2022 was 61.71 to 70.59 minutes for free-plan students and 351.99 to 384.72 minutes for paid-plan students. **We then can be 95% confident that paid-plan students watched significantly more minutes than free-plan students in Q4 2022**. This aligns with the expectation that paid-plan students who have invested in the platform tend to be more engaged than free-plan users. 

Please note that these are just interpretations based on the confidence intervals. Actual cause-effect relationships must be examined further to understand the causes behind these engagement changes.

The fact that paid-plan subscribers watch more doesn't necessarily mean **that having a paid-plan subscription encourages them to watch more**. For example, the higher engagement among paid-plan students may be **due to the additional features or content available or because more engaged students are more likely to choose a paid-plan subscription**.

Similarly, the decrease in engagement among free-plan students could be **due to various factors, such as changes in the platform, competition from other platforms, or changes in the user base**.

**Part 3: Hypothesis Testing**
**Task 4**
Test for Variances
First, I must perform a **two-sample f-test for variances** to prove that assumption of unequal variances between the samples for free-plan and paid-plan subscribers:

![Screenshot 2025-01-07 140032](https://github.com/user-attachments/assets/430f5c6b-ced6-4d16-8b0c-f52829b5569e)









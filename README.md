# SAT & ACT Analysis Project

by: Ata Akca

![success photo](./images/kids_taking_test.jpg)

(picture from: https://news.schoolsdo.org/)


### Problem statement

---

With SAT going for a record of 2 million participations, the College Board wants to keep moving forward with the trend. So the Data Science Team is requested to investigate on the data to find out which states they should invest on. The goal is to find a pain point for a state and suggest a solution to raise the participation rates for the SAT among students.

### Executive Summary

---

This project consisted of cleaning and merging of 2017 and 2018 SAT and ACT scores as well as participation rates. The data was properly imported for any external users to inspect.

The merged data set was used to explore and visualize the important points related to popularity and success of the two separate tests in every state.

An outside research was made to support the evidence found while exploring data, and recommendations were made for the College Board to increase the participation rates of certain states.

**Description of data:** SAT and ACT data sets for 2017 and 2018

***Size:*** Data from 50 states and DC

**Sources:**
- [2017 ACT Scores](./data/act_2017.csv)
- [2017 SAT Scores](./data/sat_2017.csv)
- [2018 ACT Scores](./data/act_2018.csv)
- [2018 SAT Scores](./data/sat_2018.csv)

### Conclusions and Recommendations

---

Three different states were put under scope:

***Ohio:*** Ohio requires their students to take at least one of the 2 exams. Although they had low participation rate in the SAT (12%) and higher participation rate in ACT (75%), this state showed an impressive improvement in a year, increasing their participation rates as well as the total average score for both of the exams. Ohio also appears to receive a positive feedback from many parties including a high school principal on how taking SAT gets their students college-ready.

***West Virginia:*** College Board seems to have taken action on this state already. By partnering up with Khan Academy, College Board took matters to their own hands on their rally to make SAT a more popular choice in West Virginia.

***Utah:*** Due to their minimal participation rates in SAT, Utah seems like a prospect state to improve. Also with the success rate increasing, one might assume that the state could do better in SAT. But, due to their wrong choice in technology provider, they are experiencing technical difficulties in order to get their students to attend or receive test results.

Popilation-wise, Ohio seems like the most ideal choice out of the three states. There are tenfold students eligible for participation in SAT when compared to West Virginia or Utah. Therefore Ohio state would be the better choice for a bigger scaled approach.

To increase the number of people taking tests can rely on several different criteria:

- Reliability
- Difficulty
- Success stories
- Chance of retaking
- Number of Resources
- Self-paid or financed by the state
- Researching parents impressions on the tests

### Contents

---

- [2017 Data Import & Cleaning](./code/Project_Analysis.ipynb/#Data-Import-and-Cleaning)
- [2018 Data Import and Cleaning](./code/Project_Analysis.ipynb/#2018-Data-Import-and-Cleaning)
- [Exploratory Data Analysis](./code/Project_Analysis.ipynb/#Exploratory-Data-Analysis)
- [Data Visualization](./code/Project_Analysis.ipynb/#Visualize-the-data)
- [Descriptive and Inferential Statistics](./code/Project_Analysis.ipynb/#Descriptive-and-Inferential-Statistics)
- [Outside Research](./code/Project_Analysis.ipynb/#Outside-Research)
- [Conclusions and Recommendations](./code/Project_Analysis.ipynb/#Conclusions-and-Recommendations)

### Data Dictionary

---

|Column Name|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|The 50 States that the results belong to|
|sat_17_participation|float|SAT|Participation rate of eligible population for SAT '17|
|sat_17_ebraw|float|SAT|Reading and Writing results for SAT '17|
|sat_17_math|float|SAT|Math results for SAT '17|
|sat_17_total|float|SAT|Total score for SAT '17|
|act_17_participation|float|ACT|Participation rate of eligible population for ACT '17|
|act_17_english|float|ACT|English results for ACT '17|
|act_17_math|float|ACT|Math results for ACT '17|
|act_17_reading|float|ACT|Reading results for ACT '17|
|act_17_science|float|ACT|Science results for ACT '17|
|act_17_composite|float|ACT|Composite score for ACT '17|
|sat_18_participation|float|SAT|Participation rate of eligible population for ACT '18|
|sat_18_ebraw|float|SAT|Reading and Writing results for SAT '18|
|sat_18_math|float|SAT|Math results for SAT '18|
|sat_18_total|float|SAT|Total score for SAT '18|
|act_18_participation|float|ACT|Participation rate of eligible population for ACT '18|
|act_18_composite|float|ACT|Composite score for ACT '18|

### References

---

- https://www.daytondailynews.com/news/too-much-testing-some-schools-angry-with-ohio-act-sat-mandate/5lPdirdJ68IuXs1ez7Mv7L/

- https://www.cleveland.com/metro/2017/04/free_sat_or_act_exams_give_all.html

- https://www.usatoday.com/story/news/nation/2019/04/23/17-students-ohio-high-school-perfect-act-score/3552583002/

- http://education.ohio.gov/Topics/Testing/ACT-SAT-FAQs#FAQ2839

- https://reports.collegeboard.org/pdf/2017-ohio-sat-suite-assessments-annual-report.pdf

- https://www.wvgazettemail.com/news/education/wv-chooses-sat-as-new-high-school-standardized-test-for/article_b60d2618-4943-56f6-b180-4b4442172ef8.html

- https://reports.collegeboard.org/pdf/2017-west-virginia-sat-suite-assessments-annual-report.pdf

- https://www.sltrib.com/news/education/2019/09/18/standardized-tests-utah/

- https://reports.collegeboard.org/pdf/2017-utah-sat-suite-assessments-annual-report.pdf
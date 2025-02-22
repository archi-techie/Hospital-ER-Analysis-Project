# Hospital-ER-Analysis-Project
This project is a Descriptive Analytics of a Hospital ER data containing patients’ demographics, wait time, department referrals, other patient care, as well as satisfaction score. It tells the data story by identifying trends, and correlating factors to answer questions and present insights through clear visualizations and summaries.


[You can find the project here](https://oaorogun.co.uk/20-project-challenge-with-dr-okunola-project-3/?mcp_token=eyJwaWQiOjIyOTg4MzYsInNpZCI6MTM5NjE1OTYzNywiYXgiOiJhNzFlOTczNmM4OTQzZDI1Yzk4ZGZlN2UwODIxYThkNiIsInRzIjoxNzM4MDE5MTAzLCJleHAiOjE3NDA0MzgzMDN9.2aaC8L8judkSPUS9ck2OkHvjp96piqzN53Cd7OlQHF4) 

**What’s in the Dataset?**


• Patient Demographics: Including gender, age, and race.

• ER Operations: Wait times, admission flags, and department referrals.

• Satisfaction Metrics: Ratings from patients reflecting their experience.

This dataset is rich with possibilities for exploratory analysis, hypothesis testing, and visualization.

**Questions asked include** 

1.	How do wait times vary by department and age group?
2.	Are patients with higher wait times less likely to report satisfaction?
3.	Which demographic is most frequently referred to specific departments?

**Additional Question** 

4.	 What are the busiest periods in the ER?

[Download the Dataset by Dr. Orogun](https://drive.google.com/file/d/1KCGLkSUube1aADjbI4UVpmMNg8-K7SjZ/view) or [Click here](https://github.com/archi-techie/Hospital-ER-Project/blob/main/Hospital%20ER_Data%202.csv).

- I used Python for my analysis

**What I did** 

I discovered a lot of missing entries in the Satisfaction score column and I filled them with previous entries. The reasson for that is patients will most likely have the same experience during same day/period.
I did EDA, discovered trends and insights. I also did some Feature engineering to group patient ages into 5; Infant, Child, Teenager, Young Adult, Adult and Senior, as well as to extract hour, dayname, month, and year from the date. With these, I was able to answer the questions and tell the data story:


**Data Findings and Storytelling**


The ER data records 9216 cases of patients from 1st January 2023 to 30th October 2024, most of whom are adults, Whites and African Americans. There are slightly more male than female (51 and 49 percent respectfully) with age range 1-79. The demography also includes Asians (12%), Pacific Islanders (6%), Native Americans/Alaska Native (5%), patients of two or more races (17%), as well as those who have declined to identify (11%).  

Patients that come into the ER typically spend 35 minutes from when they check in or are triaged until they receive an initial medical evaluation or treatment. However, they can spend up to an hour waiting. Depending on the patient's age group and the department to which they are referred, there may be a variation of plus or minus 2 minutes, contingent upon referral. Though, 3 of 5 patients are discharged right from the ER because they have no need to be referred to a specialty, and 1 requires critical health management after the ER visit, all 5 have equal chances of being admitted (or not). 

African American children within 3 and 12 years mostly treat gastroenterology related illnesses, and White Adults and young adults within ages 36-55 and 20-35 is mostly referred to Renal and Neurology department respectively. While a lot of  elderly White men and women more than 55 years are discharged directly from the ER, most frequently treat cardiology, orthopedics, physiotherapy, neurology, and general practice related illnesses. 

The ER is least visited during the winter period, and is at its peak just before the end of summer in August. Therefore, winter period is the best time for ER staff developmental programs.

At the end of a visit to the ER, patients’ satisfaction of the experience is almost never affected by the wait time **only**. Further analysis (Feature Selection Process) can be carried out to determine other factors that influence patients’ satisfaction score. However, it is crucial to reduce patients wait time to the barest minimum by keeping track of the busiest periods and matching up with adequate staff to properly care for patients. Finally, hospital policies on doctor to patient ratio and employment of ER staff may be reviewed to reduce work load and  less burnout which improves patients care and experience in the ER and ultimately patients satisfaction score. 







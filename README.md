# LITA_HR_DATA
---
## **PROJECT TITLE: HUMAN RESOURCE(HR)_DATA**
---
## PROJECT OVERVIEW
This project covers a Human Resource (HR) Data of a company that has been in existence for Forty (40) years. This data has both quantitative and qualitative variables, and insights are drawn from this data to know the trends of Attrition and Current employees in the company. The insights drawn will also proffer accurate decision making to know how to curb the rate of attrition in the company.

---
##  DATA SOURCE
-  This dataset is an HR Data which i gained access through The Incubator Hub 
---
## KEY VARIABLES
This segment explains the variables that are included in the analysis. 

**QUALTITATIVE DATA**
- **Employeee:** This represents the people working in a place of business. Employees can be further divided into 2;
- **Attrition:** This represents employees who are no longer working in a place of business.
- **Current Employees:** This represents employees who are currently working in a place of business.
- **Gender:** This represents the sex of employees.
- **Department:** In this dataset, there are Three (3) departments in the company which are; Research and Development (R&D), Sales and Human Resources(HR).
- **Job Role:** This shows the various duties assigned to the employees im the company.
- **Educational Field:** This represents employee's educational background.
- **Job Satisfaction Ratings**: This shows the feeling of satisfaction employees feel towards their job.

**QUANTITATIVE DATA**
- **Age Group**: this shows the frequency distribution of employee's age. The age was distributed into Five (5); Under 25, 25-34, 35-44. 45-54 and Over 55.
- **Employee Count:** This shows the total number of employees in the company both current and attrition.
- **Attrition Count**: This shows the total number of attrition in the company.
- **Current Employee** count: This shows the total number of current employee in the company.
- **Attrition rate:** This shows the percentage of attrition in the company.
- **Average Age:** This shows the age of employees on an average.
- **Total Working Years**: This represents the total number of years each employee has worked for in the company.
---
## TOOLS USED
The tool used in this analysis is;

-  Microsoft Power BI [Download here](https://www.microsoft.com/en-us/download)
----
## DATA ANALYSIS EXPRESSIONS (DAX) FUNCTIONS
With the tool used for this analysis some Data analysis expression (DAX) were carried out. The following DAX functions were carried out;
- **Attrition Count:** In order to get the total number of attrition in the company, a Conditional Column was created where "1" was assigned to employees whose attrition are "yes" and "0" was awarded to employees whose attribution are "No".
- **Attrition Rate:** This was calculated by dividing the sum of attrition count by the total sum of employee all multiplied by 100.
- **Average Age:** This was calculated by using the Average function in Power BI's quick measure.
- **Current Employee Rate:** This was calculated by dividing the sum of current employee by the total sum of employee all multiplied by 100.
---
## DATA VISUALIZATION FOR ATTRITION
To explain the pattern of Attrition in the company, i created a dashboard that visualizes attrition trends in the company.

![LITA Week2 28-Oct-24 7_41_17 PM](https://github.com/user-attachments/assets/0f54806f-ece0-4983-a52b-85f0095cee6c)

### Insights Drawn
The dashboard above shows the visual representation of attrition trends in the company. Some insights drawn from it are;

1.  The total attrition count is 237 with the total employees being 1470.
2.    The age group 25-34 have the highest count of attrition with a total of 112, which explains that the young employees left the company, this may be because of better job offers or the "Japa Syndrome".
3.  Most of the attrition employees are Single with a count of 120, with the Male population having the highest attrition count with a total of 150 (63%).
4.  The Research and Development (R&D) department have the highest rate of attrition with 53%, this department is dominated by employees who have educational background in Life Sciences and the Medical field. There are reports of Jobs abroad who want people in the medical line, this also explains the reason why employees left the company for greener pastures abroad since most of the attrition employees are in the said line.
5.  When the employees were asked to rate their satisfaction with their job, out of the attrition employees 66 admitted to be very dissatisfied with their job. Although 73 admitted to being just satisfied with their job which is the highest.

### Dashboard for applied slicer
I applied a slicer that shows the total working years of employees, because i wanted to see how long the attrition employees worked before they left the company. The Rate of attrition employees who worked for 1 year is higher than the other years, so i decided to go talk on that.

![LITA Week2 28-Oct-24 7_47_33 PM](https://github.com/user-attachments/assets/811cb7ef-1b40-4dd9-a2d8-4f9075bee8d3)

#### Insights
The slicer explained that most of the attrition employees left the company just after 1 year of working and they are within age group 25-34. This points to the fact that the young population are most likely going to leave the countey and People who plan to leave the country tend to look for where to work while they process their travelling documents. Seeing these insights just makes me come to the conclusion that most of the attrition employees had to leave the country (japa Syndrome).

---
###  CONCLUSIONS
After carrying out the analysis on the attrition employees, i noted some recommendations that will help the company moving forward.
-  In as much as most citizens are looking for a way to leave this country and you never really know if a newly employed employee have thoughts of leaving the country. You can't stop them from wanting to leave, you can only make your company better and indispensable.
-  Apart from employees leaving the country, another factor that will count for attrition is the Salary. Is the pay enticing enough that even your competition  do not give their employees up to that because if your employees see a better offer that will pay them more alongside other incentives, they will leave.
-  Lastly, from the Job satisfaction ratings asked by the company to the employees, you will see that a 73 attrition employees were satisfied with the job but they still left the job. This points to the faqct that those employees loved their job but saw better opportunities. Those who admiited to be very dissatisfied with the job were 66 and that is why they left they hated their job.
---
## DATA VISUALIZATION FOR CURRENT EMPLOYEES
To explain the actual employees in the company, i created a dashboard that visualizes current employees trends in the company.

![LITA Week2 28-Oct-24 7_49_01 PM](https://github.com/user-attachments/assets/4561eb79-91bf-4f87-8137-7b3e29a472f5)

###  Insights Drawn
After analysing the part of the current employees as shown in the dashboard above, here are some insights i drew from it;
1.  The total number of Current employee is 1233 with a rate of 84%.
2.  The Male gender have the highest count with 732 and the Female gender with 201.
3.  48% of the current employees are married while 28% and 24% of the current employees are Single and Divorced respectively.
4.  Age Group 35-44 have the highest count of current employees with 454. The Over 55 age group have the lowest count with 58.
5.  The Research and Development department have the highest count of current employees with a total of 828 and a rate of 67%. Human Resource department have the  lowest with a total of 51 and a rate of 4%.
6.  The Sales Executive job role have the highest number of current employees with a total of 269.
7.  When the current employees were asked to rate their satisfaction with their job, 407 employees admitted to being satisfied with their job which is the highest. Those who admitted to be vey dissatisfied are 223 which is the lowest in the rating rankings.

###  Dashboard for applied slicer
I applied a slicer to show the Educational field of employees. I wanted to see the most dominant educational field in the company. The Life science field had the most number of current employees so i decided to draw insights from it.

![LITA Week2 28-Oct-24 7_49_24 PM](https://github.com/user-attachments/assets/d1810cab-46ae-4b75-8b8e-605d577d177a)

####  Insights
 The applied slicer shows that most of the current employees had an educational background in Life sciences. This explains why the R&D departement have the highest count of workers. Also, from the dashboard above it shows that the employees who have an educational background in Life Sciences are present in all the job roles but Research scientist comes at the top. Lastly, Most of them admitted to being very satisfied and satisfied with their job.

 ---
 ##  CONCLUSIONS
 After carrying out my analysis on the current employees, i noted a few reccommendations to help the company retain their employees.
 1.  Find out why out of the current employees some workers admitted to being very dissatisfied and dissatisfied with thier job, by doing this you get to hear their views and opinions on the company. From their views solutions can be drawn out.
 2.  The company should always maintain a good working environment that is conducive for employees and their mental health, this way employees will be comfortable in the workspace and will always look forward to coming to work.
 3.  Lastly, the company should always strive to be better and indispensable so that other your employees won't have eyes for other competitors.

---
## GENERAL CONCLUSIONS ON ATTRITION AND CURRENT EMPLOYEES
In conclusion, in as much as the rate of attrition is low compared to that of current employee that does not mean more employees will still not leave. The company can do well to hire more hands to cover up for attrition so when in time more employees leave the company, it does not affect the company in extreme.(except most of the attrition employees were sacked). Its more like they leave you replace.

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
## Data Visualization For Attrition
To explain the pattern of Attrition in the company, i created a dashboard that visualizes attrition trends in the company.

![LITA Week2 28-Oct-24 7_41_17 PM](https://github.com/user-attachments/assets/0f54806f-ece0-4983-a52b-85f0095cee6c)

### Insights
The dashboard above shows the visual representation of attrition trends in the company. Some insights drawn from it are;

The total attrition count is 237 with the total employees being 1470.
1.  The age group 25-34 have the highest count of attrition with a total of 112, which explains that the young employees left the company, this may be because of better job offers or the "Japa Syndrome".
2.  Most of the attrition employees are Single with a count of 120, with the Male population having the highest attrition count with a total of 150 (63%).
3.  The Research and Development (R&D) department have the highest rate of attrition with 53%, this department is dominated by employees who have educational background in Life Sciences and the Medical field. There are reports of Jobs abroad who want people in the medical line, this also explains the reason why employees left the company for greener pastures abroad since most of the attrition employees are in the said line.
---
### Dashboard for applied slicer

![LITA Week2 28-Oct-24 7_47_33 PM](https://github.com/user-attachments/assets/811cb7ef-1b40-4dd9-a2d8-4f9075bee8d3)

#### Insights
To know how long the attrition employees worked before leaving the company, i applied a slicer. The slicer explained that most of the attrition employees left the company just after 1 year of working. People who plan to leave the country tend to look for where to work while they process their travelling documents. Seeing these insights just makes me come to the conclusion that most of the attrition employees had to leave the country (japa Syndrome).

---
## DATA VISUALIZATION FOR CURRENT EMPLOYEES
To explain the actual employees in the company, i created a dashboard that visualizes current employees trends in the company.

![LITA Week2 28-Oct-24 7_49_01 PM](https://github.com/user-attachments/assets/4561eb79-91bf-4f87-8137-7b3e29a472f5)

####  Insights

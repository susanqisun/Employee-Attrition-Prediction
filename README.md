# Employee-Attrition-Prediction
Develop a predictive model for employee attrition. 

The data used for this project was collected from the personnel records of employees in IBM. This dataset is comprised of 1470 observations with 22 variables.

Introduction:

The purpose of this project is to develop a predictive model for employee attrition. The data used for this project was collected from the personnel records of employees in IBM. This dataset is comprised of 1470 observations with 22 variables.

Research Questions:

The following research questions will guide this study:

1.	What are the relationships between attrition and other variables?
2.	What is the best model to predict employees’ attrition?
3.	Which features are most contributed to the response variable?

Domain Knowledge:

Attrition is one of the important issues in an organization. Stovel, M. and Bontis, N. (2002) draw attention on controlling attrition, they state that the value of employees to an organization is a very crucial element in the success of the organization. When employees leave an organization, they carry with them invaluable knowledge which is often the source of competitive advantage for the business. Attrition is defined as the normal and uncontrollable reduction of a work force because of retirement, death, sickness, and relocation. The employee attrition is often unpredictable and can leave gaps in an organization. If organizations know why their employees leave, they can develop effective strategies for employee retention. The purposes of this study are to find out why employees left the organization and to develop a model that can predict how likely the employee quit the job.
There are many reasons why employee leave the organization.
Based on the research of Firth et al (2007), intention to quit is largely influenced by job dissatisfaction, lack of commitment to the organization and feelings of stress. The work overload and job ambiguity which are the factors that trigger the chain of psychological states that lead to intention to quit. Reducing attrition can save organizations the considerable financial cost and effort involved in the recruitment, induction and training of replacement staff.
Griffeth et al. (2000) conclude that the predictors of employee turnover include job satisfaction, organizational commitment, job search, comparison of alternatives, withdrawal cognitions, and quit intentions. Also, job performance can foreshadow turnover. The pay and pay-related variables have a significant effect on employee turnover. The results of the gender-turnover correlation indicates that women turnover rate is similar to that of men. The gender age-turnover relationship demonstrates that women are more likely to remain as they age than are men.
Louis (1980) states that attrition takes place because new employees compare their actual experience with their past work experiences. Past work experience plays a significant role in taking decisions to quit in case the new worker’s expectations are not met.
All the researches mentioned above have been completed over ten years ago. In this study, we’ll examine the factors that can result in employee attrition in IBM. We’ll also develop a model to predict the employee attrition. The outcome of this research can be utilized for redesigning the HR policies and practices and take corrective actions to reduce the attrition rate.


Independent variables:

1.	Age: the age of employees, all of them are over 18. - int, continuous
2.	BusinessTravel: how frequency of employees’ business travel. - object,categorical data
3.	DailyRate: the daily income each employee gets from company IBM. - positive integer, discrete
4.	DistanceFromHome: the distance between each employee’s address and company. - positive integer, continuous
5.	Education: the education level for each employee. 1 = 'Below College', 2 = 'College', 3 = 'Bachelor', 4 = 'Master', 5 = 'Doctor' - positive integer from 1 to 5, categorical data
6.	EmployeeNumber: the unique index or id of each employee. - positive integer, continuous
7.	EnvironmentSatisfaction: how does each employee feel for the company working environment. The range is from low to high, 1= 'Low', 2= 'Medium', 3= 'High', 4= 'Very High'. - positive integer from 1 to 4, ordinal data
8.	Gender: the sex of each employee. Female or male - object, categorical data
9.	JobInvolvement: a state of psychological identification with each employee’s work—or the degree to which a job is central to a person's identity. 1 = 'Low', 2= 'Medium', 3= 'High', 4= 'Very High', - positive integer from 1 to 4, ordinal data
10.	JobLevel: the level of job for each employee - positive integer, discrete
11.	JobRole: the job title for each employee - object, categorical
12.	JobSatisfaction: how does each employee feel about his or her job. It is from low to high. 1 = 'Low', 2= 'Medium', 3= 'High', 4= 'Very High', - positive integer from 1 to 4, ordinal data
13.	MaritalStatus: the marital status for each employee. Single or Married - Object, categorical data
14.	OverTime: if the employee works always over time. Yes or no - Object, binary data
15.	PerformanceRating: the rating of each employee’s performance. 1 ='Low', 2='Good', 3= 'Excellent', 4= 'Outstanding' - positive integer from 1 to 4, ordinal data
16.	RelationshipSatisfaction: how does each employee feel about his or her working relationship. 1 = 'Low', 2= 'Medium', 3= 'High', 4= 'Very High', - positive integer from 1 to 4, ordinal data
17.	TrainingTimesLastYear: the total training time for each employee from last year. - positive integer or zero, continuous
18.	WorkLifeBalance: how does each employee feel about the work life balance. 1='Bad', 2= 'Good', 3= 'Better', 4= 'Best' - positive integer from 1 to 4, ordinal data
19.	YearsAtCompany: the number of years that each employee stays at the company. - positive integer or zero, continuous
20.	YearsWithCurrManager: the number of years that each employee works with the current direct manager. - positive integer or zero, continuous.
21.	TotalWorkingYears: the number of total working years for each employee. - positive integer or zero, continuous

Dependent variable:

Attrition: Attrition is our response variable (binary) to indicate if an employee quit the job. The value includes Yes or No.
<img width="468" height="627" alt="image" src="https://github.com/susanqisun/Employee-Attrition-Prediction/blob/main/process.png" />


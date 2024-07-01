**Employee Performance Rating Prediction Project Overview :**

This project aims to build a machine learning model to predict employee performance ratings. The dataset includes various features related to employees' demographics, job roles, satisfaction levels, and other attributes. The goal is to achieve high train and test accuracy and identify the top features influencing performance ratings.

**Business Problem :**

Employee performance rating is a critical metric for organizations to assess their workforce's effectiveness. Predicting performance ratings can help management make informed decisions about promotions, salary hikes, and identifying areas for employee development.

**Dataset :**

The dataset consists of the following columns:

EmpNumber: Employee number

Age: Age of the employee

Gender: Gender of the employee

EducationBackground: Educational background of the employee

MaritalStatus: Marital status of the employee

EmpDepartment: Department of the employee

EmpJobRole: Job role of the employee

BusinessTravelFrequency: Frequency of business travel

DistanceFromHome: Distance from home to workplace

EmpEducationLevel: Education level of the employee

EmpEnvironmentSatisfaction: Satisfaction with the work environment

EmpHourlyRate: Hourly wage rate

EmpJobInvolvement: Level of job involvement

EmpJobLevel: Job level of the employee

EmpJobSatisfaction: Satisfaction with the job

NumCompaniesWorked: Number of companies the employee has worked for

OverTime: Overtime status

EmpLastSalaryHikePercent: Percentage of last salary hike

EmpRelationshipSatisfaction: Satisfaction with relationships at work

TotalWorkExperienceInYears: Total work experience in years

TrainingTimesLastYear: Number of training sessions attended last year

EmpWorkLifeBalance: Work-life balance rating

ExperienceYearsAtThisCompany: Years of experience at the current company

ExperienceYearsInCurrentRole: Years of experience in the current role

YearsSinceLastPromotion: Years since the last promotion

YearsWithCurrManager: Years spent with the current manager

Attrition: Employee attrition status

PerformanceRating: Performance rating (output column)

**Model :**

The model used for this project is the DecisionTreeClassifier. The dataset was split into training and testing sets, and the model was trained and evaluated to predict the performance rating.

**Results :**

Train Accuracy: 1.0

Test Accuracy: 0.879

**The top 5 features affecting the performance rating are:**

EmpEnvironmentSatisfaction

EmpLastSalaryHikePercent

YearsSinceLastPromotion

EmpDepartment

EmpNumber

**Conclusion :**

The model successfully predicts employee performance ratings with high accuracy. The identified top features provide valuable insights into the key factors influencing performance. This information can help organizations focus on these areas to improve overall employee performance and satisfaction.


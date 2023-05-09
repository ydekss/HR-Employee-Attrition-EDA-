# HR-Employee-Attrition-EDA-

![Employee Attrition: What It Is, Causes, Risks & Prevention](https://www.teamly.com/blog/wp-content/uploads/2022/06/Types-of-Employee-Attrition.png)

In this project I have taken the HR Attrition Dataset and tried to do an EDA (Exploratory Data Analysis) to and visualize them along with the Decision Tree Regressor.

## Exploratory Data Analysis and  Decision Tree Classifier on HR Attrition Dataset

The attrition dataset is a simulated dataset created by IBM data scientists for the purpose of demonstrating how data science techniques can be used to understand employee turnover in an organization.

**This project covers the EDA of the HR Attrition dataset through which i suggested the business by observing the insights i got from the analysis. After the EDA i have also fitted a Decision Tree Classifier which will predict weather the employee attrition will be "Yes" or "No".**

## HR Attrition Data

The data has following features and variables:

-   **Age**: The age of the employee
-   **Attrition**: Whether the employee has left the company or not
-   **BusinessTravel**: The frequency of business travel for the employee (rarely, frequently, or non-travel)
-   **DailyRate**: The daily rate of pay for the employee
-   **Department**: The department in which the employee works (e.g., sales, research and development)
-   **DistanceFromHome**: The distance of the employee's home from their workplace
-   **Education**: The level of education attained by the employee (1 = 'Below College', 2 = 'College', 3 = 'Bachelor', 4 = 'Master', 5 = 'Doctor')
-   **EducationField**: The field of education of the employee (e.g., life sciences, marketing, technical degree)
-   **EmployeeCount**: The number of employees in the company
-   **EmployeeNumber**: The unique identifier of the employee
-   **EnvironmentSatisfaction**: The employee's level of satisfaction with their work environment (1 = 'Low', 2 = 'Medium', 3 = 'High', 4 = 'Very High')
-   **Gender**: The gender of the employee
-   **HourlyRate**: The hourly rate of pay for the employee
-   **JobInvolvement**: The employee's level of involvement in their job (1 = 'Low', 2 = 'Medium', 3 = 'High', 4 = 'Very High')
-   **JobLevel**: The level of the employee's job in the company (1 = 'Entry Level', 2 = 'Intermediate', 3 = 'Senior', 4 = 'Executive', 5 = 'Officer')
-   **JobRole**: The role of the employee in the company (e.g., manager, sales representative, research scientist)
-   **JobSatisfaction**: The employee's level of satisfaction with their job (1 = 'Low', 2 = 'Medium', 3 = 'High', 4 = 'Very High')
-   **MaritalStatus**: The marital status of the employee (single, married, divorced)
-   **MonthlyIncome**: The monthly income of the employee
-   **MonthlyRate**: The monthly rate of pay for the employee
-   **NumCompaniesWorked**: The number of companies the employee has worked for prior to the current job
-   **Over18**: Whether the employee is over 18 years old or not
-   **OverTime**: Whether the employee works overtime or not
-   **PercentSalaryHike**: The percentage increase in salary that the employee received in their most recent salary hike
-   **PerformanceRating**: The employee's most recent performance rating (1 = 'Low', 2 = 'Good', 3 = 'Excellent', 4 = 'Outstanding')
-   **RelationshipSatisfaction**: The employee's level of satisfaction with their relationships at work (1 = 'Low', 2 = 'Medium', 3 = 'High', 4 = 'Very High')
-   **StandardHours**: The standard number of working hours per day for the company
-   **StockOptionLevel**: The employee's level of stock options (1 = 'Low', 2 = 'Medium', 3 = 'High', 4 = 'Very High')
-   **TotalWorkingYears**: The total number of years that the employee has worked
-   **TrainingTimesLastYear**: The number of times the employee received training in the past year
-   **WorkLifeBalance**: The employee's level of balance between work and personal life (1 = 'Bad', 2 = 'Good', 3 = 'Better', 4 = 'Best')
-   **YearsAtCompany**: The number of years at the company

## We will structure the code as follows

1.  Loading the data
    
2.  Preparing the data
    
3.  Exploratory Data Analysis
    
4.  Building the model and accuracy analysis
    
5.  Final Analysis of the model
    
## These are some of the insights

![Premium Vector | Feedback illustration.](https://img.freepik.com/premium-vector/feedback-illustration_126608-689.jpg?w=2000)

-   The majority of employees in the dataset are male (60.8%) and the average age of employees is 36 years.
-   The attrition rate in the dataset is approximately 16%, which suggests that turnover is a relatively common occurrence in the company.
    
-  Employees who travel frequently for business have a higher attrition rate than those who travel rarely or not at all.
    
 -  The mean monthly income for employees in the dataset is $6,502, with a standard deviation of $4,707.
 
-  Employees with higher levels of education tend to have lower attrition rates.
    
-  Employees in certain job roles, such as sales representatives and human resources, have higher attrition rates than those in other roles such as managers and research scientists.
    
-  Employees who are married have lower attrition rates than those who are single or divorced.
    
-   Employees who work overtime have a higher attrition rate than those who do not work overtime.
    
-  Employees who have worked for more companies in the past tend to have higher attrition rates, suggesting that job hopping is a predictor of turnover.
    
-  Employees who have been promoted more recently tend to have lower attrition rates, suggesting that career advancement opportunities can reduce turnover.
    
 -   The mean number of years that employees have worked at the company is 7.01, with a standard deviation of 6.13 years.
 - Employees who have a higher level of job satisfaction and a better work-life balance have lower attrition rates, highlighting the importance of employee well-being in reducing turnover.

## Decision Tree Classifier

![DECISION TREE. The decision tree falls under the… | by Nikita Malviya |  Analytics Vidhya | Medium](https://cdn-images-1.medium.com/fit/t/1600/480/1*7cyzrfuh9hKqz2lZxi_8ug.gif)

After fitting the  **Decision Tree Classifier** model on our data and comparing the results of the Training and the Testing data we were able to observe that our model predicted the Attrition with an accuracy of 84% for the training data and 86% for the testing data which can vary depending on the data and the fitting of the model.

To take a look at the models, feel free to look at the  `ipnyb`  file to explore more.

![Ways to Say Thank You in Greek](https://www.greekboston.com/wp-content/uploads/2018/08/Thank-You.jpg)


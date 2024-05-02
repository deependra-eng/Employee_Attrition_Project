# Employee_Attrition_Project

Project Overview: The Employee Attrition project aims to analyze factors contributing to employee turnover and develop strategies to reduce attrition rates.

Data Sources: Data was collected from the Kaggle. 

Libraries : Pandas, Numpy, SK-learn (ML Models : Logistic regression, SVC, Decision tree classifier, Random Forest classifier)

Data Preparation: Data cleaning to remove duplicates and missing value. But, the quantity of data of emp having Attrition is less compared to employees which do not have Attrition.

EDA Observations:
>> Employees working in R&D department are more, but employees from sales department or at position like sales executive,sale Representative leaves the job early.
>> Males are more under Attrition then Females
>> Age column is very well normalized, most of employees are age between 25 to 40.
>> Employees from Bachelor are more, then from Masters background. Attrition w.r.t to bachelor can be seem more because they have more and more expectation from companies and it will be interesting to see the reason behind this in this dataset.

Data Modeling: We have built different Predictive models like Logistic regression(Accuracy = 0.64), Support Vector Classifier(Accuracy = 0.59), Decision Tree Classifier(Accuracy = 0.89) and last Random Forest Classifier(Accuracy = 0.96).

Model Selection : We are going ahead with Random Forest Classifier model, which performed very well. 

Results and Impact: The project identified low job satisfaction and lack of career growth opportunities as key drivers of attrition. As a result, the company implemented employee engagement programs and career development initiatives, leading to a reduction in attrition rates.

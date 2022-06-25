# Employee Performance Analysis and Prediction
IABAC™ Project - 2020

**Project Summary:**
This Data science projects includes the analysis of the employee performance of INX Future Inc. INX Future Inc , (referred as INX ) , is one of the leading data analytics and automation solutions provider with over 15 years. Recent years, the employee performance indexes are not healthy and this is becoming a growing concerns among the top management. 
Goal of the project is to find the performance rating of the employees with various features available in the provided dataset.

The following insights that are expected to be analysed from this project:
1.	Department wise performances 
2.	Top 3 Important Factors effecting employee performance 
3.	A trained model which can predict the employee performance based on factors as inputs. This will be used to hire employees 
4.	Recommendations to improve the employee performance based on insights from analysis. 

**Insights from the given dataset:**
•	Dataset
-	A provided data is structured and has targets. It is a 1200x28 data with 1200 rows and 28 features.
-	The features are combination of quantitative and qualitative data.
-	16 features are numerical data and 11 features are categorical data
-	1 is alphanumerical data (Employee data) which can be neglected since it doesn’t have any effect on the performance of the employee.  
-	Target variable here is the Performance Rating, which is a categorical – ordinal data.
•	The algorithm and training method(s) used
-	The dataset is labelled and has target so supervised machine learning algorithm was selected to train the model. 
-	Since the target variable is categorical – ordinal data and is a multi class, classification algorithms was selected.
-	Following algorithms were modelled and the data was trained
1.	Random Forest Classifier
2.	K Nearest Neighbours
3.	Decision Tree
4.	Support Vector Machine
5.	XG Boost
6.	Naïve Bayes
7.	Artificial Neural Network
-	The supervised machine learning model Random Forest Classifier predicted with an accuracy of 92% and XG Boost with 93%. 

**Results, Recommendation and Conclusion:**
Performing various supervised machine learning algorithm the following insights were found. 

**Result 1: Department wise performances**
Visualization method was used to analyse the performance of employees with respective to the employees department. Seaborn and matplotlib are used to visualize date to get more insights on this category. The Employee department feature was taken and this was separated department wise. There are 6 departments available in the employee department variable.
•	Development
-	Number of employees working in this department is second highest (361 employee) when compared to others. 
-	Employees with technical back ground of life science and medical work here
-	Even though the count of Female employees are less when compared to male employees they perform well.
-	More employees contributes to 3 rating in performance. 
-	They also have good amount of people who have 4 rating.
-	Employee with rating 2 lie within average age of 24 to 39.
-	People with 2 rating in salary hike, environment satisfaction, promotion and job involvement.
•	Data Science
-	They have least amount of people working. Total of 20 employees but contribute more in employees performance rating
-	Number of female employees are less than the male employees.
-	This department has a mix of employees with different education background
-	People with 3 rating are high here.
-	It is found that employees with age around 40 are the ones with 2 rating. Otherwise age is not a constraint here to perform good here.
-	The head count they have doesn’t affect on their performances.
-	There is more scope to improve employee performance when there is increased job involvement of individuals
•	Human Resources
-	Total employees working here are 54.
-	All employees are of same educational background.
-	The performance of female employees outstand the male employee even though they are less in numbers.
-	Employees with 2 rating mostly lie between the age of 31 and 44.
-	Some good performers lack in Employee job involvement and employee relationship satisfaction.
•	Research & Development
-	They have large numbers of employees working here. Total of 343.
-	People with different education background work here.
-	Female employees are less but they have good performance rating.
-	This department shows increased 2 rated employees than 3.
-	There is lack in employee environment satisfaction.
•	Sales
-	They have highest number of employee of 373 working.
-	Even though most of the employees are from marketing educational background, it is found that they contribute less in performance rating matrix
-	2 rated employees are more than 3. 
-	Employees with more 2 ratings are from sales department when compared to others, they lack more in employee environment satisfaction and employee job involvement 
•	Finance
-	Number of employees working here are 49.
-	Male employees perform good here. It is also found that people with 2 ratings are increased in number here.
-	Employee salary hike and environment satisfaction has great scope to improve, because many people lack here.

**Result 2: The Top 3 important features affecting the employee performance**
Feature engineering was done to identify the important features which affects the employee performances. Using correlation coefficient and the feature importance in random forest algorithm in sklearn the 3 importance features in the dataset was identified. 
•	Employee Salary Hike Percentage
•	Employment Environment Satisfaction
•	Years Since the last Promotion

**Result 3: A Trained model which can predict the employee performance**
The dataset was trained model using supervised machine learning algorithm with classification method with the accuracy score,
•	Random Forest classifier: 92% accuracy
•	Gradient boosted Classifier: 93% accuracy

**Result 4: Recommendations to improve the employee performance**
Summarising from the above analysis, following steps are recommended to maintain and enhance the performance of the employees 
-	Even though the number of male employees exceeds female in count, it shows that female contributes more when compared to male. More female employees can be recruited to increase the performance of the company.
-	The Employees contributes more in performance are Business Analyst than the Senior Manager R&D. Area where they lack contribution (EmpRelationshipSatisfaction and EmpWorkLifeBalance) to the company has to be enhanced to increase their performance.
-	More employees who contributes 2 rating. EmpJobLevel is low for Research & Development and EmpLastSalaryHikePercent is low for Sales department. This has to revised for both the department.
-	EmpJobSatisfaction, EmpJobInvolvement, EmpRelationshipSatisfaction has to be improved to increase the performance of the employees.
-	Ensure the employees get salary hike at regular intervals with job level promotion. This will increase motivation for an employee to contribute more towards the performance of the company
-	Constant monitoring of employees working environment satisfaction. Bringing more infrastructure in their working environment. This may boost them up psychologically to spend more hours productively.
-	Regular trainings can be conducted. Workshops or providing online courses which will enhance employees to update their domain knowledge and skills in the department they are working in.
-	Conducting fun games at workplace at regular basis contributes to a good work life balance.

# Employee Churn Predictor

The repository contain machine learning process to predict employee churn based on certain condition of inputs using multiple machine learning model (support vector machine, decision tree, and logistic regression).

Employee churn in a corporate setup is one of the complex challenges that the people managers and the Human Resources personnel have to deal with. 

According to Saradhi and Palshikar (2010), losing an employee is a problem for various reason:

1. Difficulty to find replacement of a certain employee which consider highly skills;
2. Recruitment process can be costly in terms of time and money;
3. Disrupt the business flow (ongoing projects and services); and
4. Held multiple training for new employee to get to know how the business work (lots of effort).

Therefore, understanding why and when employees are most likely to leave can lead to actions to **improve employee retention** as well as **possibly planning new hiring in advance**. The model is expected to give **a high-accuracy performance** to be able to predict the employee's intention to churn or resigned.

The model has been trained using input and output extracted from the Kaggle website which can be accessed at https://www.kaggle.com/datasets/weinoose/dataset-for-churn-prediction. Below is the description of each input and output feature:

_Input (13 features)_

Input (13 features)
Row: <int> number of row
Id: <int> employee's id
Surname: <str> employee's surname
Score: <int> credit score of an employee
Nationality: <str> employee's nationality
Gender: <str> employee's gender
Age: <int> employee's age
Tenure: <int> employee's tenure
Balance: <float> employee's total bank balance
Products: <float> product count bought by employee
Card: <int> employee owns a credit card or not
Active: <int> employee is active or not
Salary: <float> employee's annual income
  
_Output (1 feature)_

Exited: <int> employee resigned or not
  
With the help of three Machine Learning models (**logistic regression, decision tree, and support vector machine (SVM)**), the input features are expected to give a high-accuracy performance to be able to predict the employee's intention to churn or resigned.  


Nowadays, there are many papers or research journal discussing about employee churn or attrition. Mostly, most of the paper did not experiment with the balance data, 
perform experimental on the balance output train data.


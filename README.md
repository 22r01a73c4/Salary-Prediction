# Salary-Prediction

Project Description:

The Employee Salary Prediction project is a machine learning application designed to estimate an employee’s salary based on key attributes such as Job Role (JOB_ID), Manager ID, and Department ID. By leveraging historical HR data, the system helps organizations forecast compensation, maintain salary consistency, and assist in strategic workforce planning.



Objectives:

To develop a predictive model that accurately estimates employee salary based on job-specific and organizational features.
To streamline HR operations related to salary benchmarking and workforce cost estimation.
To build an interactive and user-friendly tool (Google Colab or Streamlit-based) that allows dynamic salary predictions.

 Key Features:
 
Clean and preprocess employee dataset from Excel
Use Linear Regression to build a salary prediction model
Encode categorical features (like JOB_ID)
Allow user inputs via dropdown and number fields
Display real-time salary predictions
Interactive interface built with ipywidgets (Colab) or streamlit (local)

 Dataset Description:
 
Feature	Description
EMPLOYEE_ID	Unique identifier for each employee
JOB_ID	Role or designation of the employee
MANAGER_ID	Manager assigned to the employee
DEPARTMENT_ID	Department the employee belongs to
SALARY	Monthly salary of the employee (Target)
(Others)	Name, email, phone, hire date (ignored in model)

 Technologies Used:
 
Tool / Library	Purpose
Python	Programming language
Pandas	Data manipulation
scikit-learn	Machine learning model
ipywidgets	Interactive widgets in Colab
openpyxl	Reading Excel files
Streamlit (optional)	GUI for web app deployment

Output:
Given inputs for:

JOB_ID

MANAGER_ID

DEPARTMENT_ID

The model outputs:

💰 Predicted Salary (e.g., ₹6,200.54)

 Use Cases:
 
HR salary estimations and benchmarking
Workforce budgeting and planning
Candidate offer calculations
Internal equity analysis

 Conclusion:
 
This project demonstrates how machine learning can be effectively applied to automate and enhance salary prediction tasks. It empowers HR departments to make data-driven, fair, and efficient compensation decisions.

# Pewlett-Hackard-Analysis

## Project Overview
The initial project was to perform employee research for a company called, Pewlett Hackard, to specifically find answers to the following questions: 
1) Who will be retiring within the next few years?
2) How many positions will be required to fill? 

The employee data was contained into six (6) CSV files, which was imported into PostgreSQL system. Through Quick DBD, the developed entity relationship diagram (ERD) was used as the map in designing tables in SQL in order to create databases needed for the analysis. The analysis generated a list of all employees who are eligible for the retirement package as well as provided a count of employee positions by department that will need to be filled due to the retirements. 

After presenting the inital results, a brand new assignment was called that required two (2) deliverables below to further help Pewlett Hackard prepare for what they called the "silver tsunami" as many current employees are about to reach retirement age. Further queries were written and executed for these deliverables to create the databases which are exported into CSV files.
1) To determine the number of retiring employees per title.
2) To identify employees who are eligible to participate in a mentorship program. 

## Deliverable 1 Results
* A Retirement Titles table was created to list employees who are born between January 1, 1952 and December 31, 1955

![image_retirement_titles](https://github.com/Lora-Borja/Pewlett-Hackard-Analysis/blob/main/image_retirement_titles.PNG)


* A Unique Titles table was created that contains the employee number, first and last name, and their most recent title

![image_unique_titles](https://github.com/Lora-Borja/Pewlett-Hackard-Analysis/blob/main/image_unique_titles.PNG)


* A Retiring Titles table was created that contains the number of retiring employees by their titles

![image_retiring_titles](https://github.com/Lora-Borja/Pewlett-Hackard-Analysis/blob/main/image_retiring_titles.PNG)


## Deliverable 2 Results
* A Mentorship Eligibility table was created to list current employees who were born between January 1, 1965 and December 31, 1965

![image_mentorship_eligibility](https://github.com/Lora-Borja/Pewlett-Hackard-Analysis/blob/main/image_mentorship_eligibility.PNG)

## Overall Summary
Based on the analysis results, there is quite many employees retiring. There company will need to fill a total of 90,398 across various titles. Majority of the employees who are retiring soon holds senior level titles, which is signaling a high impact result of the upcoming "silver tsunami" to the company's resources. The summary of the employee count who are retiring which is also broken down by titles can be seen in the above table under deliverable 1. Further, a list of retiring employees names along with their most recent titles is also provided in a CSV file. 

There is a total of 1,549 qualified, retirement ready employees in the various departments to mentor the next generation of Pewlett Hackard employees. The list of employees that have mentorship eligibility is also provided in a CSV file. Majority of the employees on this list do hold similar senior positions and/or titles who can therefore help in ensuring that the company can train upcoming employees and lessen the impact of the "silver tsunami".

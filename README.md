# Pewlett-Hackard-Analysis

### Overview
The purpose of this project was to project the amount of employees that will be retiring within the next few years. The company would like to know who will be retiring as well as an estimate of when they are going to retire. They also would like to prepare retirement packages as well as prepare to fill a retiree's position with a new hire. Unforturnely, the data is held within Excel and would like to create a database using SQL. 

## Results

The image below is part of the result of combining the employees and titles tables for employees that are born between 1952 and 1955. Some of the employees hold two rows of data due to promotions or movement from one department to another. 

![retirement_titles_table](https://user-images.githubusercontent.com/87910875/137645169-2f2fc51f-d0c2-4437-b116-d6e13b0fe818.png)

The image below is the unique titles table which takes the data from the employees and titles tables and only pulls one row of data per employee.

![unique_titles_table](https://user-images.githubusercontent.com/87910875/137645486-8a7d46b2-0817-42f6-9567-f14f4fbb2ec9.png)

  * The amount of employees that are within the retirement age are in the tens of thousands who also mostly hold senior level positions. This could increase the difficulty     of finding adequent hires to fill their positions.
  
  * The cost of a mass retirement within the company will be massive mostly due to the loss of many employees but also due to the cost of retirement packages for        employees who have been with the compnay for an extensive period.
 
The image below is the combination of the employees and department employees tables. This table was created to determine if certain employees were eligable for being a mentor. The table is filtered by the employees who are born in 1965.

![emp_deptemp_table](https://user-images.githubusercontent.com/87910875/137645679-043dce7f-3694-40da-af65-5a918c2a4e24.png)
  
  * They're about 1550 employees who are eligable to become mentors each of them also holding senior level positions.
  * Having a large number of employees who can become mentors is great news. Creating a mentorship program would help new hires become more acquainted with their new postion whether they've been promoted or are new hires.

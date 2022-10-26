# code-exercises

Exercise Objectives

////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

DS&A exercise: 

Part 1: Sorting Arrays

Develop a program that asks the user to enter a capital for a U.S. state. Upon receiving the user input, the program reports 
whether the user input is correct. For this application, the 50 states and their capitals are stored in a two-dimensional array 
in order by state name. Display the current contents of the array then use a bubble sort to sort the content by capital. Next, 
prompt the user to enter answers for all the state capitals and then display the total correct count. The user's answer is not case-sensitive.

Part 2: Sorting & Searching HashMap

Now revise the code to store the pairs of each state and its capital in a Map using the HashMap function. Display the content of the Map, 
then use the TreeMap class to sort the map while using a binary search tree for storage. Next, your program should prompt the user to enter a 
state and it should then display the capital for the state.

////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Database Management Exercise:

From a high-level standpoint, this exercise consists of the following steps:

1. Selection of a database.

2. Identifying the requirements for the database based on the purpose for the database and the data to fill the database.

3. Create a database design based on the requirements for the database, create the physical database, and load data into the database.

4. After loading the database, carry out sample queries that would be performed on the actual database. Show the results of the sample queries.

////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

Database Programming

A. Write the SQL statements in order to create the tables for the database. Use the Entity Relationship Diagram (ERD) of the database shown in 
Figure 1. For simplicity, we are assuming in this exercise that a book cannot be written by more than one author. You need to create the tables as 
well as the required constraints, including the keys (primary and foreign), and the relationships between tables.

Figure 1: ERD for Library Database
ERD diagram
B. Populate your database with the sample set of data given to you in the tables below the assignment prompts.

C. Write the following queries to retrieve the information detailed below:

Display all contents of the Clients table
First names, last names, ages and occupations of all clients
First and last names of clients that borrowed books in March 2018
First and last names of the top 5 authors clients borrowed in 2017
Nationalities of the least 5 authors that clients borrowed during the years 2015-2017
The book that was most borrowed during the years 2015-2017
Top borrowed genres for client born in years 1970-1980
Top 5 occupations that borrowed the most in 2016
Average number of borrowed books by job title
Create a VIEW and display the titles that were borrowed by at least 20% of clients
The top month of borrows in 2017
Average number of borrows by age
The oldest and the youngest clients of the library
First and last names of authors that wrote books in more than one genre


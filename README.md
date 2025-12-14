# Python-Appointment-Manager

Introduction 
This project developed to apply the concepts we learned in Python programming. Implementing a simple, functional and modular Python program using variables, loops, conditions, list, string and functions.
We selected a real –world problem managing daily appointment, busy day and many distracted, we need simple applications to help us to arrange our daily appointments.
To store, search and editing, instead of using complex applications, Python helps us to manage these tasks.

Problem Definitions:
Managing multiple appointments is very hard and struggling for many people.
Even using notes, paper or special models to write.
The problem include:
Forgetting times and dates, unable to update or delete appointments, difficulty in organizing appointments.
Importance for the program:
Building simple program in Python to manage appointments using programming concepts. The ability to easy solution, clean, minimal error. Providing simple, fast and free distractions. Perfect efficient tool 
Program Objective:
The main objective for appointment Manager:
1- Adding allow user to add a new appointments.
2- Viewing allow user to review all appointments.
3- Deleting allow to delete any appointments.
4- Editing allow user to modify all appointments.
5- Searching allow user to for ant appointments.
6-Using Python concepts : Input /Output  , Loops , Lists , Strings , Functions and Conditions.

System Design:
Using Python Function the program, dividing the program into small tasks  follows a modular design, every function is separated for its function to achieve clear and the ability to continue.
Data Structure:
A Python list is used to store all appointments:
appointments = []     
 
each appointment is store as a dictionary including 
ID ,Date, Time and Description .allowing access , deleting and modifications
 

Main  Function:
Purpose	Function
Searching by date 	Search_ appointment ()
Adding a new appointment 	Add_ appointment ()
Displaying all appiontments 	View _  appointments ()
Deleting by ID	delet_ appointment  ()
Editing appiontment 	Edit _ appointment ()
Handling user inertaction 	Main _ menu  ()
 
Control Structure:
The program uses:
Loops: 
For loop to search or display appointments.
While loop for menu. 
Conditions:
To check user validation or choices.
 Implementation:
Input and Output: The user interact with console throw input () , print () .
 
List and Dictionaries:
Each appointment is represented as a dictionary and appointments are stored in a List.
Loops:
Keeping the main menu active throw loops until the user choose to exist.
 Error Handling:
The project cover: Empty lists (no appointments), Invalid ID, Editing the existing appointments.
Main menu:
 The menu include 6 options and calls the appropriate functions using conditions. 
 
Testing:
To ensure the program work correctly serval test were performed:
1-	Adding appointments 

(2025-01-1, 10:15 PM, Dentist) 
Result: Appointment saved with ID =1
 
2-	Viewing appointments 
Result: Display all saved appointments.
3-	Searching by  Date
Input: 2025-01-1
Result: Displayed the correct appointment.
 
4-	Deleting
Input: ID=1
Result:  appointment erased .
 
5-	Editing 

Input: ID =2 , Changing the date from 10:15PM to 02:30PM
Result:  appointment updated . 
 
Conclusion:
The program solved a real-world problem by providing organized appointments manger, demonstrating the use of Python programming concepts.
All requirements  were defined  : Input / output , conditions ,  Loops , Lists , String , Functions .
The program runs smoothly without error and provides a user friendly experiences the program  























 

   
  
 




 



 

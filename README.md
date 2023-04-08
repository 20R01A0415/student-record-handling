# student-record-handling
 I would describe the code given as a program for managing student records. It includes functions for entering, displaying, searching, updating, and deleting student data. The program starts by declaring string arrays to store data for 20 students, and an integer variable to keep track of the total number of students entered into the system.

The "enter" function prompts the user for the number of students to add and then proceeds to collect data on each student, including their name, roll number, course, class, and contact information. If no data has been entered previously, the function adds the new student data to the arrays. Otherwise, it appends the new data to the end of the arrays.

The "show" function displays all the student data entered into the system, or prints an error message if no data is present.

The "search" function prompts the user for a student's roll number and then searches the array for a matching record. If found, the function displays the student's data. Otherwise, it prints an error message.

The "update" function allows the user to update the information for a specific student. It prompts the user for the roll number of the student to update and then displays their current information. The user can then enter new information for the student, which overwrites the previous data.

The "deleterecord" function provides two options for deleting student data. The first option deletes all records from the arrays, and the second option prompts the user for the roll number of the student to delete and removes the matching record.

Finally, the main function displays a menu for the user to choose which action to take, and loops continuously until the user chooses to exit the program.

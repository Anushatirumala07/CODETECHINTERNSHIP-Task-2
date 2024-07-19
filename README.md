# CODETECHINTERNSHIP-Task-2
Name: ANUSHA TIRUMALA
Company: CODTECH IT SOLUTIONS
ID: CT12DS312
Domain: Java Programming
Duration: May to July 2024
Mentor: G.Sravani
Overview of StudentGradeTracker Java Program
Purpose:
The StudentGradeTracker program serves the purpose of allowing users (typically educators, students, or administrators) to input grades for various subjects or assignments, calculate the average grade, determine the letter grade based on predefined criteria, and optionally compute a GPA based on the letter grade.

Components and Functionality:
Initialization and User Input:

The program starts by initializing a Scanner object to read user input.
Users are prompted to enter the number of subjects or assignments for which grades will be tracked.
Grade Input Loop:

Using a loop, the program iterates through each subject or assignment, prompting the user to enter:
The name of the subject or assignment.
The grade received for that subject or assignment.
Each subject name and grade are stored in separate lists (subjectNames and subjectGrades).
Average Grade Calculation:

After gathering all grades, the program calculates the total grade by summing up all grades stored in subjectGrades.
It then computes the average grade by dividing the total grade by the number of subjects or assignments (numSubjects).
Letter Grade Determination:

Based on the calculated average grade, the program determines the letter grade using a method (calculateLetterGrade(averageGrade)).
The calculateLetterGrade method uses conditional statements (if-else) to assign a letter grade ('A', 'B', 'C', 'D', 'F') based on the average grade.
GPA Calculation (Optional):

For demonstration purposes, the program calculates a GPA corresponding to the letter grade using another method (calculateGPA(letterGrade)).
The calculateGPA method utilizes a switch statement to assign a GPA value (4.0, 3.0, 2.0, 1.0, 0.0) based on the letter grade.
Output:

After computing the average grade, determining the letter grade, and optionally calculating the GPA, the program displays a summary:
The average grade is shown with two decimal places.
The determined letter grade is displayed.
If calculated, the GPA is shown with two decimal places.
Closure:

Finally, the program closes the Scanner object to release resources.
OUTPUT:
![Screenshot 2024-07-19 220423](https://github.com/user-attachments/assets/0019229b-425c-428c-bc7e-04647589d913)




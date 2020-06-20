# Grade_Calculator
A python TkInter tool to calculate your grade in a class.
Supports both weighted and unweighted calculations.

Upon running the application, the primary window of the program is opened.  At the top of this window is a bar where the user can input the name of the assignment, select whether the grade should be calculated using a weighted average or a summation of the total number of points, and a button that calculates the grade.  At the bottom of the window is a button with a plus on it that adds a new assignment to the list.  Each assignment contains a button with a minus on it that removes the assignment from the list, and input boxes for the number of points the user got on an assignment, the number of points the assignment was worth, and the weight of the assignment.  If the points radio button is selected at the top, the input box for the weight of the assignment is uneditable.

When the "Calculate Grade" button is pushed, the total grade appears to the right of the button.  If any of the values in the boxes are invalid for purposes of calculating the grade (invalid values being negative numbers, letters, etc), an error message will pop up requesting that all values be positive.  If the "points" button at the top is selected, the sum of the number of points earned for all assignments will be divided by the sum of the total points for all assignments.  If the "weighted" button at the top is selected, for each assignment the percent score is calculated by dividing the points earned by the total points, and then the percent score is multiplied by the weight to produce the weighted score.  This weighted scores of all the assignments are then summed up and divided by the sums of the weights, producing the total weighted grade.

# GPAcalculator
Calculates College GPA using Java and base Java libraries.
Can be used by anyone who is looking to make something similar. 

Breakdown of code:
(All imports should automatically be imported if you have any recent version of Eclipse IDE)
The 3 classes that are used here are Main, ActionEvent (Listener), GPA_calculator (Frame)
- Frame sets up the window, the drop-down selections, and all the buttons
- Listener is where the new buttons are created for additional courses
- Main is required by the program but does not have much code in it
- Additional note: Java list/drop-down options creation by using buttons in the application has code from lines 42-57 + 79-93 

Features
- Users can input their grades using a dropdown menu.
- GPA is calculated based on a pre-defined scale of letter grades to grade points.
- Supports adding courses dynamically up to a maximum of 10.
- Displays the final GPA in a dialog box.

Technologies Used
- Java: The core programming language used.
- Swing: For building the graphical user interface (GUI).
- JComboBox: Used for grade selection dropdowns.
- JOptionPane: For displaying the GPA results.

How to Run

1. Clone or download the project.
2. Compile the Java code using a terminal or an IDE like IntelliJ IDEA, Eclipse, or NetBeans.
3. Run the GPA_calculator class to launch the application.






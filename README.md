NAME : CHINTHADA PRATHYUSHA
ID : CT08DS1243
MENTOR : SRAVANI
DURATION : 25/5/2024 TO 25/6/2024
COURSE : JAVA PROGRAMMING 
DESCRIPTION :
             The `StudentGradeTracker` Java program is designed to calculate and display the average grade and corresponding letter grade for a student based on their marks in various subjects. This console-based application makes use of basic Java features such as arrays, loops, conditional statements, and user input handling through the `Scanner` class.

### Key Features:

1. **User Input for Number of Subjects**: 
   - The program starts by prompting the user to enter the number of subjects. This determines the size of the array that will hold the marks for each subject.

2. **Array for Storing Marks**:
   - An integer array, `subjectMarks`, is initialized to store the marks for each subject. The size of this array is based on the number of subjects entered by the user.

3. **Input Loop**:
   - A `for` loop iterates through each subject, prompting the user to input the marks. These marks are stored in the array, and simultaneously, the total marks are accumulated.

4. **Calculation of Average Grade**:
   - After all marks have been entered, the program calculates the average grade by dividing the total marks by the number of subjects. This is achieved using type casting to ensure the result is a double for precise division.

5. **Determination of Letter Grade**:
   - The program then determines the letter grade based on the average grade. The grading criteria are:
     - `A` for average grades 80 and above.
     - `B` for average grades between 60 and 79.
     - `C` for average grades between 40 and 59.
     - `D` for average grades below 40.

6. **Output**:
   - Finally, the program prints out the calculated average grade and the corresponding letter grade.

### Usage:
To use the `StudentGradeTracker`, a user runs the program and follows the prompts. They input the number of subjects and the marks for each subject. The program processes these inputs and outputs the average and letter grades, providing a simple and effective tool for students or educators to track academic performance.

### Conclusion:
The `StudentGradeTracker` demonstrates fundamental programming concepts such as user input handling, loops, arrays, and conditional statements. It is a practical example of how these concepts can be applied to solve real-world problems, like calculating grades, making it an excellent exercise for beginner Java programmers.

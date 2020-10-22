The academic office at the Hogwarts School of Witchcraft and Wizardry has compiled data about students' grades. The data is provided as text from standard input in three parts: information about courses, information about students and information about grades. Each part has a specific line format, described below..

Information about courses
Line format: Course Code~Course Name~Semester~Year~Instructor
Information about students
Line format: Roll Number~Full Name
Information about grades
Line format: Course Code~Semester~Year~Roll Number~Grade
The possible grades are A, AB, B, BC, C, CD, D with corresponding grade points 10, 9, 8, 7, 6, 5 and 4. The grade point average of a student is the sum of his/her grade points divided by the number of courses. For instance, if a student has taken two courses with grades A and C, the grade point average is 8.50 = (10+7)÷2. If a student has not completed any courses, the grade point average is defined to be 0.

You may assume that the data is internally consistent. For every grade, there is a corresponding course code and roll number in the input data.

Each section of the input starts with a line containing a single keyword. The first section begins with a line containing Courses. The second section begins with a line containing Students. The third section begins with a line containing Grades. The end of the input is marked by a line containing EndOfInput.

Write a Python program to read the data as described above and print out a line listing the grade point average for each student in the following format:

Roll Number~Full Name~Grade Point Average
Your output should be sorted by Roll Number. The grade point average should be rounded off to 2 digits after the decimal point. Use the built-in function round().

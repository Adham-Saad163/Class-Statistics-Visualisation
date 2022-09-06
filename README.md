# Class-Statistics-Visualisation
This program automates the process of collecting, calculating, and visualizing class statistics with a user-friendly GUI for courses PHYS101 and PHYS102 at University of Science and Technology at Zewail City.

In the first part of the project, we wanted to design a software that can calculate the final grade of any student and each of their individual component of the coursework according to the course grading system [1]. In the second part, we wanted to design a software that can graphically display useful class statistics after each midterm. These statistics include making a graph of grades distribution, average grade, median grade, and standard deviation. These statistics give real insight into students’ level and can be used to solve future problems that students might otherwise fall into.

To construct the graph, we used matplotlib, a widely known python library for scientific graphing and data visualization. To extract the data from CSV files, we used pandas, a famous python library for data science and analysis. For Excel files, we resorted to openbyxl library, yet another great python library specifically designed for data manipulation in Excel files.

User Manual
1-	Run “main.py”.
2-	Read the instructions carefully, it will thoroughly explain the program flow.
3-	For Personal grade calculation enter “1” and for class analysis enter “2”.
4-	Suppose personal grade was chosen, you will need to provide 
a- midterm1 grade, b- midterm2 grade, c- five quiz grades, d- fourteen assignment grades, e- final exam grade.
5-	Suppose class analysis was chosen, you will need to choose what file extension you will use to provide midterm grades (Excel, CSV, Text, Directly into the terminal)
and then provide the full path to the file.
6-	Enter the name of the file in which you would like to save the output data.
7-	If you prefer to provide your data through a GUI (for either personal grade or class analysis) run “Main_Win.py”.
8-	If you chose class analysis, choose the file type and you are done.
9-	If you chose personal grade, enter all your grades, and click “check” next to it to save the grade into the program.
10- If there is any bonus enter it, if there is not, click no.
11- Final click calculate and there is your final grade in the course.

[1] PHYS 101/102 grading system:
15% on best 12 assignments out of 14 
15% on best 4 quizzes out of 5
30% on 2 midterm exams (60% of the higher grade, and 40% on the lower grade)
40% on final exam


# Lab Report 5
## Part 1 - Debugging Scenario
![image](s1.png)

TA message: Have you exactly checked your directory when copying the path from the "student" submission? What are the ways in order to copy the submission and run their .java file through the tester files? Try `cp ListExamples.java ../grading-area`

![image](s2.png)

The error is in line 15, where it says `cp ListExamples.java ../grading-area.txt` which causes the error of JUnit having trouble finding the ListExamples.java, thats the student submission through autograder, when the directory is trying to copy down a NON-existing directoy of a grading-area text file.

![image]()

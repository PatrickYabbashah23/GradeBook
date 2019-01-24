# GradeBook
#This program simulates a student's list of grades in a grade book that has been organized and updated 

#Grades and classes from last semester 
last_semester_gradebook = [("politics", 80), ("latin", 96), ("dance", 97), ("architecture", 65)]

#Current classes you are taking for the semester 
subjects = ["physics", "calculus", "poetry", "history"]

#Current grades for classes this semester
grades = [98, 97, 85, 88]

#Adds "Computer Science" course along with the grade recieved towards the list 'subjects' and 'grades'
subjects.append("computer science")
grades.append(100)

#Also addes "Visual Arts" along with the grade recieved towards their respective list
subjects.append("visual arts")
grades.append(93)

#Combines the list of classes being taken and current grades for the semester
gradebook = list(zip(subjects, grades))
print(gradebook)

#Full gradebook of grades and classes combined from both the current and last semester 
full_gradebook = gradebook + last_semester_gradebook

# CMSC_447_Assignment1 Overview
![App Overveiw](images/App-Overview.PNG)
This is the overview of the project, there are four tables on display and it includes the table for the student, instructor, course, and the student_course table, and for each table, the user can insert a new object, they can delete an existing object and they also have the ability to update an object in each table.
## How the application Works:
* A student table contains the name, number or credits and id of that particular student.
* A new Student can be inserted by clicking the insert button under the student table, then user is prompted with a form to fill out the student information


![Insert-Student](images/Insert-Student.PNG)

* After the user fills out the form and inserts the student, the new student will be inserted into the table and also displayed by the table.

![Student-Inserted](images/Student-Inserted.PNG)


* An Insrtuctor table contains the name, course department and id of that particular instructor.
* A new instructor can be inserted by clicking the insert button under the instructor table, then user is prompted with a form to fill out the instructor information


![Insert-Instructor](images/Insert-Instructor.PNG)

* After the user fills out the form and inserts the instructor, the new instructor will be inserted into the table and also displayed by the table.

![Instructor-Inserted](images/Instructor-Inserted.PNG)

* A course contains the the id of the course, the title of the course, and the Instructor of the course
* There is one to many relationship between the course and Instructor so in the context of this application that means that in order for a course to be inserted into the there needs to be a instructor that can teach that course
* Therefore in the application the user can only insert a course from the list of instructors that are available, and here is how it looks

![Insert-Course](images/Insert-Course.png)

* As seen by the image the user is only able to insert an instructor from the list of instructors table and cannot just insert and random instructor.
* Here is the final result

![Course-Inserted](images/Course-Inserted.PNG)

* The last table in the application is the Student/Course Table, and this table is a many-to-many table between the student and the course
* For this application when a course inserted it prompts the user to insert the course id and student id and the grade of the student 
* The course id and student id already exists and the user is required to select from that list

![List-Student](images/List-Student.png)

* As seen above only the list of the Students that already exist are apart of the options

![List-Course]()

* As seen above only the list of the courses that already exist are apart of the options



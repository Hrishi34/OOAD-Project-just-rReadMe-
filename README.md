# **This is project that was developed as a part of OOAD project in 6th sem using spring boot IDE. This only contains the readme component of the actual project. The actual project is not public due to privacy reasons.**


# Problem Statement

The current system at PES University faces challenges in managing elective courses and assigning faculty to students. The manual process of sharing Google forms for each iteration through mail leads to inconvenience and confusion for students. Once the student responses from forms are recorded, they have to be extracted into excel sheets and fed to the algorithm manually for allocation of students and faculty. Additionally, the coordinator and IT staff do not have a single platform to view the allocation database.


# Abstract

To address these issues, this project proposes an Elective Automation System that provides a single platform for students, coordinators, faculty and IT staff. The system automates the processes of allocation of students to electives and their query resolution.
 The project will be developed as a modern web-based application using the Spring Boot framework and implementing the MVC architecture. The system will comprise four modules: Student, Faculty, Coordinator, and IT Staff, each with a distinct dashboard. The Student module will enable log in and select elective subjects for the first iteration, select elective subjects and faculty for respective subjects in the second and third iterations, finally view allocated electives-faculties and even raise queries. The Coordinator module will provide access to student databases and elective course information. Additionally  the Coordinator module will allow coordinator to address queries raised by students. Functionalities provided by IT staff and Faculty are similar which is to view the allocated results. Upon completion of the submission process for each iteration (2 in total), an algorithm will allocate students based on their CGPA and faculty availability. 


# Use Case Diagram 

![image](https://github.com/Hrishi34/OOAD_Project/assets/83940584/0e14cb3d-8fc0-4a6c-a110-d015f3a29b1f)


# CLASS MODELS:

#### MODEL 01: USER 
#### MODEL 02: STUDENT (Iteration 01)
#### MODEL 03: STUDENT (Iteration 02 and 03)
#### MODEL 04: QUERY MODEL
#### MODEL 05: ALLOTMENT RESULT



# DESIGN PRINCIPLES :

#### Single Responsibility Principle (SRP)
#### Dependency Inversion Principle (DIP)
#### Interface Segregation Principle (ISP)



# DESIGN PATTERNS:

#### SINGELTON PATTERN
#### FACTORY PATTERN
#### REPOSITORY PATTERN


# Some SSs:

### 1. Front page

![image](https://github.com/Hrishi34/OOAD_Project/assets/83940584/cf14d427-4ea2-41ae-8cdb-72a280af5159)



### 2. Sign Up page.
 
![image](https://github.com/Hrishi34/OOAD_Project/assets/83940584/26b81440-6832-41ad-9cc9-ed83dfeffc84)



### 3. Elective Enrollment form

![image](https://github.com/Hrishi34/OOAD_Project/assets/83940584/c8ecfcdc-68ba-434c-907e-8d6145184b3d)








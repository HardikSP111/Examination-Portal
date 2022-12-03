# Project Title : - Examination Portal

## Contributors : - 
   1. Hardik Pachange
   2. Om Bhoge
   3. Tanmay Mitkari
   4. Praveen Tripathi

## Introduction : -

   The online exam system project in Python focuses mainly on dealing with student’s examinations. Also, the system displays all the question sets. In addition, the system allows managing question set by entering questions, options, and answers. This project is divided into three categories: Student, Teacher, and Admin Panel. In an overview of this web application, a student can simply register and start using it. Here, the system displays all the exams for the student. And the student can proceed to attend their examinations. All the exams are of MCQ type. After submission of answers, the student can view his/her marks with their number of attempts under respective courses. The system also counts the number of attempts a student takes in order to complete the exam.
   
   
## Existing System : -
  
  
   Existing system, in the existing system students have given exams only manually.  
   
      1. Lack of security
      2. More man power
      3. Time consuming
      4. Consumes large volume of paper work
      5. Needs manual calculation
      6. Needs to go examination hall to attend papers

## Need for the System : -
      

  Online Examination System is a computerized system which gives instant results and also saves time. It fully automates 
  the previous manual process of taking written exam schemes. Students can study independently for example at home or any place.


## Scope of Work : -
 
   
It may help to take examination easily without any hard work of writing question and answer in a very short time. It will help in current all works relative to examination. Also reduce the cost of papers and the time of paper checking. By using this system, the examination will go smoothly.

1. It satisfies the user requirement.
2.	Easy to understand by user and operator
3.	Easy to operate
4.	To assist the teachers and students.


## System requirement : -

### Server-side requirement

1. Hardware Requirements
   
   Processor-i3 or above	
   RAM-2GB or above 	
   HDD-256 GB	
   
2. Software Requirements:
   
   Operating System –windows 
   Database-MySQL
   Frontend-HTML & CSS	
   Backend-Python (Django)



### Client-side requirement
1. Hardware Requirements:
   
   Processor-i3 or above	
   RAM-2GB	
   HDD-256 GB	

2. Software Requirements:
   
   Operating System-windows	
   Browser-Mozilla Firefox, Chrome


## PROPOSED SYSTEM

The purpose of the online examination system is to test the subject knowledge of the students. Such a system eliminates logistical hassles and drawbacks in the traditional mode of the pen-and-paper examination. Students don't have to assemble in the classroom to give the exam. They can do it within a given time frame from their own device. You don't have to rent a classroom.
In an overview of this web application, a student can simply register and start using it. Here, the system displays all the exams for the student. And the student can proceed to attend their examinations. All the exams are of MCQ type. After submission of answers, the student can view his/her marks with their number of attempts under respective courses. The system also counts the number of attempts a student takes in order to complete the exam.


## Module specifications 

1. Admin
   + Admin login
   + Approve/Decline teacher’s account
   + view students details/result
   
      After Login in Admin Account admin can Manage Teacher’s accounts. Can Approve the registered teachers request or decline it. Also, can see the student details and teacher details.
      
      
 2. Teacher
    + Teacher’s registration
    + Teacher’s login
    + Add Questions
    + Delete Questions
    + View Student's Result
    
    Teacher can register and after Admin’s approval teacher can add question also can delete questions and after the exam teacher can see the results of students


3. Student
   + Student Registration
   + Student login
   + Attempt Exam
   + Check Results
   + Logout
   
   Student can register by filling information and after login students can attempt the exam, and can check their results.
   
 
## Objective Of System

The purpose of the online examination system is to test the subject knowledge of the students. Such a system eliminates logistical hassles and drawbacks in the traditional mode of the pen-and-paper examination. Students don't have to assemble in the classroom to give the exam. Students can attempt it from anywhere.

+ An online exam system that will allow to attend exams online from home or any place.
+ Teachers can take exam without paper.

## Diagrams

### Class Diagram 
![Class Diagram](https://user-images.githubusercontent.com/114462074/205432433-178a76ac-4dd8-492c-bff4-15f6e0bcc02f.jpg)

***

### Object Diagram
![Object Diagram](https://user-images.githubusercontent.com/114462074/205432784-01a721f3-6cb8-4754-b9af-0936069c5320.jpg)

***

### Componant Diagram
![Component Diagram](https://user-images.githubusercontent.com/114462074/205432807-cb067bce-5824-4d16-8ae9-528ffe73e517.jpg)

***

### Deployment Diagram
![Deployment Diagram](https://user-images.githubusercontent.com/114462074/205432842-46c4bc8c-5f87-4e8e-97ff-9145f88d854e.png)

***

### Use Case Diagram
![Use Case Diagram](https://user-images.githubusercontent.com/114462074/205432865-47b33a69-163d-4271-9c32-2aa1a7115208.png)

***

### Activity Diagram


#### 1. Student Activity
 ![1 Student (Activity) Diagram](https://user-images.githubusercontent.com/114462074/205432914-04eb3d00-1d9e-4496-9987-a1a1c6fcab18.png)
 
---

#### 2. Teacher Activity
![2 Teacher (Activity) Diagram](https://user-images.githubusercontent.com/114462074/205432933-4b44159a-e1fe-4d58-b4de-d99e1243983a.png)

---

#### 3. Admin Activity
![3  Admin (Activity) Diagram](https://user-images.githubusercontent.com/114462074/205432957-625953c0-2ce3-40a2-a64a-08d5e7cbde55.png)

---

### Sequence Daigram
![Sequence Diagram](https://user-images.githubusercontent.com/114462074/205432977-e4bf7ae7-d152-457f-b0a1-f78c3464c8f4.png)


***


### Collaboration diagram
![Collaboration Diagram](https://user-images.githubusercontent.com/114462074/205432997-e70ca869-83bd-46a4-86c6-5c8e92bdd710.jpg)

***

### State diagram
![State Diagram](https://user-images.githubusercontent.com/114462074/205433013-c826c3e9-e35c-46e8-9d04-46f3ae6bfe32.png)

***

## Table Specification
![1 Authorise User](https://user-images.githubusercontent.com/114462074/205433843-62ba8a86-a1c8-4f22-85d8-e16300693aac.png)

![2  Student Table](https://user-images.githubusercontent.com/114462074/205434201-d8fd7b44-1668-4753-884a-a13a3e5c127b.png)

![3  Teacher Table](https://user-images.githubusercontent.com/114462074/205434202-c2ba2465-4387-49ab-b178-940353dfad27.png)

![4  Subject Table](https://user-images.githubusercontent.com/114462074/205434206-a86e5af5-a7fd-4a7b-84f8-49faed4fba74.png)

![5  Question Table](https://user-images.githubusercontent.com/114462074/205434207-782a84f1-b12f-4763-8094-9c3e1f832559.png)

![6  Result Table](https://user-images.githubusercontent.com/114462074/205434208-38af097e-322f-4e1f-9f8d-9011ddae7f4a.png)


   ### Data Dictionary
![2](https://user-images.githubusercontent.com/114462074/205434056-fe38bb31-98ea-4cdc-bf7a-b42dbe53fa36.jpg)


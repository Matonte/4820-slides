---

title:        COSC 4820 Database Systems
subtitle:     Course Introduction
author:       Ruben Gamboa
#logo:         uw-logo-large.png
#biglogo:      uw-logo-large.png
job:          Associate Professor
highlighter:  highlight.js
hitheme:      tomorrow
mode:         selfcontained
framework:    io2012
widgets:      [mathjax, bootstrap]

---

<style>
.title-slide {
     background-color: #EDE0CF; /* CBE7A5; #EDE0CF; ; #CA9F9D*/
     background-image: url(assets/img/uw-logo-large.png);
     background-repeat: no-repeat;
     background-position: center top;
   }
</style>

# What Is (and Is Not) Covered in This Course

--- 

## Why You Should Take This Course

* This is the first in a two-course sequence on database systems
* This course is designed to teach you how to use databases effectively
* Almost all professional programmers use database systems
* Every programmer is expected to know
  * How to design a database schema to store information
  * How to add data to a database
  * How to use SQL (database query language)
	* How to generate reports from a database

---

## What You Will Learn

* You will learn how to use databases **effectively**
* That means you will learn
  * Different ways to map "real world" information into a database and how to evaluate the different solutions
  * Different ways to query databases
  * How to write database applications (not database systems)

---

## What You Will Not Learn in This Class

* You will **not** learn (in this class) how to use specific databases, e.g., Microsoft SQL Server, MySQL, SQLite, etc.
* You will also **not** learn how to install, maintain, or manage databases
* I.e., you will **not** learn enough to become a database administrator (DBA) just from this class
* But the concepts you learn in this class **will** apply to all databases
* With the knowledge you learn in this class, you will be able to use any of those databases effectively
* That is enough for developers, and is is the first step towards becoming a DBA

---

## More Stuff You Will Not Learn (in This Class)

* You will also **not** learn the details of how databases are implemented and how to write your own database system
* Nor will you learn about large-scale databases, e.g., distributed databases
* And you will **not** learn about the very, very large-scale NoSQL databases that are not relational databases, 
  e.g., Amazon Dynamo, Google BigTable, Facebook Cassandra, MongoDB, etc.

> * Those topics are covered in the second course (next semester???) of this two-course sequence

> * Finally, you will **not** learn about data mining or data warehousing
	  * Data mining is partially covered in Van Baalen's AI class
	  * Data warehousing is partially covered in the College of Business information management courses
	  * We may do a little bit of data warehousing in Week 14

---

# Course Policies

---

## Attendance Policies

* You must come to class
* Attendance is enforced
	* by rollcall (at first)
	* by inspection (later)
<br>

> * Let's try it out!

---{
    tpl: twocol
}

## Grading Policy

*** =left

 Item                | Pct
 --------------------|----
 Class Participation | 10%
 Assignments         | 15%
 Project             | 15%
 Exam 1              | 20%
 Exam 2              | 20%
 Final Exam          | 20%

*** =right

* If you can't take an exam, we can arrange for a makeup
* You do not need an excuse to arrange for a makeup
* Try to be here on the right day!
* Once you start taking an exam, you may not stop for any reason until you turn in the exam for grading

---

## Assignments, Project, and Exams

* Assignments
  * The assignments will be similar to exercises from the book 
  * You will take the assignments through http://www.gradiance.com
  * Assignments must be turned in on time
  * Submission windows close automatically!
* Project
  * The project is the database portion of a web application
  * You will be implementing the project in pieces
  * You can think of it as a series of related homework problems that you turn in
* Exams
  * The exams will include primarily questions that are similar to those in the assignments
  * The exams will also include a few questions that ask you to tie together ideas learned
    in several sections

---

## Collaboration Policy

* In doing the assignments, you may collaborate, search the internet, read different database books, etc.
* Feel free to **learn** with others, but always **do your own work** so you're prepared for the exams

---

## Other Policies

* Academic dishonesty
  * Zero tolerance
  * You will get a zero for the offending work
  * You will **also** lose a letter grade at the end of the semester
  * Do your own work, and come see me if you need help
* WyoCourses Website
  * Handouts, grades, and announcements
  * First task: Update your profile to include your picture
* Gradiance Website
  * Assignments
  * First task: Create an account (Access token on syllabus)
  * Check early, check often for new assignments

---

## Meetings

* Come see me during office hours
  * MWF 11-11:45am
  * MF 1-2:45pm
  * or by appointment
* Email is OK for private matters
* But I prefer that you ask class-related questions by creating a new discussion thread
  in WyoCourses, so everyone can benefit
* (And check to see if your question has been answered already)

---

## Course Outline

1. The Worlds of Database Systems
2. The Relational Model of Data
3. Design Theory for Relational Databases
4. High-Level Database Models
<hr>
5. Algebraic and Logical Query Languages
6. The Database Language SQL
7. Constraints and Triggers
8. Views and Indexes
<hr>
9. SQL in a Server Environment
10. Advanced Topics in Relational Databases *(time permitting)*





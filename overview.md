---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: "Overview"
layout: single
classes: wide
---

## Class Description

Welcome to CSE 113: Parallel and Concurrent Programming! In this class, we will explore many aspects of parallel computing, from instruction-level parallelism in seemingly sequential programs to thread-level parallel programs that can efficiently execute across the many cores of today's multiprocessors. We will learn how to write programs that execute efficiently and correctly in concurrent environments. This class will give you the necessary foundation to solve problems using concurrency: a powerful skillset as today's computers are becoming more and more parallel.

## Teaching Staff

We have a great teaching staff this quarter! All of them have lots of experience in parallel programming. This is Reese's second time TA'ing the class. Tim and Sanya took the class last year. Please get to know them and take advantage of the office hours and mentoring sessions they provide

- *Grad TA*: Reese Levine
- *Undergrad Mentor/Grader*: Tianhao Guo (Tim)
- *Undergrad Mentor/Grader*: Sanya Srivastava 


## Necessary Background

The prerequisites for this class are CSE 12 (systems), CSE 101 (data-structures and algorithms), and recommended CSE 120 (architecture). You will need some foundation in all of those topics to succeed in this class. You will need to know data-structures and algorithms as we will extend some of these sequential concepts to their natural parallel counterparts. You will need some systems background as we will discussing many aspects of the hardware/software interface. Parallel programming is most efficiently executed on parallel hardware: Thus, it is helpful to understand shared  hardware resources (e.g. the memory hierarchy) of the underlying architectures. 

Because this is an upper division class, I do expect a general CS foundation. For the homeworks, I will assume that you are:

- comfortable using a linux command-line
- programming in a high-level language (e.g. Python)
- programming in a low-level language (e.g. C)
- a high-level understanding of computer architecture

## Class Modules

This class will be split into 5 modules, each of which are roughly two weeks:

* **Module 1: Introduction, Background and ILP** This module will introduce the class and provide a programming, compiler, and architectural refresher. We will discuss how to write parallel code in C++ and show how modern hardware exploits parallelism within a sequential thread (ILP).

* **Module 2: Mutual Exclusion** This module will discsuss the fundamental problem of mutual exclusion. We will discuss the theory behind mutual exclusion, how it is implemented in practice, and specialized mutual exclusion implementations. 

* **Module 3: Concurrent Data Structures** This module will discuss concurrent objects and how to reason about them. We will discuss several implementations and discuss how it can be used in load balancing.

* **Module 4: Reasoning about Concurrency** This module will discuss how to reason about concurrent programs, including memory consistency and fairness. 
 
* **Module 5: Heterogenous Parallelism (GPGPU)** This module will discuss heterogenous programming, with a focus on GPGPU programming. We will discuss the SIMT programming model, hierarchical execution, and different architectural considerations when optimizing programs.

## Class Format

Each class is 65 minutes. I will plan to be available (either in Zoom or in person)
room open 10 minutes before class starts and 10 minutes
afterwards. 

For the remote lectures, I will enable global chat. I encourage you to use this to ask questions or comments throughout the lecture.

_Non-protected materials_ will be hosted on this website. This includes the schedule, lectures, and references, etc.

_Protected materials_ will be hosted on a Canvas website that you will need your university credentials to access. These materials include homeworks, zoom links, lecture recordings, tests, grades, etc.

We plan to host a class forum, likely in Piazza. If you organize other forums outside of the class Piazza, please adhere to academic integrity.

## Quiz/Attendence

Live discussions are a valuable part of the learning experience. I expect you to make an effort to synchronously attend this class, whether on Zoom on in-person.

Given the volatility of the format this year, i.e. between in-person and remote, I will not grade attendance for remote lectures. 

As we return to in-person lectures, **Attendance will be 10% of your grade**. Depending on the availability of recording equiptment, I will upload recordings of the class to canvas, but this is not a substitute for attendance. This will be graded using a small quiz at the beginning of class. Please do not submit the quiz unless you are attending. If you submit a quiz without attendance, it will be considered a breach of academic integrity. 

You can have up to 3 absences that will not affect your grade. If you need more than that, please message the teaching staff to discuss.

## Accessibility

UC Santa Cruz is committed to creating an academic environment that supports its diverse student body. If you are a student with a disability who requires accommodations to achieve equal access in this course, please submit your Accommodation Authorization Letter from the Disability Resource Center (DRC) to me by email, preferably within the first two weeks of the quarter. I would also like us to discuss ways we can ensure your full participation in the course. I encourage all students who may benefit from learning more about DRC services to contact DRC by phone at 831-459-2089 or by email at drc@ucsc.edu.

## Office Hours:

### Instructor Office Hours:

I will provide 2 office hours per week: Thursdays fro 3 - 5 PM. 

My office hours can be remote or in-person. My physical office is E2-233 (no nameplate yet, but I'm working on it!). I will provide a Zoom link on canvas. I manage the office hours through a Google doc sign-up sheet. I will reset the list around noon on Thursday and notify with a canvas announcement. Any name on the list before then will be erased.

Please sign up for only 1 slot at a time. If there is no other student waiting at the end of your slot, you are welcome to stay. If you want to discuss an issue that you think others might also be interested in, please add the issue to the spreadsheet. If you see your issue listed, please add your name and we add more people to the discussion. 

The sign-up sheet is meant to provide fairness; as such I will be strict about keeping to the schedule. Please forgive any abruptness.

### TA Office Hours:

Reese will hold hybrid office hours on Wednesdays from 2:30 to 4:30 PM. Zoom link will be available on Piazza, and room will be BE-153A when in person instruction resumes.

### Mentoring Hours:

Sanya will hold 1-1 tutoring hours primarily in-person (when we return). Location is TBD. 

* Monday 4:00 - 5:00 PM
* Friday 3:30 - 4:30 PM

_Sanya will be asynchronous until Jan. 10. Please ask questions on Piazza and she will answer._

Tim will hold 1-1 tutoring hours primarily remotely

* Tuesday 2:00 - 3:00 PM
* Thursday 2:00 - 3:00 PM



## Asynchronous Communication

For any questions outside of office hours: Please post to the class forum (Piazza). If these are sensitive questions, you can email them directly to the teaching staff. If it is more general, make it visible to the rest of class. If it isn't clear if it is a sensitive question or not, please start out by making the question to the teaching staff and we can advise on making it public or not. Feel free to answer questions that your classmates post or freely participate in discussions there!

Other questions can be sent through canvas if you'd like. If your question appears to be more appropriate for the discussion forum, we may kindly ask you to post your question there. Please do not email us individually. Those emails get buried, or they might not be seen by the right member of the teaching staff.

We will strive to reply to homework questions and discussions within 24 hours. Do not plan on, or expect help, outside of regular business hours (after 5 pm or weekends)

## Homework:

There will be one assignment per module, for a total of 5 homeworks.

We will host a docker container that includes the necessary environment (compilers, libraries) for the homeworks. You are free to run this docker from your local machine or from a unviversity machine. We will provide a list of university resources in Canvas. It is required that your homeworks execute successfully inside the docker. The homeworks will also specify a submission format (e.g. a directory structure). Please strictly adhere to this, as it helps with grading.

Homeworks are due at midnight on their due date, but do not plan on help after 5 pm (as mentioned above). Late homeworks are marked down 10% per day for up to 3 days, at which point they will not be accepted.

Homework will be submitted on canvas.

## Tests:

There will be two asynchronous tests in this course: a midterm and a final. The midterm will roughly be worth as much as a single homework assignment (~10%). The final will be worth 30%.

You will get the test as pdf worksheet and have a set time to complete it. You have 1 week for the midterm, and you have 12 hours for the final. 

The midterm will be given halfway through the class: assigned on Monday, Feb. 7 and due on Feb. 14. 
The final will be given on Thursday, March 17.

I will design the tests to take ~120 minutes. These are open note/book/internet tests. However, it is not open friend or question. That is, while the test is active, you are not allowed to discuss the test with another person (either in the class or online). For example, you *can* google concepts that are on the test. You *cannot* post a test question to stackoverflow.

_a note on timing_: my tests are designed to take 120 minutes *if* they were given in-person. In practice, students take much longer on take-home tests because you can spend time validating answers and less time studying before hand. Because of this, many students spend much longer on take-home tests. Please consider this when budgeting time.

## Late Policy:

Assignments are docked 10% per day late up to 3 days. After that they will no longer be accepted.  

The midterm and final will not be accepted late.

## Grade Breakdown

- Attendance/Quiz: 10%
- Homeworks: 50% (10% each)
- Midterm: 10%
- Final Exam: 30%

If you want to discuss a grade, please contact the teaching staff no later than 1 week after the grades are posted.

## Academic Integrity

One of the joys of university life is socializing and working with your classmates. I want you to make friends with each other and discuss the material. 

**That said, I expect all assignments (code, write-ups, and tests) to be your own original work.**

If you work together with a classmate on an assignment, please mention this, e.g. in the comments of your code. If you use a figure you didn't create in a write-up, then it needs a citation. Please review the [universities policy on plagiarism](https://guides.library.ucsc.edu/citesources/plagiarism)

This class has a zero tolerance policy on cheating. Please don't do it. I would much rather get a hundred emails asking for help than have to refer anyone for academic misconduct.

## Privacy

I will largely be using Zoom for remote lectures, and I plan to record in-person lectures as well. You should be aware that:

- Things you do or say will be recorded. I doubt that this will be an issue, but if you want me to remove any part of the recording, please just let me know.
- Many forums (e.g. zoom chats, Piazza posts, etc.) chats are not private. Please be respectful and kind and assume everyone can see what you are typing.

## Acknowledgements

This page is based off of Professor [Lindsey Kuper](https://users.soe.ucsc.edu/~lkuper/)'s CSE232, Fall 2020 website

---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: "Overview"
layout: single
classes: wide
---

## Class Description

Welcome to CSE 110A: Fundamentals of Compiler Design! In this class we will explore one of the most import tools in computer science: the compiler. In particular, we will explore how compiler techniques transform high level languages into low-level languages, i.e. closer to the instructions that processors can actually execute. We will study how compilers can automatically make code more efficient and safe to execute. When you leave this class you should be comfortable with: specifying programming language grammars, how to efficiently parse these languages, and how to convert complex high-level code into equivalent (and hopefully more performant) low-level code. 

Given the influx in domain-specific languages, and the explosion of architectural diversity occuring in computing today, these are valuable skills.

## Teaching Staff

We have a great teaching staff this quarter! All of them have lots of experience in compilers. Yanwen is 2nd year PhD student who did his undergrad at UCSC; Arrian and Neal took this class last quarter. Please get to know them and take advantage of the office hours and mentoring sessions they provide

- *Grad TA*: Yanwen Xu
- *Undergrad Mentor/Grader*: Arrian Chi
- *Undergrad Mentor/Grader*: Neal Chokshi

## Necessary Background

The prerequisites for this class are CSE 12 (systems) and CSE 101 (data-structures and algorithms). You will need some foundation in all of those topics to succeed in this class. You will need to know data-structures as we will use lots of trees and traversals in parsing. You will need some systems background as we will be discussing how to transform a high-level programming language into a low-level language (like assembly). CSE 103 will also be helpful as we will be using regular expressions and context-free grammars.

Because this is an upper division class, I do expect a general CS foundation. For the homeworks, I will assume that you are:

- comfortable using a linux command-line
- programming in a high-level language (e.g. Python)
- programming in a low-level language (e.g. C)

## Class Modules

This class will be split into 5 modules, each of which are roughly two weeks:

* **Module 1: Lexing** 

* **Module 2: Parsing** 

* **Module 3: Intermidiate Representations** 

* **Module 4: Optimizations**  
 
* **Module 5: Backends** 

## Class Format

Each class is 65 minutes. I plan to stay after class for roughly 10 minutes to answer questions

_Non-protected materials_ will be hosted on this website. This includes the schedule, lecture slides, and references, etc.

_Protected materials_ will be hosted on a Canvas website that you will need your university credentials to access. These materials include homeworks, lecture recordings, tests, grades, etc.

We plan to host a class forum, likely in Piazza. If you organize other forums outside of the class Piazza, please adhere to academic integrity.

## Attendance

Live discussions are a valuable part of the learning experience. I expect you to make an effort to synchronously attend this class (which will hopefully be in person all quarter).

Depending on the availability of recording equiptment, I will upload recordings of the class to canvas, but this is not a substitute for attendance. These recordings are not guaranteed (e.g. if the equiptment fails). And you will likely miss out on class discussions and may not be able to see the white board.

## Quiz

There will be a quiz for each lecture. These quizes will be assigned immediately after class and you will have until the next class starts to do them. Your answers are **not** graded, but your submission is. These are meant to test your understanding. These will account for 10% of your class grade. We reserve the right to remove points on an individual basis if we feel that there is not sufficient effort put into the quiz.

You can miss up to 3 quizes without penalty.

## Accessibility

UC Santa Cruz is committed to creating an academic environment that supports its diverse student body. If you are a student with a disability who requires accommodations to achieve equal access in this course, please submit your Accommodation Authorization Letter from the Disability Resource Center (DRC) to me by email, preferably within the first two weeks of the quarter. I would also like us to discuss ways we can ensure your full participation in the course. I encourage all students who may benefit from learning more about DRC services to contact DRC by phone at 831-459-2089 or by email at drc@ucsc.edu.

## Office Hours:

### Instructor Office Hours:

I will provide 2 office hours per week: Thursdays from 3 - 5 PM. 

My office hours can be remote or in-person. My physical office is E2-233 (no nameplate yet, but I'm working on it!). I will provide a Zoom link on canvas. I manage the office hours through a Google doc sign-up sheet. I will reset the list around noon on Thursday and notify with a canvas announcement. Any name on the list before then will be erased.

Please sign up for only 1 slot at a time. If there is no other student waiting at the end of your slot, you are welcome to stay. If you want to discuss an issue that you think others might also be interested in, please add the issue to the spreadsheet. If you see your issue listed, please add your name and we add more people to the discussion. 

The sign-up sheet is meant to provide fairness; as such I will be strict about keeping to the schedule. Please forgive any abruptness.

### TA Office Hours:

Mondays from 1 PM to 2 PM (Virtual)

Fridays from 2 PM to 3 PM (Room BE-151)

Yanwen's office hours will be hybrid and he will use a similar sign-up sheet.

### Mentoring Hours:

Arrian is Tuesday from 1 PM to 3 PM, virtual.

Neal is Wednesday 1:30 PM - 2:30 PM, virtual; and Friday 2 PM to 3 PM sharing a room with Yanwen.

## Asynchronous Communication

For any questions outside of office hours: Please post to the class forum (Piazza). If these are sensitive questions, please make the post private. If it is more general, make it visible to the rest of class. If it isn't clear if it is a sensitive question or not, please start out by making the question to the teaching staff and we can advise on making it public or not. Feel free to answer questions that your classmates post or freely participate in discussions there!

Please do not email us individually. Those emails get buried, or they might not be seen by the right member of the teaching staff. Any re-grading requests must occur through Piazza.

We will strive to reply to homework questions and discussions within 24 hours. Do not plan on, or expect help, outside of regular business hours (after 5 pm or weekends)

## Homework:

There will be one assignment per module, for a total of 5 homeworks.

We will host a docker container that includes the necessary environment (compilers, libraries) for the homeworks. You are free to run this docker from your local machine. It is required that your homeworks execute successfully inside the docker. The homeworks will also specify a submission format (e.g. a directory structure). Please strictly adhere to this, as it helps with grading.

Homeworks are due at midnight on their due date, but do not plan on help after 5 pm (as mentioned above). Homework will be submitted on canvas.

## Tests:

There will be two asynchronous tests in this course: a midterm and a final. The midterm will roughly be worth as much as a single homework assignment (~10%). The final will be worth 30%.

You will get the test as pdf worksheet and have a set time to complete it. You have 1 week for the midterm, and you have all day (8 AM to Midnight) for the final. 

The midterm will be given halfway through the class: Monday May 2; it will be due Friday May 6.
The final will be given on 	Tuesday, June 7	

I will design the tests to take ~120 minutes. These are open note/book/internet tests. However, it is not open friend or question. That is, while the test is active, you are not allowed to discuss the test with another person (either in the class or online). For example, you *can* google concepts that are on the test. You *cannot* post a test question to stackoverflow.

_a note on timing_: my tests are designed to take 120 minutes *if* they were given in-person. In practice, students take much longer on take-home tests because you can spend time validating answers and less time studying before hand. Because of this, many students spend much longer on take-home tests. Please consider this when budgeting time.

_a note on academic integrity_: I like giving take home tests. I feel like it is more representative of the types of challenges you will face in your careers. However, if we find any cheating, we will move to in-person, timed, proctored exams. Please do not cheat.

## Late Policy:

Assignments are docked 10% per day late up to 3 days. After that they will no longer be accepted. No assignment will be accepted after the day of our final. This is unversity policy, not mine.

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

---
title: "Schedule"
layout: splash
---

_I will strive to get slides uploaded before lecture_

_Unless explicitly mentioned, Readings will refer to Engineering a Compiler (EAC), see the references [page](https://sorensenucsc.github.io/CSE110A-sp2022/references.html)_

### Module 1: Lexing

| Date             | Topic    | Slides |   Readings
|------------------|----------|--------|----------------
| Mon, March 28    | Welcome!  |  [slides](lectures/CSE110A_sp2022.pdf)   | [Overview page](https://sorensenucsc.github.io/CSE110A-sp2022/overview.html)
| Wed, March 30    | Introduction to Compilers |  slides [pdf](lectures/CSE110AMarch30_sp2022.pdf) [pptx](lectures/CSE110AMarch30_sp2022.pptx)  | EAC Chapter 1
| Fri, April 1     | Introduction to Lexical Analysis  | slides [pdf](lectures/CSE110AApril1_sp2022.pdf) [pptx](lectures/CSE110AApril1_sp2022.pptx)   |
| Mon, April 4     |  Regular Expressions | slides [pdf](lectures/CSE110AApril4_sp2022.pdf) [pptx](lectures/CSE110AApril4_sp2022.pptx)  | 
| Wed, April 6     |  Implementing Scanners with REs | slides [pdf](lectures/CSE110AApril6_sp2022.pdf) [pptx](lectures/CSE110AApril6_sp2022.pptx)| 
| Fri, April 8     |  Token Actions and PLY | slides [pdf](lectures/CSE110AApril8_sp2022.pdf) [pptx](lectures/CSE110AApril8_sp2022.pptx) | 

### Module 2: Parsing

| Date             | Topic    | Slides |   Readings
|------------------|----------|--------|----------------
| Mon, April 11     | CFGS and Derivations | slides [pdf](lectures/CSE110AApril11_sp2022.pdf) [pptx](lectures/CSE110AApril11_sp2022.pptx) | EAC Chapter 3.2
| Wed, April 13     |  Parse Trees and ambiguous grammars   | slides [pdf](lectures/CSE110AApril13_sp2022.pdf) [pptx](lectures/CSE110AApril13_sp2022.pptx) | EAC Chapter 3.2
| Fri, April 15     | Associativity and top-down parsing   | slides [pdf](lectures/CSE110AApril15_sp2022.pdf) [pptx](lectures/CSE110AApril15_sp2022.pptx)  | EAC Chapter 3.3 (first half)
| Mon, April 18     | Left recursion and lookahead in parsing    | slides [pdf](lectures/CSE110AApril18_sp2022.pdf) [pptx](lectures/CSE110AApril18_sp2022.pptx)  | EAC Chapter 3.3 (first half)
| Wed, April 20     | Recursive descent parsers and symbol tables   | slides [pdf](lectures/CSE110AApril20_sp2022.pdf) [pptx](lectures/CSE110AApril20_sp2022.pptx)  | EAC Chapter 3.3 (second half)
| Fri, April 22     | Symbol Tables and parser generators | slides [pdf](lectures/CSE110AApril22_sp2022.pdf) [pptx](lectures/CSE110AApril22_sp2022.pptx)  | [ply documentation](https://www.dabeaz.com/ply/ply.html)


### Module 3: Intermediate representations

| Date             | Topic    | Slides |   Readings
|------------------|----------|--------|----------------
| Mon, April 25      | CLASS CANCELED | |
| Wed, April 27      | Intro to IRs and ASTs | slides [pdf](lectures/CSE110AApril27_sp2022.pdf) [pptx](lectures/CSE110AApril27_sp2022.pptx) |EAC Chapter 5.1
| Fri, April 29      | ASTs and type checking | slides [pdf](lectures/CSE110AApril29_sp2022.pdf) [pptx](lectures/CSE110AApril29_sp2022.pptx) | EAC Chapter 4.2
| Mon, May 2     | ASTs and type checking 2  |slides [pdf](lectures/CSE110AMay2_sp2022.pdf) [pptx](lectures/CSE110AMay2_sp2022.pptx) | EAC Chapter 4.2
| Wed, May 4     | ASTs and type checking 3 | slides [pdf](lectures/CSE110AMay4_sp2022.pdf) [pptx](lectures/CSE110AMay4_sp2022.pptx) | EAC Chapter 5.3
| Fri, May 6     | Converting ASTs into 3 address code |slides [pdf](lectures/CSE110AMay6_sp2022.pdf) [pptx](lectures/CSE110AMay6_sp2022.pptx) | EAC Chapter 5.3
| Mon, May 9     | Converting statements into 3 address code |slides [pdf](lectures/CSE110AMay9_sp2022.pdf) [pptx](lectures/CSE110AMay9_sp2022.pptx) | EAC Chapter 5.3

### Module 4: Optimizations

| Date             | Topic    | Slides |   Readings
|------------------|----------|--------|----------------
| Wed, May 11      | HW 3 overview and intro to optimizations        | slides [pdf](lectures/CSE110AMay11_sp2022.pdf) [pptx](lectures/CSE110AMay11_sp2022.pptx) | EAC Chapter 8.1
| Fri, May 13     | Optimization overview | slides [pdf](lectures/CSE110AMay13_sp2022.pdf) [pptx](lectures/CSE110AMay13_sp2022.pptx) | EAC Chapter 8.1
| Mon, May 16     | Basic blocks and local value numbering |  slides [pdf](lectures/CSE110AMay16_sp2022.pdf) [pptx](lectures/CSE110AMay16_sp2022.pptx) | EAC Chapter 8 (up to 8.5)
| Wed, May 18     | Local value numbering 2 | slides [pdf](lectures/CSE110AMay18_sp2022.pdf) [pptx](lectures/CSE110AMay18_sp2022.pptx) | EAC Chapter 8 (up to 8.6)
| Fri, May 20     | CLASS CANCELED | |
| Mon, May 23     | Loop transforms | slides [pdf](lectures/CSE110AMay23_sp2022.pdf) [pptx](lectures/CSE110AMay23_sp2022.pptx)  | EAC Chapter 7.8
| Wed, May 25     | Loop transforms 2 | slides [pdf](lectures/CSE110AMay25_sp2022.pdf) [pptx](lectures/CSE110AMay25_sp2022.pptx)  | EAC Chapter 7.8
| Fri, May 27     | Loop transforms 3| slides [pdf](lectures/CSE110AMay27_sp2022.pdf) [pptx](lectures/CSE110AMay27_sp2022.pptx)|
| Wed, June 1     | Control Flow Graphs | slides [pdf](lectures/CSE110AJune1_sp2022.pdf) [pptx](lectures/CSE110AJune1_sp2022.pptx) | EAC Chapter 8.6.1
| Fri, June 3     | Live variable Analysis | slides [pdf](lectures/CSE110AJune3_sp2022.pdf) [pptx](lectures/CSE110AJune3_sp2022.pptx) | EAC Chapter 8.6.1

## Final

Our final is scheduled for Tuesday, June 7. If you would like to block off specific hours, our scheduled time is 7:30 PM to 10:30 PM

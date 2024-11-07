---
title: Course Info.
---
## News

  * [2024/11/07] Two more exercises added to [Practicals 04 (with solutions)](pages/syllabus.html).
  * [2024/10/29] [Handouts 04, Practicals 04, and solutions](pages/syllabus.html) online.
  * [2024/10/29] [GCL Summary](pages/syllabus.html) online.
  * [2024/10/29] [Solution to Midterm Exam](pages/syllabus.html) online.
  * [2024/10/08] [Solutions to Practicals 03](pages/syllabus.html) updated with solution to question 1.
  * [2024/10/08] [Handouts 03, Practicals 03, and solutions](pages/syllabus.html) online.
  * [2024/09/20] [Solutions to Practicals 01 and 02](pages/syllabus.html) online; fixed some typos in Handouts 01.
  * [2024/09/10] [Handouts 02, Practicals 02, Theorems of Propositional Calculus](pages/syllabus.html) online.
  * [2024/09/03] [Handouts 00, 01, Practicals 01](pages/syllabus.html) online.

## Time and Location

  * Course ID: IM 5065, 725 U3930
  * Credits: 3
  * Time: Thursday 2,3,4 (9:10am - 12:20noon)
  * Location: Information Management Building 1, Lecture Room 101 (管一 101)

## Objectives

To bring rigorous, formal logical thinking into programming.
To teach the techniques of *program derivation*: starting from a formal problem specification, develop a program solving the problem and the correctness proof of the program hand-in-hand.
To emphasize the importance of program correctness,
and provide another view on what *programming* is.

將嚴謹的、形式化的邏輯思考帶入程式設計中。訓練學生由問題的規格開始，一邊推導出解決該問題的程式，一邊做該程式為何正確的證明。由此培養對於程式正確性的要求、對於「程式設計是什麼」提出一個不同的觀點。

## Introduction

In the *imperative programming* paradigm, which many common programming languages such as C, Python, and Java belong to, programs are sequences of commands to be carried out by the computer. How to construct such programs and prove their correctness?

This course, **Imperative Program Construction**, is one of the **Programming Languages** series of courses. The series is not about learning any specific programming language, but about ways to construct programs to solve problems, the mathematical and logical foundations behind programming, and the roles of programming languages and formal methods. In this course where we discuss imperative programming, the points we want to make include:

  * A programming language is a formal language in which we think about programming with. We express ideas using the language, as well as verifying correctness of programs using the formal rules provided by the language.

  * "Programming" is much more than producing codes --- a huge part of the work is to make sure the code produced is correct. And the only way to ensure correctness is by proofs.

  * *Program Derivation*, which we will teach in this course, is a methodology in which we, starting from a program specification, derive a program and its correctness proof hand-in-hand.

  * Thinking about "how to prove this program correct" often provide useful hints on how a program can be constructed.

  * Programming is a mathematical activity.

  * *Separation logic* is a formal tool developed to reason about programs using pointers.

Concepts and tools we will cover in this course include:

  * Guarded Command Language of E. W. Dijkstra.
  * Propositional logic and first order logic.
  * Hoare Logic.
  * The "weakest precondition" predicate transformer.
  * Separation logic.

Many points made in the course echos that of another course, **Programming Languages: Functional Programming** (IM 5064). The two course can be taken separately, however. This course is also very related to **Software Specification and Verification** (IM 7079): both make use of concepts including propositional logic, Hoare Logic, predicate transformer, etc. IM7079 is more about verification, while this course emphasizes on derivation, meaning that there will be more manual calculation and solving specific algorithmic programs, and less discussion on topics such as semantics, concurrency, functional call, etc.

**Keywords**： imperative programming, program derivation, induction, proofs, logic.

「命令」(imperative) 程式語言意指把程式視為「給電腦一個個指令」的語言。我們常用的 C, Python, Java 等語言都可歸屬在此類別下。這類程式語言中，該怎麼寫程式、該怎麼證明程式的正確性？

本課程為「程式語言(Programming Languages)」系列課程之一，著眼點並不是教特定程式語言，而是討論設計程式解決問題的思考方式、設計程式使用的數學與邏輯基礎、以及程式語言與形式符號在其中扮演的角色。本課程以命令程式為主角，其核心概念包括：

 * 程式語言是一種形式語言，作為思考的工具。我們用程式語言表達概念，也用程式語言中的形式規則檢驗程式的正確性。

 * 「寫程式」不只是把程式碼生出來的動作 --- 我們還得確定程式是「對」的。而確定程式正確的唯一方法是證明。

 * 「程式推導」：由問題的規格開始，一邊推導出解決該問題的程式，一邊做該程式為何正確的證明。

 * 當我們不知一個程式該怎麼寫，「這個程式該怎麼證明」這件事可以反過來透露一些「這個程式該怎麼寫」的提示。

 * 「寫程式」是一個數學行為。

 * 為了討論使用指標的程式，我們發明了相對應的「分離邏輯」，藉以證明這類程式的正確性。

本課程將討論的具體工具包括

 * Dijkstra 的 Guarded Command Language.
 * 命題邏輯 (propositional logic)、一階邏輯 (first-order logic)
 * Hoare Logic.
 * The "weakest precondition" predicate transformer.
 * Separation logic.

本課程與「程式語言：函數程式設計」有可呼應之處，但兩者都可獨立修習。本課程亦與「軟體規格與驗證（Software Specification and Verification）」非常相關：命題邏輯、Hoare Logic, predicate transformer 等都是兩堂課共同的元素。該課程談驗證 (verification), 本課程則較注重推導(derivation)，有較多手動計算與演算法問題的推導，而不會嚴謹地談到語意、函數呼叫、concurrency 等課題。

**關鍵字**： 命令程設 imperative programming, 程式推導 program derivation, 歸納法 induction, 證明 proofs, 邏輯 logic.

## Grading

* No roll calls.
* Practicals/Exercises are not included in the final score --- do the exercise for the sake of learning.
* Two exams: mid-term, and final. The higher one constitute 60% of the final score, while the lower one consitute 40%. The percentage could be adjusted.

## Lecturer and Teaching Assistant

 * Lecturer：Shin-Cheng Mu 穆信成. scm [AT] iis.sinica.edu.tw

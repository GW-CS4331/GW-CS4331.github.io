---
layout: home
title: CS 4331/6331 Cryptography
---


## Instructor ##
Name: Arkady Yerukhimovich (He/Him)
Email: <a href="mailto:arkady@gwu.edu">arkady@gwu.edu</a>
Office: SEH4570
Office hours: TBD

## Course Information ##

Class time: Mondays 12:45-3:15pm
Class location: 1957 E St., Room 112
Textbook: Jonathan Katz, Yehuda Lindell: "Introduction to Modern Cryptography. Second Edition." CRC Press 2014. (Available for free through [GW libraries](https://wrlc-gwu.primo.exlibrisgroup.com/discovery/fulldisplay?context=L&vid=01WRLC_GWA:live&search_scope=DN_and_CI&isFrbr=true&tab=Everything&docid=alma99185917007604107).) 

> This course will introduce students to modern cryptography with a focus on formal definitions and provably secure constructions of cryptographic protocols. Topics covered will include secret-key and public-key encryption, message-authentication codes, digital signatures, and advanced topics. See syllabus for additional details.  This is a theoretical course and requires rigorous mathematical analysis, including deriving formal proofs, which will help you develop your on mathematical abstraction and problem solving skills. 



## Announcements ##
  - <b>This website is permanently under construction - all content subject to change!<b>

## Class Resources ##
  - [Piazza](https://piazza.com/gwu/fall2026/csci63314331) -- Used for questions and discussion
  - [Gradescope](https://www.gradescope.com/courses/1345729) -- Used for homework submission and grading
  - [Course Website]() -- Used to distribute lecture notes

## Tentative Schedule  ##

<div style="font-size:90%">

| Symmetric-Key Cryptography (Weeks 1-8) | Materials
| :--- |:---  |
| Introduction to Cryptography and Perfect Secrecy (Week 1) | |
| Computationally-Secure Encryption (Week 2)  |   |
| Proof by Reduction and Pseudorandom Generators (Week 3)   |  |
| CPA-Secure Encryption and Pseudorandom Functions  (Week 4)   | |
| Building CPA-Secure Encryption and Modes of Operation (Week 5)   | |
| Message Authentication Codes and CCA-Secure Encryption (Week 6)  |  |
| Authenticated Encryption and Hash Functions (Week 7)  |  |
| <br> <b> Exam 1 (Week 8) Oct. 16 </b> |   |

| Public-Key Cryptography (Weeks 9-15)  | Materials
| :--- |:---  |
|  Practical Constructions of Symmetric-Key Primitives (Week 9)   |  | 
|  Number Theory and Group Theory (Week 10)  | |
|  Cryptographic Hardness Assumptions and Key Exchange (Week 11)   | |
|  Public-Key Encryption (Week 12)  |  |
|  Digital Signatures (Week 13)   |  |
|  Advanced Topics and Research Workshop (Week 14)    | |
|  Exam Review (Week 15)   | |

| Final Exam   | Materials
| :--- |:---  |
| <b> Final Exam </b>    | Comprehensive but will focus primarily on material after Exam 1.|


<!--
| Symmetric-Key Cryptography (Weeks 1-8) | Materials
| :--- |:---  |
| Introduction to Cryptography and Perfect Secrecy (Week 1) <br><br>  | [Lecture 0 -- Course Information](lectures/lecture0.pdf) <br> [Lecture 1 -- Principles of Modern Cryptography](lectures/lecture1.pdf) <br> [Lecture 2 -- Probability Review and Perfectly-Secure Encryption](lectures/lecture2_marked.pdf) <br> [Quiz 1](quiz/quiz1.pdf)|
| Computationally-Secure Encryption (Week 2) <br>  <br>  |  [Lecture 3 -- Limitations of Perfect Secrecy and Computationally-Secure Encryptions](lectures/lecture3.pdf) |
| Proof by Reduction and Pseudorandom Generators (Week 3) <br>  <br>  | [Lecture 4 -- PRGs and Reductions](lectures/lecture4_marked.pdf) <br> [Lecture 5 -- Security of PRG+OTP](lectures/lecture5_marked.pdf) <br> [Quiz 2](quiz/quiz2.pdf) |
| CPA-Secure Encryption and Pseudorandom Functions  (Week 4) <br>  <br>  | [Lecture 6 -- Reductions Review and CPA-Secure Encryption](lectures/lecture6_marked.pdf) <br> [Lecture 7 -- Psuedorandom Functions](lectures/lecture7_marked.pdf) <br> [Quiz 3](quiz/quiz3.pdf)|
| Building CPA-Secure Encryption and Modes of Operation (Week 5) <br>  <br>  | [Lecture 8 -- Building CPA-Secure Encryption](lectures/lecture8_marked.pdf) <br> [Lecture 9 -- Proof of Security of PRF+OTP, Modes of Operations](lectures/lecture9_marked.pdf)|
| Message Authentication Codes and CCA-Secure Encryption (Week 6) <br>  <br>  | [Lecture 10 -- Padding Oracle Attack](lectures/lecture10_marked.pdf) <br> [Lecture 11 -- Message Authentication Codes](lectures/lecture11_marked.pdf) <br> [Quiz 4](quiz/quiz4.pdf) <br> [Quiz 5](quiz/quiz5.pdf) |
| Authenticated Encryption and Hash Functions (Week 7) <br>  <br>  | [Lecture 12 -- Authenticated Encryption](lectures/lecture12.pdf) <br> [Lecture 13 -- Hash Functions](lectures/lecture13_marked.pdf) |
| <br> <b> Exam 1 (Week 8) Oct. 16 </b> |  [Lecture 14 -- Exam Review](lectures/lecture14_marked.pdf) <br> All material on symmetric-key cryptography. |

| Public-Key Cryptography (Weeks 9-15)  | Materials
| :--- |:---  |
|  Practical Constructions of Symmetric-Key Primitives (Week 9) <br>  <br>   | [Lecture 15 -- Constructing Practical Block Ciphers (AES)](lectures/lecture15_marked.pdf)  <br> [Lecture 16 -- DES and constructing Hash Functions](lectures/lecture16_marked.pdf) | 
|  Number Theory and Group Theory (Week 10) <br>  <br>   |  [Lecture 17 -- Intro to Number Theory](lectures/lecture17_marked.pdf) <br> [Lecture 18 -- Intro to Group Theory](lectures/lecture18_marked.pdf) <br> [Quiz 6](quiz/quiz6.pdf) |
|  Cryptographic Hardness Assumptions and Key Exchange (Week 11) <br>  <br>   | [Lecture 19 -- Computational Hardness Assumptions](lectures/lecture19_marked.pdf) <br> [Lecture 20 -- Private-key crypto and Key-Exchange from Number Theoretic Assumptions](lectures/lecture20_marked.pdf)|
|  Public-Key Encryption (Week 12) <br>  <br>   | [Lecture 21 -- From Key Exchange to PKE](lectures/lecture21_marked.pdf) <br> [Lecture 22 -- El Gamal and RSA Encryption](lectures/lecture22_marked.pdf) <br> [Quiz 7](quiz/quiz7.pdf) |
|  Digital Signatures (Week 13) <br>  <br>   | [Lecture 23 -- Digital Signatures](lectures/lecture23_marked.pdf) <br> [Lecture 24 -- Signatures from Symmetric-key Primitives](lectures/lecture24_marked.pdf) <br> [Quiz 8](quiz/quiz8.pdf) |
|  Advanced Topics and Research Workshop (Week 14) <br>  <br>   | [Lecture 25 -- MPC](lectures/lecture25_marked.pdf) |
|  Exam Review (Week 15) <br>  <br>   | [Lecture 26 -- Final Review](lectures/lecture26--finalReview.pdf) <br> [Quiz 9](quiz/quiz9_marked.pdf)|

| Final Exam   | Materials
| :--- |:---  |
| <b> Final Exam </b>  Monday, December 16 -- 12:40-2:40  | Comprehensive but will focus primarily on material after Exam 1.|

-->
</div>

## Office Hours ##

TBD
All office hours will be held in my office -- SEH 4570.  

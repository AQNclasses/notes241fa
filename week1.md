Prof. Alexandra Nilles

Western Washington University

# 25 September

Welcome!

## Syllabus Review

- Learning Objectives
- Academic Integrity
- Course Structure
    - Labs
    - Homeworks
    - Exams
    - Final Project

## Fill out Info Sheet

By the end of this course, you will be experts at Git, Linux, and Java.

## Java

- Brief history of Java...
    - Most used programming languages (IEEE, 2024): https://spectrum.ieee.org/top-programming-languages-2024
    - Github, 2022: https://octoverse.github.com/2022/top-programming-languages
- Value semantics:

```java
int x = 5;
int y = x;
y = 17; // what is x? (it's still 5)
```

- Reference semantics:

```java
int[] a1 = {4, 15, 8};
int[] a2 = a1;
a2[0] = 7; // what is the first element of a1? (it's 7 !!)
```

- Why reference semantics?
    - Efficiency
    - Memory Usage
    - Copying objects
- What to watch out for: 
    - modifying objects in functions in other classes
    - assuming pass-by-reference for primitive types

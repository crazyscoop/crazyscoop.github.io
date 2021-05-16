---
title: Programming And Scripting Languages
author: Himanshu Singh
date: 2021-05-16 06:00:00 +0530
categories: [TIL]
tags: [Languages]
math: true
mermaid: true
image:
  src: https://cdn.jsdelivr.net/gh/cotes2020/chirpy-images/commons/devices-mockup.png
---

# Programming And Scripting Languages
We often use phrases like ***scripting in python*** and ***programming in java***, but is there any difference ?


Most people use the terms, programming and scripting synomously, but they do have different meanings.
> **All scripting languages are programming languages, all programming languages are not scripting languages.**

Simply said, scriting languages are a subset of all programming languages.

## Definition
A **programming language** is essentially a formal language that combines a set of instructions that can be fed into the computer to generate a specific output.
Example: Java, C, C++.

A **scripting language** is a programming language that supports scripts that are programs written exclusively for a special runtime environment to automate the execution of a specific action/function.
Example: Pyhton, JavaScript, Php.


## Differences
- The most notable difference between the two is in their execution – programming languages use a **compiler** to convert the high-level programming languages into machine language, on the other hand, scripting languages use an **interpreter**.
A compiler compiles a code in a complete chunk, an interpreter compiles a code line by line.
For example, in normal circumstances we complile code written in C before execution, whereas we don't need to compile JavaScript/Python code before running. 


- Programming Laguages are more often used to create something from scratch whereas Scripting langauges can be used to combined existing component or module.

- Programming languages are designed in such a way a developer can take full advantage of features of a language, whereas Scripting languages are designed to make coding faster and simpler.

- The compiled codes execute faster than the interpreted codes as they are changed into native machine program.  In a compiler, the overall code is analyzed just once in the whole cycle, and it submits the overall encountered errors. At the same, the interpreter analyzes the entire program every time and halts the execution if any error is encountered.

## Conclusion
Today, a difference between programming and scripting languages is becoming more and more blurry since compilation can be pretty fast modern hardware and compilation techniques. There is no reason that one cannot write a C interpreter and use it as a scripting language, and similarly, there is no reason that one can’t compile JavaScript to machine code and store it in an executable file.

## References
- https://www.educba.com/programming-vs-scripting
- https://stackoverflow.com/questions/17253545/scripting-language-vs-programming-language
- https://www.programmingeeks.com/scripting-vs-programming-languages/
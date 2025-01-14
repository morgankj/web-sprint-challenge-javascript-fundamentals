# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each.

    .map() Usually used for converting data, .map returns a new array and requires a return statement; anything in the return statement will be pushed to the new array. If you want to create a new array using an existing array of numbers that you want to be multiplied by 7, you can use .map to achieve this!
    .reduce() Reduce returns only a single value and requires 2 arguments, an accumulator (or a running total) and an item. The reduce method is handy if you need an average or sum of the items in your array.
    .filter() Filter returns a new array, checking each item to see if it passes your defined True/False statement. Filter also requires a return statement. You can use .filter to create a new array with odd numbers removed from your original array.

2. Explain the difference between a callback and a higher order function.

    A higher order function is one that takes another function as one of its arguments. A callback function is one that has been used as an argument inside of a higher order function.

3. Explain what a closure is.

    A closure is created when an inner function reaches outside of its scope for data. 

4. Describe the four principles of the 'this' keyword.

  1. Window Binding - this is an error - if you use "this" incorrectly, without giving it any context (so that no rules apply), it will reference the entire window (unless you are in strict mode, in which case "undefined" will be returned). 
  2. Implicit Binding - the most common use of "this," implicit binding refers to when it is used within a function and its context is direct and clear. When you invoke the function in question here, simply look to the left of dot before the function name to see what "this" will reference. 
  3. Explicit Binding - pass an object into one of the following 3 methods: "call," "apply," or "bind." The object passed in is what "this" will reference.
    call - immediately invokes the function, pass your arguments in 1 by 1
    apply - immediately invokes the function, pass your arguments in as an array
    bind - returns a new function that can be invoked at your leisure, pass your arguments in 1 by 1
  4. New Binding - you can use Constructor functions to create new objects in your data! In this case, "this" is used to refer to that individual new object.

5. Why do we need super() in an extended class?

    Super is the secret sauce in class functions that tells your function what attributes to pull from its parent function. Super performs what .call would perform in prototype syntax.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.


### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://lambdaschool.notion.site/lambdaschool/Lambda-School-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade

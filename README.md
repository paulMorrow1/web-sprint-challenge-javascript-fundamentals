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

The .filter method is used to iterate through an array and pull out everything that matches what is being looked for. It returns the items that match the search, into a new array.

The .map method is used to callback a function on every element in an array. .map iterates through an array, running the function on each element and returns a new array based off of the results. You do not want to use .map if you are not planning on using the array that it returns.

The .reduce method is used to take multiple sets of data, and return a single piece of data stored as a number. The .reduce method uses accumulation to iterate through the indexes, and adds the previous total to the current index, continuing the pattern until the end of the array. Then it returns the sum. You can set an initial value so that the function starts counting from 0, or whatever number you want to start from.

2. Explain the difference between a callback and a higher order function.

A callback function is a function that gets called on later in your code to execute a task.

A Higher Order Function is a function that can take a callback function as a parameter, so that it can access the function throughout your program.

3. Explain what a closure is.

A 'closure' is when a function reaches OUTSIDE of its' own scope to get data from a broader scope.

4. Describe the four principles of the 'this' keyword.

The first principle of the 'this' keyword is Window Binding. Window binding happens when we don't give the 'this' keyword anything to bind to. If there is nothing bound to the 'this' keyword, it is bound to the Window by default, or will return 'undefined'.

The second principle of 'this' is implicit binding. Implicit binding uses dot syntax on methods to access objects. When using implicit binding, whatever is to the left of the dot is the object 'this' is referring to, and to the right of the dot is the method.

The third principle of 'this' in explicit binding. In explicit binding, you call on the actual function and tell the function what the 'this' keyword is. There are three methods, .call(), .apply(), and .bind(). The .call() method will invoke your function and you add your parameters. The .apply() method will invoke the function and you will pass in your parameters as an array. Lastly, with the .bind() method you pass in your arguments, but the function does not run. It will save a new function that you can invoke later.

The fourth principle of the 'this' keyword is New binding. New binding is when a function is invoked with the 'New' keyword before the function name, which allows the 'this' keyword to be bound to the new object that is being created inside the function.

5. Why do we need super() in an extended class?

We need to use super() in an extended class because that is what is allowing us to access the keys from the Parent Class.

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

[Sprint Challenge Study Guide](https://www.notion.so/bloomtech/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://notion.so.bloomtech.BloomTech-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade

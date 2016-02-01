---
---
# HW 2 Simple Functions in Java
This week's homework includes reading and a simple coding exercise.

## Goals:

- Practice with command line projects in InteliJ
- Learn basic Java syntax for functions, including parameters and return values
- Work with static functions
- Work with primitive types in Java
- Version the project in GitHub

## Reading & End of Chapter Exercises
Before beginning, you’ll want to read through (or review) Chapters 1 through 3 in your textbook. These chapters introduce basic Java language syntax for how to use program control and logic structures. We will use these throughout the semester, but will not be spending a lot of time on them in class.  It is assumed you already have a foundation in at least one other programming language and have worked with these basic program control and logic structures before.

Pay attention to the primitive data types introduced in Chapter 2 and compare this information from the lecture.

As you complete each chapter, work through the Self Test Exercises at the end of each Chapter to measure what you have learned. The answers are in Appendix A at the back of the book, so you can evaluate and correct your work when you are done. If you have questions on anything covered, please ask. The class chat room will be an excellent spot to discuss these.

## GitHub Info
Repository:  https://github.com/htc-ccis2595/simple-functions

You need to fork this repository and submit a pull request to turn in the assignment.  Please post a screenshot of the pull request to the D2L dropbox.  The dropbox is mainly used to communicate due dates, not for storing the completed work.  You do not need to upload the project to D2L, only to GitHub.

## Homework 2 - Pet Age Functions
We will calculate the equivalent human ages of cats and dogs.

Use InteliJ to create a new project called simple-java-functions in the spot where you clone the GitHub Repository.

Use the Command Line template to make a basic "Main" class with a main function.  Create two additional functions as indicated below. These functions must be __static__ functions, just like main.  Inside the main function you will use these functions to calculate some pet human ages.

### Dog Human Age
Make a static function called "calculateDogHumanAge" that:
 - takes a single input parameter (that might be a decimal)
 - returns the human age

For the first two years, a dog year is equal to 10.5 human years.
After that, each dog year equals 4 human years.

FYI: This calculation is based on studies that indicate dogs, except maybe larger breeds, develop more quickly in the first two years of life.

### Cat Human Age
Make a static function called "calculateCatHumanAge" that:
 - takes a single input parameter (that might be a decimal)
 - returns the human age

A one year old, a cat is roughly equal to a 15 year old human.
At two years, a cat is roughly equal to a 25 year old human.
After that, each cat year equals about 4 human years.  So a 3 year old cat is 29, and a 4 year old cat is 33.

### Main method
Use each of the above functions in your main method.  Call them 3-4 times with different values and print friendly messages to the output that show both the pet age and their human age.  Make sure to check your calculation results to show that the functions work.

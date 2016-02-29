---
---
# HW 6 Inheritance and Interfaces in Java
This week's homework includes reading and a simple coding exercise.

## Reading & End of Chapter Exercises
Before beginning, you’ll want to read through (or review) Chapter 8 in your textbook.

As you complete each chapter, work through the Self Test Exercises at the end of each Chapter to measure what you have learned. The answers are in Appendix A at the back of the book, so you can evaluate and correct your work when you are done. If you have questions on anything covered, please ask. The class chat room will be an excellent spot to discuss these, but will only be as interesting as you make it.

## GitHub Info
Repository:  https://github.com/htc-ccis2595/pet-classes

You need to fork this repository and submit a pull request to turn in the assignment.  

This repository was used for last weeks in-class exercise. If you already have a fork/clone of this repository, you do not need to fork it again.  You should however use `git pull` to pick up any changes.  

## HW Week 6
This week we're going to add to our Pet classes by adding a turtle class and a Audible interface. It'd be great I'm sure to have real sound here, but alas we will "print" sounds to the console.

### Turtle
Add a new sub-class of Pet called Turtle.  Turtle age in human years is a tough issue because there are so many types of turtles and they can age very differently.  However, we'll go with the following rule:

- A turtle is 15 in human years after its first year. And then 25 years old when it's 2, and then it adds on four every year.

### Audible
Add an Interface called Audible that supports 1 method called makeSound. It should not take any arguments (input parameters) and should not return a value.  It should just print an appropriate sound to the console, i.e. "Woof", or "Meow".  

Since Cats and Dogs "speak" or make noises, they will implement this interface.  While some types of turtles do make some noises (no, Cowabunga does not count), we will stick with the generally accepted turtles can't "hear" and thus don't "speak" or make meaningful sounds theory.

### Update Main
Update the main program output to create a few (more than one) instance of the Turtle class and add them to our list of Pets.

Iterate (loop through) the list of Pets and if the pet can make noise (use the `instanceof` keyword to check) have the pet make a noise.  If the Pet cannot make a noise, print a message to the console saying the pet's name and that it is silent. For example: "Raphael is silent."  


## Test and Submit your work
Make sure to look at your program output and check that things are displaying as you expect.  Make sure to verify the code for your turtle human age calculations.  Also check that Cats and Dogs are making sounds while turtles are silent.

When complete, push your changes to GitHub and create a pull request for your work.  Place a screen-shot of that pull request in the dropbox.

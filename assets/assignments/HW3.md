---
---
# HW 3 Simple Classes in Java
This week's homework includes reading and a simple coding exercise.

## Goals:

- Create an InteliJ project from existing source code
- Learn basic Java syntax for classes, including instance variables and methods
- Practice encapsulation by using private instance variables with getter and setter functions
- Working with arrays of objects


## Reading & End of Chapter Exercises
Before beginning, you’ll want to read through (or review) Chapters 4 and 5 in your textbook. These chapters introduce basic Java classes.  Chapter 4 introduces how you can write your own classes and Chapter 5 discusses some built-in classes, including Strings and arrays.

As you complete each chapter, work through the Self Test Exercises at the end of each Chapter to measure what you have learned. The answers are in Appendix A at the back of the book, so you can evaluate and correct your work when you are done. If you have questions on anything covered, please ask. The class chat room will be an excellent spot to discuss these, but will only be as interesting as you make it.

Chapter 5 includes an example of Bubble Sort.  If this is not familiar to you, it may help to watch a video explanation.

<iframe width="560" height="315" src="https://www.youtube.com/embed/8Kp-8OGwphY" frameborder="0" allowfullscreen></iframe>

Thanks to [Harvard's CS50](https://www.youtube.com/channel/UCcabW7890RKJzL968QWEykA) class for the video!


## GitHub Info
Repository:  https://github.com/htc-ccis2595/simple-classes

You need to fork this repository and submit a pull request to turn in the assignment.  Please post a screenshot of the pull request to the D2L dropbox.  The dropbox is mainly used to communicate due dates, not for storing the completed work.  You do not need to upload the project to D2L, only to GitHub.

## Homework 3 - Cat and Dog classes
Use InteliJ to create a new project called simple-classes in the spot where you clone the GitHub Repository.  You may be prompted to create a project from existing sources.  If so, answer Yes.

Take a look at the code that you are provided.  There are three classes inside the edu.htc.pets package folder inside of src.  You will update these java files as indicated below.

### Cat Class
Update the Cat class to have the following private *instance variables*:

 - name
 - age

Add get and set functions for both the name and age.  (i.e. getName/setName and getAge/setAge)  

Add a getHumanAge function, that uses the calculation you worked out last week. Unlike your function from last week, this *method* should __NOT__ require any input, as the Cat object is already aware of its own age.  Use the age instance variable in the calculation, and return the equivalent human age.

### Dog Class
Update the Dog class to have the following private *instance variables*:

 - name
 - age

Add a constructor that requires a name.

Add get and set functions for both the name and age.  (i.e. getName/setName and getAge/setAge)

Add a getHumanAge function, that uses the calculation you worked out last week. Like the method for the Cat class above, this *method* should __NOT__ require any input, as the Dog object is already aware of its own age.  Use the age instance variable in the calculation, and return the equivalent human age.

### Main Program
In your Main class's main method, you will create 3 cats and 3 dogs, put them into an array and use a loop to display information about each animal.  Note that I want you to use a different loop for the cats and the dogs

#### Cat code
Let's start with the cats.

1. Create an empty array to hold the Cat objects you will create.
2. Create a cat, setting it's name and age, then add it to the array.
3. Create two more cats, also setting their names and ages, then add each of them to the array.
4. Print a message to say you are displaying the cat information.
5. Set up a regular __for__ loop with a counter to go through the cat array and print the cat's name, age, and then human age. Use nice messages so we can tell what you are printing.

#### Dog code
Now it's time for the dogs.

1. Create an empty array to hold the Dog objects you will create.
2. Create a dog, setting it's name and age, then add it to the array.
3. Create two more dogs, also setting their names and ages, then add each of them to the array.
4. Print a message to say you are displaying the dog information.
5. Set up a __for-each__ or an enhanced for loop to go through the dog array and print the dog's name, age, and then human age. Use nice messages so we can tell what you are printing.

### Code Questions
Answer the following questions using comments in your code.  Write code to show that you tried to do these things (comment it out if it doesn't compile). Use comments to explain what you found.

1. Can you create a Cat without a name?
2. Can you create a Dog without giving it a name?  
3. What happens if you try to put a dog in the cat array?  Does it compile?  Does the code run?
4. What does a Cat or Dog object look like if you print it?  (Extra: Can you figure out how to make it print pretty?)


## Test and Submit your work
Make sure to look at your program output and check that you are calculating the correct human ages, and while it sounds silly, look that you are in fact seeing the names and ages that you expect based on the values that you set.

When complete, push your changes to GitHub and create a pull request for your work.  Place a screen-shot of that pull request in the dropbox.

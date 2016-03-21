---
---
# HW 8 File I/O
This week's homework introduces File I/O and Java's new try-with-resources.

## Reading & End of Chapter Exercises
Before beginning, you’ll want to read through (or review) Chapter 10 in your textbook.

As you complete each chapter, work through the Self Test Exercises at the end of each Chapter to measure what you have learned. The answers are in Appendix A at the back of the book, so you can evaluate and correct your work when you are done. If you have questions on anything covered, please ask. The class chat room will be an excellent spot to discuss these, but will only be as interesting as you make it.

## GitHub Info
Repository:  [https://github.com/htc-ccis2595/file-read-write](https://github.com/htc-ccis2595/file-read-write)

You need to fork this repository and submit a pull request to turn in the assignment.  Please post a screenshot of the pull request to the D2L dropbox.  The dropbox is mainly used to communicate due dates, not for storing the completed work.  You do not need to upload the project to D2L, only to GitHub.

## File I/O and the IDE
Working with File I/O can be a little troublesome when using IDEs as they can alter your working directory.  Because of this, you need to be careful with where and how you look up files.  It is generally easier to find a file reliably by using the classpath.  There is sample code for you in this project that shows how to do that.

### FileParser
Complete the code in the FileParser class so that the file is read line by line.  Trim each line and if it is not empty, add the line to an ArrayList to return.

### ListFileWriter
Complete the code in the ListFileWriter class so that it will write each non-empty item from the ArrayList to the file at the path specified. Make sure you do not write empty lines.

### Main
Once you have both classes completed and the tests in the main methods show no errors, update the Main class so that it reads the sampleData into an ArrayList by using the FileParser class, and then use the ListFileWriter to write that into a new file.


## Test and Submit your work
Make sure to look at your final program output and check that things are displaying as you expect. Re-run the main methods in each class to ensure that they show no errors.

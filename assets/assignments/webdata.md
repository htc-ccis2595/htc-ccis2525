---
---
# Project 3 - Web Data Project
This project started with last week's [Homework 9](http://htc-ccis2595.github.io/assets/assignments/HW9.html).

## GitHub Info
Repository:  [https://github.com/htc-ccis2595/web-data-project](https://github.com/htc-ccis2595/web-data-project)

You need to fork this repository and submit a pull request to turn in the assignment.  Please post a screenshot of the pull request to the D2L dropbox.  The dropbox is mainly used to communicate due dates, not for storing the completed work.  You do not need to upload the project to D2L, only to GitHub.

## Data classes (From HW 9)
You should set up get/set methods for the properties of each of these classes and test making some objects.

For the properties which are lists, it is helpful to add a method to your class to add an item to the list.  
For example in the Game class, add a method called addTag(String tag) so that you can easily add one tag to the Game.

### Game Class
In class we designed a Game with the following properties:

- Name
- Release Date (will be just the year)
- Platform (use a String, will be like PC or Playstation or XBox)
- List of Tags (words like genres/types, single/multiplay, awards, subscriptions)
- Average Rating
- List of Reviews


### Review Class
We designed a Review with the following properties:

- Star Rating - 1 to 5, no half stars
- Reviewer
- Game
- Comments - The text of the review
- Date - use java.util.Date class


### Reviewer Class
We designed the Reviewer class with the following properties:

- UserName (screen name or user name)
- Name (actual name - optional)
- Age
- Gender
- Comments/Profile - whatever text they want to share
- List of Favorite Games
- Password


### InvalidDataException
We will add a custom Exception to indicate that invalid data was found.  This should be used as appropriate in the setter methods for each class.  For example, in the Game class we have a star rating that should have a value of 0-5.  (Zero indicates it is not set.)  If the set method is called with a value outside of that range, then the InvalidDataException should be thrown.

### Validation method
Before saving data to the database, it is important to make sure all our valid fields are set.  If not, then we shouldn't save the data and need to give an error back to the user.  To check that the required fields on our object have been set, we will add a validate method to each class.  This method should return true if all required fields on the object have a valid value, and false if they do not.  (The error to the user will be handled elsewhere.)

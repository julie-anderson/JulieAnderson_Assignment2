# JulieAnderson_Assignment2

Julie Anderson File Created 10/9/16 

Assignment 2
CIS-395: Programming for the Web

Build a simple, static note-taking site using Node.js, Express framework and bootstrap and
deploy to AWS. This will be a starting point for Assignment 4.

Screen 1: Login

Create a login page with Username and Password. Assume that a button click to login is always
successful and leads to the second screen.

Screen 2: List of Notes

This is simply a list of notes.js. You should have at least 10 note names that link to the third page (all the
same link). When the screen is made small enough that the whole list cannot fit onto the page, the list
overflow should be scrollable
Finally, there should be a button to add a new note (this can also just lead to the third screen).

Problem 3: Note Editor

This screen will have a large, editable title at the top of the page. It will have 2 buttons, SAVE and
DELETE. When these buttons are clicked, a pop up message will show the used that this was successful
(even though they do not call back to the server yet).
The bulk of the screen will be a large, editable text area.

Logging
Whenever one of these routes is called, you should log that the request was received and server the
page.

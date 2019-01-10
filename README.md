# hack-a-thing-1-pulsebot
hack-a-thing-1-pulsebot created by GitHub Classroom

### Project
This project is a survey bot that automatically fills out pulse surveys.  The goal of
this project was to create a bot that not only filled out surveys on an automated loop,
but also did so in a way that simulated human activity.  To do this the bot has built in sleep
timers that simulate pausing to consider before answering.  The bot also has a small amount 
of language parsing capabilities so that it can determine the range that a number should sit in 
if the input is supposed to be numerical.

### Learned Skills
Over the course of this project I learned how to use selenium with python.  
I also learned about automating web interactions as this was something I had 
never attempted before.  Finally, although I was familiar with HTML, I had never 
had to examine the HTML of web pages and determine how I would select them from 
the view point of a program.

### What still needs Work
Through my test I found two issues that still require work.  First, since the 
Dartmouth login page that pulse redirects to for logging in has no HTML hooks that 
I could find for the login box, that part still has to be done manually.  Also if there 
are a very large amount of options to choose from, selecting the next button does not move the
screen along.  The program then gets stuck in a loop.  I did however verify that this is not an issue
with the program but seems to be a bug in the pulse website itself.

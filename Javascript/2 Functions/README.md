Here's an explanation of what I've learned while creating this Rock, Paper, Scissor program. See the in-program comments for more specific information about the different logical paths that are taken.
var is Javascripts way of indicating that you're making a new variable. It's followed by the variable name and then a single equals sign that is for the variable's value. In this program's case, the first variable is entered by the user with the same "prompt" command that we saw in Javascript section 1. Console.log, as we saw in the last section, prints out a statement in quotes OR a variable name w/o quotes. Math.random() is a neat command! It randomly creates a number from 0, up to 1 ... 1 isn't an option, so it's actually 0 - 0.99. The random number is later used to select the computer's choice. 
This program is my first usage of "else if". Else if comes between if and else and I think you can have as many "else if"s in between as you'd like ... some brief reading on Stack Overflow suggests this is the case. I use if, else if, else to make <0.34 = "rock", <= 0.67 = "paper" and the final else doesn't need any condition because all that's left is >0.67. Now that we've got the user's and the robot's choice, we need to determine who won and we can do that with more if/else statements and a new Javascript feature called function.
The Javascript function that I've labeled as compare takes the computer and user's choices and runs through the logic of figuring out who won. This was my favorite part of the program because it required a whiteboard to make sure all choice options were covered and showed me how I didn't have to take everything into account once I've already covered an option from before, like when I didn't have to use a conditional for >0.67 for the computer's selection. 
I'll go into more detail about the choice paths inside the program w/ my comments there becase it'll get too confusing to do that here w/o the code right next to it. 
I will mention the return command, which takes the result of the inner code block and serves it up to the function's call. Also, note that the compare function gets called by the end of the program, where it says "compare(userChoice, computerChoice)





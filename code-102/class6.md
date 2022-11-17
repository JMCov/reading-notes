# Intro to JavaScript

**JavaScript** is a compiled programming language with first class functions. It is the most well known scripting language for web pages.

## Input/Output

There is a number of differesnt ways that JavaScript can display text for the user.

1. **Alert** is a function called by using the `alert()` command. Inside the parenthesis you can type anything you want inside a pair of double quotes to make a popup occur on your website for users to see.

2. **document.write** is a function called by `document.write()`. Like Alert you will put what you want to say in the parenthesis with double quotes. document.write is mainly for changing what is displayed on a web page given user input by placing a variable in the function call.

3. **console.log** is a function called by `console.log()`. Like the 2 previous examples what is displayed depends on what is in the parenthesis.  This function is used by developers to assist them in debugging code. Web page users will not see the output from this function.

Two ways to receive input from users are:

1. **prompt** is a function called by `prompt()`. Inside the parenthesis you can type a message such as what is your name? the prompt function will save the input inside a variable that the developer codes. `var name = prompt("What is your name?)` This would store whatever the user inputs inside a variable named name. The developer could then use this variable to output the user's name inside other functions.

2. **confirm** is a function called by `confirm()`. The function will show a pop up with a message input by the developer inside the parenthesis. The user will see the text and be given an option OK or Cancel. If the user selects OK the confirm function returns true, if Cancel is selected the function returns false. The developer can create condidtional statements to decide what the code will do give input of true or false.

## Variables

**Variables** are containers for storing data.

A developer's declare variables by using `var`, `let`, `const` or using no syntax at all which is considered a bad practice.

Ex.  `var x = 10` `var y = 2` `var z = x * y`

The given output if a developer calls `document.write(z)` would be 20

This is just the tip of the iceberg of how variables can be used to store numbers, words, boolean logic, and more.

[Back to Home](../README.md)

---
tags: cssi, javascript
level: 1
languages: javascript
---
#Intro to Javascript and the Developer Console
After the lesson, you'll be able to:
+ Understand and define key programming concepts
+ Use the JS console
+ Understand the console is for testing, does not permanently store code
+ Use arithmetic operators in console
+ Use and concatenate strings in console

##Why JavaScript?

JavaScript was introduced in 1995 as a way to add interactivity to web pages in
the Netscape Navigator browser. The language has since been adopted by all
other major graphical web browsers. JavaScript has made modern web applications
possible — applications with which a user can interact with, without doing a
page reload for every action. JavaScript is also used in more traditional
websites to provide various forms of interactivity and cleverness.

It is important to note that JavaScript has almost nothing to do with the
programming language named Java. The similar name was inspired by marketing
considerations, rather than good judgment. When JavaScript was being
introduced, the Java language was being heavily marketed and was gaining
popularity. Someone thought it was a good idea to try to ride along on this
success. Now we are stuck with the name




##Using the Console

You can experiment with Javascript in the Javascript Console. The console is a way to test small bits of Javascript code.

To get to the console, open a web broswer (Chrome for example), and navigate to any webpage.  Press <kbd>command</kbd> + <kbd>option</kbd> + <kbd>J</kbd>

This gives you an area down at the bottom of the screen, called the console. The ">" symbol is called the prompt, where you can type JavaScript code.


##Math Interpretation
Try typing these lines, pressing enter after each one:
```
>4
>2+3
>2*3
```
Note that your friend the interpreter mostly just repeats what you say, but evaluates mathematical expressions. JavaScript performs basic math as you would expect, with the operators +, -, /, *.  A less familiar operator is %, or modulo. See if you figure out what modulo does.

```
> 10 % 5
```
```
> 11 % 5
```
```
> 13 % 5
```
```
> 16 % 5
```

```
> 23 % 16
```

Here are some other mathematical operators:

| operator 	| name      	| description    	| usage         	|
|----------	|-----------	|----------------	|---------------	|
| -        	| negation  	| subtracts      	| 3 - 2 = 1     	|
| +        	| plus      	| adds           	| 3 + 2 = 5     	|
| *        	| multiply  	| multiplies     	| 3 * 2 = 6     	|
| /        	| divide    	| divides        	| 12 / 3 = 4    	|
| %        	| modulus   	| remainder      	| 12 % 5 = 2    	|
| ++       	| increment 	| increases by 1 	| x=1; x++; x=2 	|
| --       	| decrement 	| decreases by 1 	| x=1; x--; x=0   |


##String Interpretation
So now  we know we can do math in the JavaScript console. The interpreter will react to pieces of text, too. In programming bits of text are called "strings".  

```
>"my string"
```
Note that you have to put text inside quotes before the interpreter can understand them. Anything between quotes is called a string.

Now try adding two strings together:
```
>"first name" + " last name"
```

Combining strings with the + operator is called concatenation.

JavaScript uses + symbol for math when it is operating on numbers, but when it sees strings, it will concatenate (link together) the text.

Let’s test this. Try entering these three different expressions:
```
>1 + 1
>”1” + “1”
>”1” + 1
```


1 + 1 is a mathematical expression adding two numbers, while “1” + “1” is an expression concatenating two strings of the character 1. If you try to add a string and a number, both pieces are treated as strings and concatenated into a bigger string.

##Rerunning JavaScript Code
To rerun a command, you can hit the <kbd>↑</kbd> key on your keyboard and scroll through all of the previous commands. When you find the command you want to rerun, just hit <kbd>enter</kbd>.




Your code and results will only remain in the console until the page is refreshed. These commands are not saved. Think of the console as a place to test ideas quickly, not a place to build something that will endure for the ages.

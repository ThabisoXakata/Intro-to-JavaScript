# Intro-to-JavaScript

## Week 1
Introduction to Javascript
## What is Javascrpt?
A scripting languagethat allows web developers to implement interactivesness and very complex features on web pages. When you see web animations, interactive maps, infinite scrolls amongst many other things, we can bet that there is some involvement of Javascript.
<br><br>javascript acts as the third layer of standard web techgnologies after HTML and CSS.<br><br>
## Variables
Javascript has containers, known as variables that must be declared and used to store data that you will refer to at some point in your web programme. Javascript variables can be declare in 5 ways:
- var            - Refers to the container being declared/created to store specific information.
- let            - Also a variable declaration, difference is that "let" is block-scoped and a local variable 
- const          - Declares block-scoped local variables, difference is that the value of a constant can/does not change. A constant is an object that has properties that can only be added, updated and/or removed.
- automatically  - Declares global variables that can be accessed anywhere at anytime in the program. i.e, if we forget to type "var, let, and const" javascript will declare it automatically and assign the type of content stored on the that variable.

## Javascript Operators


Operators are used to assign values and compare values, perform calculations and arithmetic operations and many more other things.Types of Operations:
<ul>
  <li>Arithmetic Operators</li>
  <li>Assignment Operators</li>
  <li>Comparison Operators</li>
  <li>Logical Operators</li>
  <li>Conditional Operators</li>
  <li>Type Operators</li>
</ul>
Examples of Arithmetic Operators: <br>

```
Given that y = 5

+	Addition	          x  = y + 2	  y=5, x=7	
-	Subtraction	        x = y - 2	    y=5, x=3	
*	Multiplication	    x = y * 2	    y=5, x=10	
**	Exponentiation	  x = y** 2	    y=5, x=25	
/	Division	          x = y / 2	    y=5, x=2.5	
%	Remainder	          x = y % 2	    y=5, x=1	
++	Pre increment	    x = ++y	      y=6, x=6	
++	Post increment	  x = y++	      y=6, x=5	
--	Pre decrement	    x = --y	      y=4, x=4	
--	Post decrement	  x = y--	      y=4, x=5	
```
Examples of Assignment Operators: <br>
```
Given that x = 10 and y = 5

=          x = y	    x = y	        x = 5	
+=	       x += y	    x = x + y	    x = 15	
-=	       x -= y	    x = x - y    	x = 5	
*=	       x *= y    	x = x * y    	x = 50	
/=	       x /= y    	x = x / y	    x = 2	
%=	       x %= y	    x = x % y	    x = 0	
:	         x: 45	    size.x = 45	  x = 45	

```
## Strings
A string is a sequence of mutliple characters(letters, numbers, and symbols). String objects are used to hold data/information that is represented in a form of a text. Strings are one of the most fundamental concepts of programming to be familiar with, because humans and computers communicate through text. String objects can be manipulated to check the "length" of a string, can be concatenated using the "+" and "+=" string operators.

## Functions
Refers to a a group of fully reusable codes(Set of statements) that perform specific tasks when called. Note, a function can be called anywhere in your program. Examples of functions include "alert()", write().
- To use function in Javascript, we first need to define them, then call them where ever and whenever we need them. We use function to eliminate the need to write the same complex code over and over again.

### Function Definition
- To define a function, we use the "function" keyword, followed by the function name to identify it, then we list the parameters that are going to be inside that function and a statement block surrounded by curly braces"{}".

### Global Scope and Functions
- Determines how we access variables, objects, and functions from different parts of the code. Variables that have been defined outside of a function block, declared without let and/or const get automatically created in the global scope. This means, they can be seen everywhere in your JavaScript code. The reason why we promote the declaration of variables to be done using "let" or "const" is because if that is not done, it can cause unintended consequences elsewhere in your code or when running that specific function again.

Local Scope- Variables which are declared within a function, as well as the function parameters, have local scope. When you declare variables within a function's parameters, they are only visible and can be accessed within that function.

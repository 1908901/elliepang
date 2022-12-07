---
toc: true
layout: post
description: A minimal example of using markdown with fastpages.
categories: [markdown]
title:  Vocab 
---
# Fundamental Vocab Definitions 
|Topic|Hacks|
|-|-|
|Unit 3.1-3.2|[Hacks](https://1908901.github.io/elliepang/collegeboard/2022/11/29/hacks-for-3.2.html)|
|Unit 3.3-3.4|[Hacks](https://haeryny.github.io/trimester2group/)|
|Unit 3.5-3.7|[Hacks](https://github.com/MuffinMan1287/BARN/issues/5#issuecomment-1336691548)|
|Unit 3.8-3.10|[Hacks](https://1908901.github.io/elliepang/2022/12/06/hacks.html)|

Unit 2… Binary/Data Terms
bits: the minimum unit of binary information stored in a computer system. A bit can have only two states, on or off, which are commonly represented as ones and zeros. In our binary markdown we used to change the number of bits.

bytes: A group of eight bits put together is known as a byte. A byte consists of 256 different combinations if you include the number 00000000 — all the binary numbers between 00000000 and 11111111.

hexadecimal/nibbles: Hexadecimal is a numbering system with base 16. It can be used to represent large numbers with fewer digits. In this system there are 16 symbols or possible digit values from 0 to 9, followed by six alphabetic characters -- A, B, C, D, E and F. For example, when we use Javascript to change the color of the background on our blogs, we use hexadecimals like #eb4034, which would give us a red color. 

RGB- Hexadecimal is basically a short code for RGB color, they are simply different ways of communicating the same thing – a red, green, and blue color value. For example, (235, 64, 52) is the RGB for RED. Here's an example of how it is implemented in our fastpages:
a { color: rgb(255,255, 255) !important; }

boolean- value that is either true or false

Unit 3… Algorithm/Programming Terms

variables- A variable is an abstraction inside a program that can hold a value. Each variable has associated data storage that represents one value at a time, but that value can be a list or other collection that in turn contains multiple values. Using meaningful variable names helps with readability of program code and understanding of what values are represented by the variables. Some programming languages provide types to represent data, which are referenced using variables.

data types- integer, string, float, boolean, lists, dictionaries, arrays, etc.
lists- Lists are used to store multiple items in a single variable.

dictionaries- A dictionary consists of a collection of key-value pairs. Each key-value pair maps the key to its associated value.

A plus sign indicates addition: a + b

A subtraction sign indicates subtraction: a - b

An asterisk/star indicates multiplication: a * b

A slash indicates division: a / b

MOD represent the Modulus operator. Returns the value after division: a MOD b

algorithms- finite set of instructions that accomplish a specific task, composed of sequencing, selection, and iteration.

sequence- a section of code is run only if a condition is met. (ex: if statements)

selection- repeating steps or instructions over and over again (ex: loops)

iteration- outline or set of steps that we do and follow in order that they are given

strings- a sequence of characters

concatenation- combines two or more strings into one

length- len function finds the number of characters in a string

substring- a part of a existing string

upper- upper() method returns the uppercase string from the given string. It converts all lowercase characters to uppercase.

lower- lower() method returns the lowercase string from the given string. It converts all uppercase characters to lowercase.

comparison operators- Logical operators allow for boolean values to be evaluated. Pseudocode uses the logical operators NOT, AND, and OR.

Truth tables- A truth table is a way of summarizing and checking the logic of a circuit. The table shows all possible combinations of inputs and, for each combination, the output that the circuit will produce.

if statement- will go through certain statements if the if expression is true

if-else- will go through a statement no matter what, but the statement which is run depends on the if expression is true or false

elif- elif is short for "else if" and is used when the first if statement isn't true, but you want to check for another condition. Meaning, if statements pair up with elif and else statements to perform a series of checks.

nested selection statements- Nested selection structures are used when more than one decision must be made before carrying out a task. Nesting is a programming activity, in which one program block is placed inside other program block of the same operation type. Nesting processes are mostly used implemented in the selection control structures.

For Loop: repeats a function for a set number of times; I is the number of times repeated. With the for loop we can execute a set of statements, once for each item in a list, tuple, set etc.

While Loop: the while loop is used to repeat a section of code an unknown number of times until a specific condition is met. A while loop will execute a set of statements as long as a condition is true.

return values: The value that a function returns to the caller is generally known as the function's return value. All Python functions have a return value, either explicit or implicit.

class- A class creates a new local namespace where all its attributes are defined. Attributes may be data or functions. Like function definitions begin with the def keyword in Python, class definitions begin with a class keyword.

parameters- Parameters are the variables that appear between the brackets in the "def" line of a Python function definition.

procedural abstraction- One good use of a procedure is to eliminate duplicate code. In addition to improving the readability of the app, the use of a procedure will make it easier to modify that chunk of code because it only occurs once in the program. Use of parameters and complexity.

# APCSP Week 1 Notes 

- In class we learned how to use bash and python such as python functions if/else statements and variables. 
- We learned about keys and that bash can make scripts with terminal/shell. 
- Static Text do not change.
- Output in Jupyter Notebook is under the code cell. It will vary based on development intentions and tools.
- Sequence of code: two or more lines forms a sequence.
- "Msg": parameter to print command, causing input to be output to terminal.
- Procedural abstraction: grouping a sequence of commands.

---
layout: page
toc: false
title: "Coding Intro"
indent: 0
number: 2
icon: fa-solid fa-code
---

## Statements

Computer programs are made by writing a sequence of commands for the computer to execute.  These commands are called *instructions* or *statements*.

<img src="{% link media/code.png %}">

The computer processing chip (called a *microcontroller*) executes these instructions in sequence.  It can execute instructions VERY fast (up to 240 million per second), so even if you write several instructions in a sequence, it will execute them so fast it will appear to you that they execute instantly and all at the same time.

<img src="{% link media/semicolons.png %}">

**Important:** See how each statement ends with a semicolon?  This is *required* to indicate the end of a statement.  DON'T FORGET TO ADD THESE OR YOUR CODE WON'T RUN!

## Comments
Sometimes we want to tell the computer to ignore certain statements.  We can do this by adding `//` in front of any lines of code we want to disable. This is called a **comment**. 

For example in the code below, we comment out the second statement so that now only LED1 and LED17 turns on (and LED13 does not).  The editor helps you remember that this code is commented out by turning it green.

<img src="{% link media/comments1.png %}">

Comments are also used to add personal messages to your code.  This is done to help you remember what your code is supposed to do.  It also helps others who look at your code to understand it.  Here is an example:

<img src="{% link media/comments2.png %}">


The editor will automatically comment or uncomment code for you if you put your cursor on the line and press `Ctrl + /`

## Functions and Braces
Sometimes it is helpful to group together code statements into blocks of code that you can run in one easy step.  Grouping the statements together is like creating a *recipe* of directions.  This is called a **function**.

The code below shows two different functions (`turnOnLEDs` and `turnOffLEDs`) that turn on or off the first three LEDs.  Functions start with an open brace `{` and end with a close brace `}`.  All of the instructions within the braces make up the recipe of the function.

<img src="{% link media/functions.png %}" hspace="5%" width="500">

You can run the function recipe by **calling** a function.  This is done by writing a statement with the function name followed by parenthesis `()`. In the above code, the statements at <span style="color:green">**1**</span> and <span style="color:green">**5**</span> run the `turnOnLEDs` function to turn on the three LEDs.  The statement at <span style="color:red">**3**</span> runs the `turnOffLEDs` function to turn off the three LEDs. 

Using functions helps us organize our code to make it easier to understand.  It also allows us to *reuse* code, by calling the same recipe of instructions multiple times.  



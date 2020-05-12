# IT1600 Final Project
## By Amelia McEntire
 A tutorial for drawing a heart with a Python turtle.
 The audience for this tutorial is beginning programmers who already have some familiarity with how to code. 

**Getting Started with Python**
Python is an object-oriented, flexible, and popular programming language. It uses free, open-source software; if your computer is a Mac, it comes already installed. If you are using a Windows machine, you will need to install the software.

- Install the latest version of Python from [Python.org](https://www.python.org/downloads/)
- Open the Python IDLE application
- [Learn how to create a "Hello, world!" program](helloworld.md)

**Drawing a Cute Heart**
A "turtle" is a program that functions a bit like a drawing board. The turtle is the pen. This is how to make a heart.
- Create a new file in IDLE
- Import the turtle library
- Initialize the variable for your screen
- Initialize the variable for your turtle
- Optionally, define what color the line will be
- Tell your turtle where to go
- End your program with the "done" command
- Save your file

Here is an example of the finished code. 

`import turtle  # Imports turtle library`
`screen = turtle.getscreen() # Creates drawing board`
`turt = turtle.Turtle() # The turtle variable`
`turt.shape("turtle") # Makes it cute`
`turt.color("red") # Makes it red`
`turt.left(45)
turt.forward(100)
turt.circle(50,180)
turt.right(90)
turt.circle(50,180)
turt.forward(100)
turt.backward(100)
turt.left(180) # The turtle moves`

`turtle.done() # Ends the program`

Done!
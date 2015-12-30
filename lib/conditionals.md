---
title: Conditionals
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What is a conditional?

A conditional is used to control the flow of a program once it is executed.  It does this by using 'if', 'else', and 'elseif' statements. 
Flow in a program can also be controlled using the comparison method.  This method uses comparators such as: <, >, ==, <=, >=, and != to determine whether or not
to execute a block of code.
If the condition following an 'if' statement is true, then Ruby will run the block of code following it.  If the statement is false, then Ruby will jump to 
the next line of code.  Often this is an 'else' statement.  We can add multiple conditions to the code using 'elseif'.  Like an 'if' statement, an 'elseif' statement
will run the following block of code only if the condition is true.  Otherwise, it will jump to the next 'elseif' or 'else' statement in the code. 

If we wanted to write a program that repeated itself until a certain condition is true, then we would use another method of flow control called a loop.  If we wanted to paint a canvas yellow
using a ruby commands: paint_yellow and canvas_is_full.  We would want the comand paint_yellow to repeat itself until the canvas was full.  We could do this using "while".  
Our paint yellow program might look something like this:
while !canvas_is_full
    paint_yellow
        if canvas_is_full
        break
    end
end


# What is the difference between `=` and `==`?

In Ruby a '==' is used to check equality,
while '=' is used to set the value of a variable. 
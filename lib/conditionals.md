---
title: Conditionals
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What is a conditional?

A conditional in Ruby is like saying "If...then...". It creates a condition that must be met before the second part of the statement can occur.
A conditional is always either true or false. A true condition will signify the start of an operation. A false one will not do anything.
In Ruby 'if' is used to start a conditional and a "conditional operator" like '==' or '>='. If that is met the loop starts.
If not the conditional can stop or branch off using 'elseif' if a certain other condition is met or 'else' when no conditions are met.


# What is the difference between `=` and `==`?

A singular '=' is used to define a variable, similar to its use in mathematics. 
Starting off by defining 'a = 100' will allow the programmer to use 'a' instead of typing out '100' when necessary. 
In that example the variable name is 'a' and its value is 100.

The double equal sign '==' is used in conditional loops and is one of several conditional operators. 
I understand them as being a part of the 'if' in an if-then statement. 
They are always either 'true' or 'false' and that condition will signify whether the loop will proceed, branch off, or stop altogether. 
If a programmer wants something to happen only when 'a' is a certain value they can use "if a == 100" to signify that an operator should start only when 'a' has a value of 100.
If a does have a value of 100 then the operator '==' will be true. For all other values it will be false.

'=' and '==' look similar but mean very different things and definitely are not good to mix up!
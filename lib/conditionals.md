---
title: Conditionals
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What is a conditional?

A conditional allows a block of code to be run if the condition given is true or some other code to be run if it returns false.

Some examples of using conditionals:

1. If 5 is greater than 3 then print out "5 is more than 3.". If 5 is not greater than 3 then print out "The world has turned upside down!".

if 5 > 3
    puts "5 is more than 3."
else
    puts "The world has turned upside down!"
end

2. If 17 is not equal to 17 then print out "What???". If  17 is equal to 17 print out "Of course 17 is equal to 17."

if 17 != 17
    puts "What???"
else
    puts "Of course 17 is equal to 17."
end

# What is the difference between `=` and `==`?

The = sign assigns a value to a variable while the == operator checks if something is equal to something else.
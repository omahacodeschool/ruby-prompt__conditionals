---
title: Conditionals
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What is a conditional?

Conditions are circumstances that can require modifications to the course of action of a program in order for the program to achieve its goal. 
Conditions can compel a program to follow different branches on a path toward a desired result.

A conditional indicates to the computer what those conditions are and what to do when it encounters them.

For example, if I am running a program to have my robot friend, Tom, make me a grilled cheese sandwich, I MUST add conditionals to modify Tom’s course of action using commands that he can understand. 
I must tell Tom, using conditionals, that if the pan is hot, he can place the sandwich on it, else (otherwise) he must wait patiently until the pan is hot. 
Likewise, I must tell him that if the cheese is melted to the proper temperature, he must remove the sandwich from the heat, else (otherwise) he must wait, repeat these actions until the cheese is melted, and so forth. 
I can (and probably should) also tell Tom how to modify his actions if the cheese is moldy, if the bread is gone, if the stove catches fire, etc.

# What is the difference between `=` and `==`?

The computer can determine if a condition is met using the comparative operator, or "==". 
Using "==" requires that there are only two outcomes to a given scenario, true and false, and the computer should determine which is correct.

However, I can communicate specifics to the computer using the assignment operator, or “=”.
Using “=” assigns value to the necessary variables in a way the computer can understand.
Unlike "==", "=" will not ask the computer to check if something is true or false. Instead, I am telling the computer that 'this' means 'that' in a given situation.
For example, if I want to tell a computer that I would like to get an input from a user and call it "name," I can tell it that name = gets.chomp.
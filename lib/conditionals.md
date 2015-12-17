---
title: Conditionals
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What is a conditional?

 A conditional is what controls the flow of a program. A contional allows one to give a program conditions that, 
 when met, execute the program one way, or if not met, allow the program to run another way (for example, If, else, elseif, etc...).
 
 Using the conditional statement "else," for example, allows one to execute a program that runs a particular block of code if the conditions 
 of the original "if" statement are not met. In addition, one could use "elseif" if there is more than one condition to be met. 
 
 Example:
 if me == "thirsty"
 puts "You should drink some water!"
 elseif me == "hungry"
 puts "You should eat an apple!"
 else
 puts "You seem content to me."
 end
 
 In the above example, this simplified code would give the output "You should drink some water" only if the "If" statement's conditions are met 
 (in this case, that me == thirsty). However, the "elseif" statement allows for another condition. If I am hungry instead (me == "hungry"), the program 
 would output "You should eat an apple!". Otherwise if neither of the two conditions (if or elseif) are true, the program would default to the "else" 
 statement's code.
 
 Another example of how a conditional could be used in control flow could be to use a loop. Loops are used to run the same block of code a certain 
 amount of times. In a while loop, for example, the block of code in the loop runs (possibly repeatedly) while the conditional is true.
 
 

# What is the difference between `=` and `==`?

"==" is used to check for equality, whereas "=" is used to set the value of variables.
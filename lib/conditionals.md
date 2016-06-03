---
title: Conditionals
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What is a conditional?

Conditionals are used to control flow within a program, I think of it like a flow chart.  
If there are two braches you use if and else.  
If there are more than two branches you can use if, elsif, and else using as many eslifs that are needed.  
The program starts at the beginning and runs until one of options is true. 

An example of an if / else:
num = 9
if num % 3 == 0
   puts "The number is a multilpe of three"
else
   puts "The number is not a multiple of three"
 end
   
  => "The number if a multiple of three" (the if was satisfied)
  
  num = 7
  if num % 3 == 0
     puts "The number is a multiple of three"
  else
     puts "The number is not a multiple of three"
  end
     
     => "The number is not a multilpe of three"  (the if was not satisfied)


An example of a while loop:

x = 25
while x > 0
  x -= 5
puts x
end

=> 20     (25-5)
   15     (20-5)
   10     (15-5)
   5      (10-5)
   0      (5-5)
   
   This loop counts down by fives.  It first plugs 25 in for x.
   The loop stops when it tries to plug in 0 because it is not greater than 0.


# What is the difference between `=` and `==`?


A single equals sign is used to assign a value to a variable.  
A double equals sign is used to test for equlity.  
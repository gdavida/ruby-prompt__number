---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

-integers
    -numbers without decimal points
-floats
    -numbers with decimal points

# What are some common operations and comparisons you would perform on numbers?

+ addition
- subtraction
/ division
* multiplication
% modulus (divides first number by second number and returns the remainder)
** exponent (takes first number to the second numberth power)

____NOTE____
You can preform operations using integers and floats together. The answer will return a float.
puts 2 + 2.5  #=> 4.5
puts 2.5 + 2 #=> 4.5

( http://ruby-doc.org/core-2.2.3/Float.html )

# What is the difference between the `+` operation on a number versus on a String?

-operator it performs the math of adding the numbers together
    puts 2 + 2  => 4
-string it is used to contatenate the strings together
    puts "2" + "2"  => 22
    puts "apple" + "juice"  => applejuice
    

# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

Numbers being used as strings need to be turned into integers before trying to preform a mathematical operation. 
    -Use the .to_i method
    age = "20"
    age.to_i
Or if you want a number to turn into a string you use .to_s method
    age = 2016 - 1983
    age.to_s

# What is the purpose of the `times` operation? Is that the same as `*`?

-'times' is the number of times to run some given action.
( https://www.codecademy.com/articles/glossary-ruby )

Times and * are NOT the same because .times works with objects and * is used with for numbers or maybe a string for the first part but then a number.
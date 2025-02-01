# Ruby Instance Variable Shadowing Bug

This repository demonstrates a subtle bug in Ruby where an instance method with the same name as an instance variable can inadvertently hide the variable, leading to unexpected behavior when attempting to modify the variable's value.

## The Bug
The `bug.rb` file shows how defining a method with the name of an instance variable prevents modification of that instance variable, resulting in unexpected behavior.

## The Solution
The `bugSolution.rb` file presents a solution where the method's name is changed to avoid conflicts with the instance variable's name or using `attr_accessor` to handle assignments.
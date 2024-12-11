# Unexpected Behavior When Directly Modifying Instance Variables

This repository demonstrates a potential issue in Ruby when directly modifying instance variables using `instance_variable_set`. While the code works, it violates encapsulation principles and can cause unexpected behavior or make debugging more difficult.

The `bug.rb` file shows the problem. The `bugSolution.rb` file offers a more robust approach.

## How to Reproduce the Bug

1. Clone this repository.
2. Run `bug.rb` using a Ruby interpreter.
3. Observe that the value of the instance variable is modified even without using the accessor method.
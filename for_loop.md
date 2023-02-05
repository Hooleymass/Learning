# For Loop Manual

A "for loop" is a type of control flow statement that allows you to repeat a set of instructions a specific number of times. In this manual, we will explain the concept of a for loop and how to use it in a computer program.

## Introduction

A for loop is a tool that helps you automate repetitive tasks. It is used to perform a specific action multiple times, either for a specified number of iterations or until a certain condition is met. For loops are widely used in programming and are supported by most programming languages.

## Structure of a for loop

A for loop has three components:

1. Initialization: The initialization component is used to set a starting value for the loop's counter variable. This value is usually set to 0, but it can be set to any other value depending on the requirements of the task.

2. Condition: The condition component is a boolean expression that is evaluated before each iteration. The loop continues to execute as long as the condition is true. When the condition becomes false, the loop terminates.

3. Increment/ Decrement: The increment/decrement component is used to update the value of the loop's counter variable after each iteration. This is usually used to control the number of times the loop runs.

Here is the general structure of a for loop in most programming languages:

```
for (initialization; condition; increment/decrement) {
  // code to be executed
}

```

## Using a for loop
To use a for loop, you need to specify the following elements:

1. The starting value for the loop's counter variable.
2. The condition that will cause the loop to terminate.
3. The step size for updating the loop's counter variable after each iteration.

Once you have specified these elements, you can use the for loop to execute a set of instructions for each iteration.

Here is a simple example of a for loop in Python that prints the numbers 0 to 9:
```
for i in range(10):
  print(i)
```

This will output:

```
0
1
2
3
4
5
6
7
8
9
```

In this example, the `for loop` uses the `range` function to specify the number of iterations. The `range` function generates a sequence of numbers from 0 to 9 (not including 10). The loop's counter variable `i` takes on each value in the sequence and the `print` function is used to print the value of `i` for each iteration.


## Conclusion
For loops are a powerful tool for automating repetitive tasks and simplifying complex algorithms. Understanding how for loops work and how to use them is an essential skill for any programmer. With this manual, you should have a good understanding of what for loops are and how to use them in your code.

## Subtitute
A common substitute for a "for loop" in programming is a "[while loop](./while_loop.md)".  while loop allows you to execute a block of code repeatedly while a certain condition is true. Here's an example of how a while loop can be used in Python to print the numbers 0 to 9:
```
i = 0
while i < 10:
  print(i)
  i += 1
```
output:
```
0
1
2
3
4
5
6
7
8
9
```

Another substitute for a for loop is the "foreach loop", which is commonly used in programming languages like Java and C#. A foreach loop allows you to iterate over a sequence of elements, such as an array or a list, and perform a specific operation on each element.

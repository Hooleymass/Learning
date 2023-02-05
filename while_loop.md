# While Loops

A `while` loop is a control structure that allows you to repeat a block of code as long as a given condition is true. 

The basic syntax for a `while` loop is:

```c
while (condition) {
// code to be executed
}

```

The `condition` is evaluated before each iteration of the loop. If the condition is `true`, the code within the loop will be executed. Once the condition becomes `false`, the loop will terminate and the code following the loop will be executed.

Here's an example of how you could use a `while` loop to count from 1 to 10:

```
var i = 1;
while (i <= 10) {
console.log(i);
i++;
}
```

This loop will repeat 10 times and print the numbers 1 through 10 to the console.

It's important to make sure that the condition eventually becomes `false`, or the loop will continue indefinitely, resulting in an infinite loop.



<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Row 1, Column 1</td>
    <td>Row 1, Column 2</td>
  </tr>
  <tr>
    <td>Row 2, Column 1</td>
    <td>Row 2, Column 2</td>
  </tr>
</table>


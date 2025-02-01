## Expression Evaluator

### Description
The program interprets and calculates the value of mathematical expressions written in prefix notation. It allows you to build an expression tree, modify it and perform calculations. It supports arithmetic operators (+, -, *, /) and trigonometric functions (sin, cos). The program automatically completes incorrect expressions, provides the ability to print a list of variables used in the tree and allows for dynamic combination of expressions. It uses the Tree class to manage data, representing the entire tree, and the Node class, corresponding to a single node.

### Commands

- **`enter <formula>`** – creates a tree based on the given expression. If the formula contains errors, the program corrects them and displays a modified version.
- **`vars`** – prints all variables in the current tree (each variable appears only once).
- **`print`** – displays the current tree in prefix notation.
- **`comp <var0> <var1> ... <varN>`** – calculates the value of the expression for the given variable values ​​in the order returned by `vars`. If the number of values ​​given does not match the number of variables, the program reports an error.
- **`join <formula>`** – creates a new tree based on the given expression and appends it to the existing tree, replacing one of its leaves.
- **`stop`** – stops the program.

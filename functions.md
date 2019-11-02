# Scripts
A script is a series of instructions that a computer can follow to achieve a goal like a recipe with a step by step instruction. To write a script, you must know the end goal.
1. Define the goal
2. Design the script by using a flow chart or a list of steps
3. Code each step
# Expressions
An expression results into a single value.
- There are expressions that just assign a value to a variable:
    - `var number = 1;`
- And expressions that use two or more values to return a single value:
    - `var area = 5 * 12;`
# Operators
Operators are an important part of an expression because they allow a single variable to be created from one or more values.
- Assignment operators
    - `var number = 1;`
- Arithmetic operators which include +, -, /, *, ++, --, and %
    - `var area = 3 * 2;`
- String operators
    - `var message = "Hi" + ", how are you?";` this uses concatenation which combines two strings into one
- Comparison operators
    - `var buy = 4 > 9;` which returns a false value
- Logical operators
    - `var buy = (9 > 4) && (1 < 8);` which returns true
# Functions
Functions give you the ability to group a series of statements together to perform a task. The statements in a functions are not always executed when a page loads. Functions offer a way to store the steps needed to achieve a task.
- *Functions should be named by describing the task it is performing.*
When asked to perform its task, the function is being **called**. The task is packaged in a code block which consists of one or more statements within a curly brace. Pieces of information that is passed to a function are called **parameters**. And the response of the function is called a **return value**.
    ```
    var msg = 'Hi there!';
    function updateMessage() {
        var el = document.getElementByID('message');
        el.textContent = msg;
    }
    updateMessage();
    ```

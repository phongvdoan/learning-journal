## Comparison Operators
Comparing one value in the script to a value that is to be expected which results in boolean, either true or false. This is called evaluating the condition.
- `==` is equal to. This operator compares two values to see if they are the same.
- `!=` is not equal to. This operator compares two values to see if they are *not* the same.
- `===` strict equal to. This operator compares two values to check that both the data type and the values are the same.
- `!==` strict not equal to. This operator compares two values to check that both the data type and the values are *not* the same.
- `>` greater than. This operator checks to see if the first value is greater that the value on the right.
- `<` less than. This operator checks to see if the first value is less than the right.
- `>=` greater than or equal to
- `<=` less than or equal to 
In a condition, there are usually one operator and two operands which are placed on each side of the operator. These expressions are often enclosed in parenthesis.
    - `(height > weight)`
You can also use expressions with comparison operators. The operands do not have to be single value.
    - `(speed1 + distance1) > (speed2 + distance2)`
## Logical Operators
These operators allow you to compare the results of more than one comparison operator. Logical expressions are evaluated left to right. If the first condition can provide enough information to get the answer, then there is no need to evaluate the other.
- `&&` logical And. It tests more than one condition.
    - **true** && **true** returns true
    - **true** && **false** returns false
    - **false** && **true** returns false
    - **false** && **false** returns false
- `||` logical Or. It tests at least one condition
    - **true** \|\| **true** returns true
    - **true** \|\| **false** returns true
    - **false** \|\| **true** returns true
    - **false** \|\| **false** returns false
- `!` logical Not. This takes a single Boolean value and inverts it.
    - !true returns false
    - !false returns true
## Loops
Loops check a condition. If it returns true then the code block will run. The condition will be checked again until it returns false.
### For Loops
This is used if you need the run the code a specific amount number of times. The condition is usually a counter which is used to tell how many times the loop should run.
    - `for (var i = 0; i < 10; i++)`
In the for loop, the `var i = 0` is the initialization which is the creating of a variable to act as a counter. The condition is `i < 10`. And the update is `i++` which increases the variable by 1 every time the code block runs.
### While Loops
This is used if you do not know how many times the code should run. And it will run as long as the condition returns true.
    - `While (i < 10)`
### Do While Loops
This is similar to the while loop, except that it will run at least once before testing the condition even if it is false.

    ```
    Do {
        //something
    } while (i < 1);
    ```

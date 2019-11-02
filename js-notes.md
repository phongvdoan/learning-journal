# JavaScript
## What is the difference?
HTML is where the content lives, which gives the page structure and adds semantics. CSS enhances the HTML page as a presentation layer which is how the content is presented. JavaScript is how the page behaves with interactivity.
JavaScript increases the user experience with the site.

In `document.write('Good Morning');` doument is the object. The period is the member operator which allows access of the members of the bboject. Write() is the method of the object document and inside of the parenthesis is the parameter.

## Statements
- A script is a series of instructions that a computer can follow one by one.
- A statement is an individual instruction which starts on a new line and end with a semicolon.
```
var today = new Date();
var hourNow = today.getHours();
```
- Code blocks are statements surrounded by curly braces which is not followed by a semicolon.
```
f (hourNow > 18) {
    greeting = 'Good Evening!';
} else if (hourNow > 12) {
    greeting = 'Good Afternoon!';
} else if (hourNow > 0) {
    greeting = 'Good Morning!';
} else {
    greeting ='Welcome!';
}
```
Using Comments to explain what your code does makes it easier for others to read and understand it. For single-line comments `//` is used and for multi-line comments start with `/*` and end with `*/`.

*Variables* temporarily store bits of data in order for the script to do its job. **It can change each time the script runs**.

in `var count = 1;`, var is the variable keyword and count is the variable name.

## Data Types
*Once you assigned a value to a variable, you can change what is stored later*

### Numeric Data Type
These types store numbers to include negative integers and decimals.
- `var price = 5;`
### String Data Type
This data types consists of letters and other characters enclosed in either single or double quotes. If you start with single quotes, it must end in single quotes. Same with double quotes. In addition, strings must always be written on one line. 
```
var message;
message = 'Hello!';
```
### Boolean Data Type
These can either have one of two values: *true* or *false*. Its like a light switch, either on or off. Booloeans are used when your code can take more than one path.
```
var cold;
cold = true;
```
## Shorthand
1. Varibles are declared and values assigned in the same statement.
- `var price = 5;`
2. All variables are declared on the same line, then values assigned to each.
- `var price, quantity, total;`
3. All variables are declared and assigned values on the same line.
- `var price = 5, quantity = 14;`

## Rules for Naming Variables
1. The name must begin with a letter, dollar sign, or an underscore, not a number.
2. The name can contain letters, numbers, dollar sign, or an underscore.
3. You cannot use keywords or reserved words which tell the interpreter to do something.
4. All variables are case sensitive.
5. Use a name that describes the kind of information that the variable stores.
6. If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word.


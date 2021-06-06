# JavaScript Functions:
A JavaScript function is a block of code designed to perform a particular task.

A JavaScript function is executed when "something" invokes it (calls it).

**JavaScript Function Syntax**:

A JavaScript function is defined with the function keyword, followed by a name, followed by parentheses ().

Function names can contain letters, digits, underscores, and dollar signs (same rules as variables).

The parentheses may include parameter names separated by commas:
(parameter1, parameter2, ...)

The code to be executed, by the function, is placed inside curly brackets: {}

_function name_(parameter1, parameter2, parameter3) {

  // code to be executed

  * parameters are listed inside the parentheses () in the function definition.
  * Function arguments are the values received by the function when it is invoked.
  * Inside the function, the arguments (the parameters) behave as local variables.
  >A Function is much the same as a Procedure or a Subroutine, in other programming languages.

  **Function Invocation**
  The code inside the function will execute when "something" invokes (calls) the function:
  - When an event occurs (when a user clicks a button)
  - When it is invoked (called) from JavaScript code
  - Automatically (self invoked)
  ### Why Functions?
  You can reuse code: Define the code once, and use it many times.

You can use the same code many times with different arguments, to produce different results.

**JavaScript Operators:**

- The assignment operator (=) assigns a value to a variable.
- The addition operator (+) adds numbers:
- The multiplication operator (*) multiplies numbers.

**JavaScript Arithmetic Operators**
* 	Addition  +
*  	Subtraction -
*   Multiplication *
*   Exponentiation (ES2016) **
*  Increment  ++
*  decrement --

**Control flow**
The control flow is the order in which the computer executes statements in a script.

Code is run in order from the first line in the file to the last line, unless the computer runs across the (extremely frequent) structures that change the control flow, such as conditionals and loops. 

For example, imagine a script used to validate user data from a webpage form. The script submits validated data, but if the user, say, leaves a required field empty, the script prompts them to fill it in. To do this, the script uses a conditional structure or if...else, so that different code executes depending on whether the form is complete or not:A typical script in JavaScript or PHP (and the like) includes many control structures, including conditionals, loops and functions. Parts of a script may also be set to execute when events occur.
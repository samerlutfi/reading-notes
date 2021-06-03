# What is JavaScript?
JavaScript is a cross-platform, object-oriented scripting language used to make webpages interactive (e.g., having complex animations, clickable buttons, popup menus, etc.).

**Grammar and types:**

JavaScript is case-sensitive and uses the Unicode character set. For example, the word Früh (which means "early" in German) could be used as a variable name.
>Comments:

// a one line comment

/* this is a longer,
 * multi-line comment
 */

/* You can't, however, /* nest comments */ SyntaxError */

* JavaScript has three kinds of variable declarations:

**var**

Declares a variable, optionally initializing it to a value.

**let**

Declares a block-scoped, local variable, optionally initializing it to a value.

**const**

Declares a block-scoped, read-only named constant.

**variables:**

You use variables as symbolic names for values in your application. The names of variables, called identifiers, conform to certain rules.


A JavaScript identifier must start with a letter, underscore (_), or dollar sign ($). Subsequent characters can also be digits (0–9).

Because JavaScript is case sensitive, letters include the characters "A" through "Z" (uppercase) as well as "a" through "z" (lowercase).


You can use most of ISO 8859-1 or Unicode letters such as å and ü in identifiers. (For more details, see this blog post.) You can also use the Unicode escape sequences as characters in identifiers.

Some examples of legal names are Number_hits, temp99, $credit, and _name.


**Evaluating variables**

A variable declared using the var or let statement with no assigned value specified has the value of undefined.

An attempt to access an undeclared variable results in a ReferenceError exception being thrown:

var a;
console.log('The value of a is ' + a); // The value of a is undefined

console.log('The value of b is ' + b); // The value of b is undefined
var b;
// This one may puzzle you until you read 'Variable hoisting' below

console.log('The value of c is ' + c); // Uncaught ReferenceError: c is not defined

let x;
console.log('The value of x is ' + x); // The value of x is undefined

console.log('The value of y is ' + y); // Uncaught ReferenceError: y is not defined
let y; 
You can use undefined to determine whether a variable has a value. In the following code, the variable input is not assigned a value, and the if statement evaluates to true.

_var input;_

if (input === undefined) {
  doThis();
} else {
  doThat();
}
The undefined value behaves as false when used in a boolean context. For example, the following code executes the function myFunction because the myArray element is undefined:

var myArray = [];
if (!myArray[0]) myFunction();
The undefined value converts to NaN when used in numeric context.

var a;
a + 2;  // Evaluates to NaN
When you evaluate a null variable, the null value behaves as 0 in numeric contexts and as false in boolean contexts. For example:

var n = null;
console.log(n * 32); // Will log 0 to the console
Variable scope
When you declare a variable outside of any function, it is called a global variable, because it is available to any other code in the current document. When you declare a variable within a function, it is called a local variable, because it is available only within that function.

JavaScript before ECMAScript 2015 does not have block statement scope. Rather, a variable declared within a block is local to the function (or global scope) that the block resides within.

For example, the following code will log 5, because the scope of x is the global context (or the function context if the code is part of a function). The scope of x is not limited to the immediate if statement block.

if (true) {
  var x = 5;
}
console.log(x);  // x is 5
This behavior changes when using the let declaration (introduced in ECMAScript 2015).

if (true) {
  let y = 5;
}
console.log(y);  // ReferenceError: y is not defined
Variable hoisting
Another unusual thing about variables in JavaScript is that you can refer to a variable declared later, without getting an exception.

This concept is known as hoisting. Variables in JavaScript are, in a sense, "hoisted" (or "lifted") to the top of the function or statement. However, variables that are hoisted return a value of undefined. So even if you declare and initialize after you use or refer to this variable, it still returns undefined.

/**
 * Example 1
 */
console.log(x === undefined); // true
var x = 3;

/**
 * Example 2
 */
// will return a value of undefined
var myvar = 'my value';

(function() {
  console.log(myvar); // undefined
  var myvar = 'local value';
})();
The above examples will be interpreted the same as:

/**
 * Example 1
 */
var x;
console.log(x === undefined); // true
x = 3;

/**
 * Example 2
 */
var myvar = 'my value';

(function() {
  var myvar;
  console.log(myvar); // undefined
  myvar = 'local value';
})();
Because of hoisting, all var statements in a function should be placed as near to the top of the function as possible. This best practice increases the clarity of the code.

# Loops and iteration:
![df](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Loops-1200x720.jpg)

Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.

You can think of a loop as a computerized version of the game where you tell someone to take X steps in one direction, then Y steps in another. For example, the idea "Go five steps to the east" could be expressed this way as a loop:

>for (let step = 0; step < 5; step++) {
  // Runs 5 times, with values of step 0 through 4.
  console.log('Walking east one step');
}

**for statement:**

 for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

A for statement looks as follows:
>for ([initialExpression]; [conditionExpression]; [incrementExpression])
  statement

  _When a for loop executes, the following occurs:_

  1. The initializing expression initialExpression, if any, is executed. This expression usually initializes one or more loop counters, but the syntax allows an expression of any degree of complexity. This expression can also declare variables.
  2. The conditionExpression expression is evaluated. If the value of conditionExpression is true, the loop statements execute. If the value of condition is false, the for loop terminates. (If the condition expression is omitted entirely, the condition is assumed to be true.)
  3. The statement executes. To execute multiple statements, use a block statement ({ ... }) to group those statements.
  4. If present, the update expression incrementExpression is executed.
  5. Control returns to Step 2.
   ![f](https://cdn.educba.com/academy/wp-content/uploads/2020/02/Nested-Loop-in-Java-Flowchart.jpg)

   **while statement:**
   ![s](https://www.freecodecamp.org/news/content/images/2020/11/image-24.png)
   A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

while (condition)
  statement
* If the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.

The condition test occurs before statement in the loop is executed. If the condition returns true, statement is executed and the condition is tested again. If the condition returns false, execution stops, and control is passed to the statement following while.

To execute multiple statements, use a block statement ({ ... }) to group those statements.



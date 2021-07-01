### Debugging & Error Handling:

* If you understand execution contexts (which have two 
stages) and stacks, you are more likely to find the error 
in your code.

* Debugging is the process of finding errors. It involves a 
process of deduction. 
* The console helps narrow down the area in which the 
error is located, so you can try to find the exact error.
![f](https://www.oreilly.com/library/view/javascript-and-jquery/9781118531648/images/p452-001.jpg)

- Error handling is a combination of coding and methodology that allows your program to anticipate user and other errors. ... It allows you to create a robust program.

>here are many types of errors that you can unwittingly build into your scripts, and finding them provides hours of fun for all the family. Errors can result from:

1-Including language features or syntax that the scripting engine does not support within the script.

2-Failing to correctly implement the intent of the program or some particular algorithm. This occurs when, although code is syntactically correct and does not generate any errors, it produces behavior or results other than those you intend. 

3-Including components that contain bugs themselves. In this case, the problem lies with a particular component, rather than with your script, which “glues” the components together.

* JavaScript has 7 different types of errors. Each creates 
its own error object, which can tell you its line number 
and gives a description of the error. 

* If you know that you may get an error, you can handle 
it gracefully using the try, catch, finally statements. 
Use them to give your users helpful feedback. 


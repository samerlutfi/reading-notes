# Text in HTML:
● **Structural markup:** the elements that you can use to 
describe both headings and paragraphs
● **Semantic markup:** which provides extra information; such 
as where emphasis is placed in a sentence, that something 
you have written is a quotation (and who said it), the 
meaning of acronyms, and so on.

**Headings:**
HTML has six "levels" of 
headings:
<h1> is used for main headings
<h2> is used for subheadings</h2>

**Paragraphs:**



To create a paragraph, surround 
the words that make up the 
paragraph with an opening  
tag and closing tag.
By default, a browser will show 
each paragraph on a new line 
with some space between it and 
any subsequent paragraphs.

**Bold & Italic:**
"By enclosing words in the tags 
<b> and </b> we can make 
characters appear bold.
The <b> element also represents 
a section of text that would be 
presented in a visually different 
way (for example key words in a 
paragraph) although the use of 
the <b> element does not imply 
any additional meaning"

* By enclosing words in the tags 
<i> and </i> we can make 
characters appear italic.
The <i> element also represents 
a section of text that would be 
said in a different way from 
surrounding content — such as 
technical terms, names of ships, 
foreign words, thoughts, or other 
terms that would usually be 
italicized.

**Strong & Emphasis:**

> The use of the <strong>
element indicates that its 
content has strong importance. 
For example, the words 
contained in this element might 
be said with strong emphasis.
By default, browsers will show 
the contents of a <strong>
element in bold

> The <em> element indicates 
emphasis that subtly changes 
the meaning of a sentence.
By default browsers will show 
the contents of an <em> element 
in italic.

**bbreviations & 
Acronyms:**

If you use an abbreviation or 
an acronym, then the <abbr>
element can be used. A title
attribute on the opening tag is 
used to specify the full term.

**Citations &
Definitions:**

* When you are referencing a 
piece of work such as a book, 
film or research paper, the 
<cite> element can be used 
to indicate where the citation is 
from.
In HTML5, <cite> should not 
really be used for a person's 
name — but it was allowed in 
HTML 4, so most people are 
likely to continue to use it.

* The first time you explain some 
new terminology (perhaps an 
academic concept or some 
jargon) in a document, it is 
known as the defining instance 
of it.
The <dfn> element is used to 
indicate the defining instance of 
a new term.

* The <address> element has 
quite a specific use: to contain 
contact details for the author of 
the page.
It can contain a physical address, 
but it does not have to. For 
example, it may also contain a 
phone number or email address.

* The <ins> element can be used 
to show content that has been 
inserted into a document, while 
the <del> element can show text 
that has been deleted from it.

* The <s> element indicates 
something that is no longer 
accurate or relevant (but that 
should not be deleted)

### Introducing CSS:

* CSS allows you to create rules that control the 
way that each individual box (and the contents 
of that box) is presented.

* CSS works by associating rules with HTML elements. These rules govern 
how the content of specified elements should be displayed. A CSS rule 
contains two parts: a selector and a declaration.

I[dd](https://miro.medium.com/max/3840/1*naFDyXh9iGtmvNRhhFY-og.png)

**Using External CSS:**

The <link> element 

can be used 
in an HTML document to tell the 
browser where to find the CSS 
file used to style the page. It is an 
empty element (meaning it does 
not need a closing tag), and it 
lives inside the <head> element. 
It should use three attributes:

href

This specifies the path to the 
CSS file (which is often placed in 
a folder called css or styles).

type

This attribute specifies the type 
of document being linked to. The 
value should be text/css.

rel

This specifies the relationship 
between the HTML page and 
the file it is linked to. The value 
should be stylesheet when 
linking to a CSS file.

**Using Internal CSS:**

You can also include CSS rules 
within an HTML page by placing 
them inside a <style> element, 
which usually sits inside the 
<head> element of the page. 
The <style> element should use 
the type attribute to indicate 
that the styles are specified in 
CSS. The value should be text/
css.

**CSS Selectors:**

![dd](https://cf.ppt-online.org/files/slide/k/Kbp3XcismqFREgGuz9OBIWY1vDx6MwHVeZQjC5/slide-8.jpg)


**Why use External Style Sheets?**

* When building a website there are several advantages to placing your 
CSS rules in a separate style sheet.

* Sometimes you might consider placing CSS rules in the same page as 
your HTML code.

###  BASIC JAVASCRIPT INSTRUCTION:

**STATEMENTS:**

A script is a series of instructions that a computer can follow one-by-one. 
Each individual instruction or step is known as a statement. 
Statements should end with a semicolon.

* STATEMENTS ARE INSTRUCTIONS AND 
EACH ONE STARTS ON A NEW LINE 

* Some statements are surrounded by curly braces; 
these are known as code blocks. The closing curly 
brace is not followed by a semicolon. 

**Comments:**

You should write comments to explain what your code does. 
They help make your code easier to read and understand. 
This can help you and others who read your code. 

> To write a comment that stretches over more than 
one line, you use a multi-line comment, starting with 
the /* characters and ending with the */ characters. 
Anything between these characters is not processed· 
by the JavaScript interpreter.

**WHAT IS A VARIABLE?** 

A script will have to temporarily 
store the bits of information it 
needs to do its job. It can store this 
data in variables.

- A variable is a good name for this 
concept because the data stored 
in a variable can change (or vary) 
each time a script runs.

**DATA TYPES:**

* **NUMERIC DATA TYPE :**

The numeric data type handles 
numbers.

* **STRING DATA TYPE :**

The strings data type consists of 
letters and other characters.

* **BOOLEAN DATA TYPE:**

Boolean data types can have one 
of two values: true or false.

**ARRAYS**

An array is a special type of variable. It doesn't 
just store one value; it stores a list of values. 
You should consider using an 
array whenever you are working 
with a list or a set of values that 
are related to each other. 
Arrays are especially helpful 
when you do not know how 
many items a list will contain 
because, when you create the 
array, you do not need to specify 
how many values it will hold. 
If you don't know how many 
items a list will contain, rather 
than creating enough variables 
for a long list (when you might 
only use a small percentage 
of them), using an array is 
considered a better solution. 

**ARITHMETI C OPERATORS:**

![dd](https://www.devopsschool.com/blog/wp-content/uploads/2020/07/JavaScript-Arithmatic-Operators.png)

* A script is made up of a series of statements. Each 
statement is like a step in a recipe. 


* Scripts contain very precise instructions. For example, 
you might specify that a value must be remembered 
before creating a calculation using that value. 

* Variables are used to temporarily store pieces of 
information used in the script. 

* Arrays are special types of variables that store more 
than one piece of related information. 

* JavaScript distinguishes between numbers (0-9), 
strings (text), and Boolean values (true or false).


* Expressions evaluate into a single value.

**USING COMPARISON OPERATORS**

Comparison operators — operators that compare values and return true or false. The operators include: >, <, >=, <=, ===, and !==.
Logical operators — operators that combine multiple boolean expressions or values and provide a single boolean output. The operators include: &&, ||, and !.

**Comparison Operators**

You may be familiar with comparison operators from math class. Let’s make sure there aren’t any gaps in your knowledge.

Less than (<) — returns true if the value on the left is less than the value on the right, otherwise it returns false.
Greater than (>) — returns true if the value on the left is greater than the value on the right, otherwise it returns false.
Less than or equal to (<=) — returns true if the value on the left is less than or equal to the value on the right, otherwise it returns false.
Greater than or equal to (>=) — returns true if the value on the left is greater than or equal to the value on the right, otherwise it returns false.
Equal to (===) — returns true if the value on the left is equal to the value on the right, otherwise it returns false.
Not equal to (!==) — returns true if the value on the left is not equal to the value on the right, otherwise it returns false.

**Logical Operators:**

Comparison operators allow us to assert the equality of a statement with JavaScript. For example, we can assert whether two values or expressions are equal with ===, or, whether one value is greater than another with >.

There are scenarios, however, in which we must assert whether multiple values or expressions are true. In JavaScript, we can use logical operators to make these assertions.

&& (and) — This operator will be truthy (act like true) if and only if the expressions on both sides of it are true.
|| (or) — This operator will be truthy if the expression on either side of it is true. Otherwise, it will be falsy (act like false).


**USING IF STATEMENTS:**


**Use if** to specify a block of code to be executed, if a specified condition is true.
**Use else** to specify a block of code to be executed, if the same condition is false.
**Use else if** to specify a new condition to test, if the first condition is false.















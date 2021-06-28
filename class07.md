### Domain Modeling:
Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.
* Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

* tips to follow when building your own domain models:
1-When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2-Model its attributes with a constructor function that defines and initializes properties.
3-Model its behaviors with small methods that focus on doing one job well.
4-Create instances using the new keyword followed by a call to a constructor function.
5-Store the newly created object in a variable so you can access its properties and methods from outside.
6-Use the this variable within methods so you can access the object's properties and methods from inside.

### Tables:
**What's a Table?**
A table represents information in a grid format. 
Examples of tables include financial reports, TV 
schedules, and sports results.

* Basic Table Structure:
(<)table):The <table> element is used 
to create a table. The contents 
of the table are written out row 
by row.
\tr):You indicate the start of each 
row using the opening ()tr) tag. 
(The tr stands for table row.) 
It is followed by one or more 
td) elements (one for each cell 
in that row). 
At the end of the row you use a 
closing </tr) tag.
* Each cell of a table is 
represented using a |td|
element. (The td stands for 
table data.)
- th for headings

![s](https://ictacademy.com.ng/wp-content/uploads/2017/10/HTML-Table-Structure.png)

-  The table element is used to add tables to a web 
page.
-  A table is drawn out row by row. Each row is created 
with the tr element.
-  Inside each row there are a number of cells 
represented by the td element (or th if it is a 
header).
-  You can make cells of a table span more than one row 
or column using the rowspan and colspan attributes.
-  For long tables you can split the table into a thead, 
tbody and tfoot.

##### FUNCTIONS, METHODS & OBJECTS:
![a](https://techvidvan.com/tutorials/wp-content/uploads/sites/2/2020/04/python-methods-vs-functions.jpg)
- Functions allow you to group a set of related 
statements together that represent a single task. 
- Functions can take parameters (informatiorJ required 
to do their job) and may return a value. 
- An object is a series of variables and functions that 
represent something from the world around you. 
- In an object, variables are known as properties of the 
object; functions are known as methods of the object. 
- Web browsers implement objects that represent both 
the browser window and the document loaded into the 
browser window. 
- JavaScript also has several built-in objects such as 
String, Number, Math, and Date. Their properties and 
methods offer functionality that help you write scripts.


### Why problem domains are hard?
The real world is a messy place.  Many of the problem domains we face as programmers are difficult to understand and look completely different depending on your viewpoint.
>Programming is easy if you understand the problem domain

#### What can you do about it?
1-Make the problem domain easier
2-Get better at understanding the problem domain

##### WHAT IS AN OBJECT?
Objects group together a set of variables and functions to create a model 
of a something you would recognize from the real world. In an object, 
variables and functions take on new names. 

* If a variable is part of an object, it is called a 
property. Properties tell us about the object, such as 
the name of a hotel or the number of rooms it has. 
Each individual hotel might have a different name 
and a different number of rooms.

![xx](http://xomino.files.wordpress.com/2013/04/j1.png)

#### The Document Object Model (DOM) s:
specifiehow browsers should create a model of an HTML 
page and how JavaScript can access and update the 
contents of a web page while it is in the browser window.

- **MAKING A MODEL OF THE HTML PAGE:**
When the browser loads a web page, it 
creates a model of the page in memory. 
The DOM specifies the way in which the 
browser should structure this model using 
a DOM tree. 

- The DOM is called an object model 
because the model (the DOM tree) is 
made of objects. 
![aa](https://www.researchgate.net/profile/Olfa-Nasraoui/publication/221417012/figure/fig2/AS:669043992322053@1536523926785/Dom-Tree-of-An-Example-Web-Page.png)

- Each node is an object with methods and properties. 
Scripts access and update this DOM tree (not the source HTML file). 
Any changes made to the DOM tree are reflected in the browser. 
##### WORKING WITH THE DOM TREE:

**STEP 1**: ACCESSTHE ELEMENTS
**STEP 2:** WORK WITH THOSE ELEMENTS
- DOM queries may return one element, or they may return a Nodelist, 
which is a collection of nodes. 

* The browser represents the page using a DOM tree. 

* DOM trees have four types of nodes: document nodes, 
element nodes, attribute nodes, and text nodes. 

* You can select element nodes by their id or cl ass 
attributes, by tag name, or using CSS selector syntax. 
* Whenever a DOM query can return more than one 
node, it will always return a Nadel i st. 
* From an element node, you can access and update its 
content using properties such as textContent and 
i nnerHTML or using DOM manipulation techniques. 
* An element node can contain multiple text nodes and 
child elements that are siblings of each other.
* In older browsers, implementation of the DOM is 
inconsistent (and is a popular reason for using jQuery). 
* Browsers offer tools for viewing the DOM tree . 

![ff](https://divbyte.com/wp-content/uploads/2019/02/html-css.png)
# introduction:
**Is it hard to Learn?**

 The truth 
is, it's not that hard to learn how 
to write web pages and read 
the code used to create them; 
you certainly don't have to be a 
"programmer."
Understanding HTML and CSS 
can help anyone who works 
with the web; designers can 
create more attractive and 
usable sites, website editors can 
create better content, marketers 
can communicate with their 
audience more effectively.

**How People 
Access the Web?**

* **Browsers**: People access websites using 
software called a web browser. 
Popular examples include 
Firefox, Internet Explorer, Safari, 
Chrome, and Opera.
* **Web Servers:**
When you ask your browser for 
a web page, the request is sent 
across the Internet to a special 
computer known as a web 
server which hosts the website.
* **Screen readers:**
 are programs 
that read out the contents of a 
computer screen to a user. They 
are commonly used by people 
with visual impairments.
* **Devices:**People are accessing websites 
on an increasing range of devices 
including desktop computers, 
laptops, tablets, and mobile 
phones.

**How Websites
Are Created?**
All websites use HTML and CSS, but content 
management systems, blogging software, and 
e-commerce platforms often add a few more 
technologies into the mix.


**How the Web Works?**

When you visit a website, the web server 
hosting that site could be anywhere in the 
world. In order for you to find the location of 
the web server, your browser will first connect 
to a Domain Name System (DNS) server.

## structures:
In all kinds of documents, structure is very important in helping 
readers to understand the messages you are trying to convey 
and to navigate around the document. So, in order to learn how 
to write web pages, it is very important to understand how to 
structure documents.
>How Pages Use 
Structure?

The use of headings and 
subheadings in any document 
often reflects a hierarchy of 
information. For example, a 
document might start with 
a large heading, followed by 
an introduction or the most 
important information.

_**HTML Describes
the Structure 
of Pages:**_

![fd](https://www.w3schools.com/htmL/img_notepad.png)

* Tags act like containers. They tell you 
something about the information that lies 
between their opening and closing tags.
 
### Body, Head & Title:
**<body>**

Everything inside this element is 
shown inside the main browser 
window

**<Head>**

Before the <body> element you 
will often see a <head> element. 
This contains information 
about the page (rather than 
information that is shown within 
the main part of the browser 
window that is highlighted in 
blue on the opposite page). 
You will usually find a <title>
element inside the <head>
element.

**<title>**

The contents of the <title>
element are either shown in the 
top of the browser, above where 
you usually type in the URL of 
the page you want to visit, or 
on the tab for that page (if your 
browser uses tabs to allow you 
to view multiple pages at the 
same time).

## Extra Markup:

* **The Evolution of HTML:**

1- HTML 4: Released 1997

2- XHTML 1.0: Released 2000

3- HTML5: Released 2000

**DOCTYPEs:**

Because there have been 
several versions of HTML, each 
web page should begin with a 
DOCTYPE declaration to tell a 
browser which version of HTML 
the page is using

<!DOCTYPE html> : in HTML5


**Comments in HTML:**
<!-- --> 
If you want to add a comment 
to your code that will not be 
visible in the user's browser, you 
can add the text between these 
characters:
<!-- comment goes here -->
It is a good idea to add 
comments to your code because, 
no matter how familiar you 
are with the page at the time 
of writing it, when you come 
back to it later (or if someone 
else needs to look at the code), 
comments will make it much 
easier to understand.

**ID Attribute:**

Every HTML element can carry 
the id attribute. It is used to 
uniquely identify that element 
from other elements on the 
page.

> <p id="pullquote">Every time I view the sea I feel 
 a calming sense of security, as if visiting my 
 ancestral home; I embark on a voyage of seeing.
</p>

**Class Attribute:**

Every HTML element can 
also carry a class attribute. 
Sometimes, rather than uniquely 
identifying one element within 
a document, you will want a 
way to identify several elements 
as being different from the 
other elements on the page. 
For example, you might have 
some paragraphs of text that 
contain information that is more 
important than others and want 
to distinguish these elements, or 
you might want to differentiate 
between links that point to other 
pages on your own site and links 
that point to external sites. 
To do this you can use the 
class attribute. Its value 
should describe the class it 
belongs to. 
><p class="important">For a one-year period from 
 November 2010, the Marugame Genichiro-Inokuma 
 Museum of Contemporary Art (MIMOCA) will host a 
 cycle of four Hiroshi Sugimoto exhibitions.</p>

 **Block Elements:**

 Some elements will always 
appear to start on a new line in 
the browser window. These are 
known as block level elements. 

**Inline Elements:**

Some elements will always 
appear to continue on the 
same line as their neighbouring 
elements. These are known as 
inline elements.
> Examples of inline elements are :
a, b, em, and ,img

**Grouping Text & Elements In a Block:**

The <div> element allows you to 
group a set of elements together 
in one block-level box.
For example, you might create 
a <div> element to contain all 
of the elements for the header 
of your site (the logo and the 
navigation), or you might create 
a <div> element to contain 
comments from visitors.
In a browser, the contents of 
the <div> element will start on 
a new line, but other than this 
it will make no difference to the 
presentation of the page. 

**Grouping Text & Elements Inline:**

The <span> element acts like 
an inline equivalent of the <div>
element. It is used to either:
1. Contain a section of text 
where there is no other suitable 
element to differentiate it from 
its surrounding text
2. Contain a number of inline 
elements
The most common reason why 
people use <span> elements 
is so that they can control the 
appearance of the content of 
these elements using CSS.

**IFrames:**
<iframe>

An iframe is like a little window 
that has been cut into your 
page — and in that window you 
can see another page. The term 
iframe is an abbreviation of inline 
frame.
One common use of iframes 
(that you may have seen on 
various websites) is to embed 
a Google Map into a page. The 
content of the iframe can be any 
html page (either located on the 
same server or anywhere else on 
the web).

* src:

The src attribute specifies the 
URL of the page to show in the 
frame.

* height:

The height attribute specifies 
the height of the iframe in pixels.

* width:

The width attribute specifies 
the width of the iframe in pixe

* scrolling:

The scrolling attribute will 
not be supported in HTML5. In 
HTML 4 and XHTML, it indicates 
whether the iframe should 
have scrollbars or not. This is 
important if the page inside the 
iframe is larger than the space 
you have allowed for it (using the 
height and width attributes). 
Scrollbars allow the user to move 
around the frame to see more 
content. It can take one of three 
values: yes (to show scrollbars), 
no (to hide scrollbars) and auto
(to show them only if needed).

* frameborder:

The frameborder attribute will 
not be supported in HTML5. In 
HTML 4 and XHTML, it indicates 
whether the frame should have 
a border or not. A value of 0
indicates that no border should 
be shown. A value of 1 indicates 
that a border should be shown.

* seamless:

In HTML5, a new attribute 
called seamless can be applied 
to an iframe where scrollbars 
are not desired. The seamless
attribute (like some other new 
HTML5 attributes) does not 
need a value, but you will often 
see authors give it a value of 
seamless. Older browsers 
do not support the seamless
attribute.

**<meta>:**

 The <meta> tag allows you to supply all kinds of 
information about your web page.

*  Escape characters are used to include special 
characters in your pages such as <, >, and ©.
<<<<<<< HEAD

### New Html5 Layout Elements:
![ds](https://slideplayer.com/slide/12052583/69/images/7/NEW+HTML5+LAYOUT+ELEMENTS.jpg)

This example has exactly the 
same structure as seen on the 
previous page. However, many 
of the <div> elements have been 
replaced by new HTML5 layout 
elements.
For example, the header sits 
inside a new <header> element, 
the navigation in a <nav>
element, and the articles are in 
individual <article> elements.
The point of creating these 
new elements is so that web 
page authors can use them to 
help describe the structure of 
the page. For example, screen 
reader software might allow 
users to ignore headers and 
footers and get straight to 
the content. Similarly, search 
engines might place more 
weight on the content in an 
<article> element than that 
in the <header> or <footer>
elements. I think you will agree 
that it also makes the code 
easier to follow.

**Headers & Footers:**

● The main header or footer 
that appears at the top or 
bottom of every page on the 
site.

● A header or footer for an 
individual <article> or 
<section within the pag.

> * HTML5 allows web page authors 
to place an <a> element around 
a block level element that 
contains child elements. This 
allows you to turn an entire block 
into a link.


>* Older browsers that do not 
know the new HTML5 elements 
will automatically treat them as 
inline elements. Therefore, to 
help older browsers, you should 
include the line of CSS on the 
left which states which new 
elements should be rendered as 
block-level elements.

> * To make HTML5 elements work in Internet Explorer 8 
(and older versions of IE), extra JavaScript is needed, 
which is available free from Google

>*   Older browsers that do not understand HTML5 
elements need to be told which elements are 
block-level elements.

## Process & Designe :

*  It's important to understand who your target audience 
is, why they would come to your site, what information 
they want to find and when they are likely to return.

*  Site maps allow you to plan the structure of a site.

*  Wireframes allow you to organize the information that 
will need to go on each page.

*  Design is about communication. Visual hierarchy helps 
visitors understand what you are trying to tell them.

*  You can differentiate between pieces of information 
using size, color, and style. 

*  You can use grouping and similarity to help simplify 
the information you present.

**What is the a script and how do i create one ?**
* A script is a series of instructions that the computer 
can follow in order to achieve a goal. 
* Each time the script runs, it might only use a subset of 
all the instructions. 
* Computers approach tasks in a different way than 
humans, so your instructions must let the computer 
solve the task prggrammatically. 
* To approach writing a script, break down your goal into 
a series of tasks and then work out each step needed 
to complete that task (a flowchart can help). 

**How do computers fit in with the world around them?**
* computers create models of the world using data>
* programmers can write code to say when this event occurs run that code!
* to make webpage interactive you write code that uses the browser models of web page.

**How do i write a script for a page?**
* It is best to keep JavaScript code in its own JavaScript 
file. JavaScript files are text files (like HTML pages and 
CSS style sheets), but they have the . j s extension. 

* The HTML <script> element is used in HTML pages 
to tell the browser to load the JavaScript file (rather like 
the <link> element can be used to load a CSS file). 

* If you view the source code of the page in the browser, 
the JavaScript will not have changed the HTML, 
because the script works with the model of the web 
page that the browser has created.


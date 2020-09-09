# Links

#### What is the link?
Links are created using the `<a>`element. Users can click on anything
between the opening `<a>` tag and the closing `</a>` tag. You specify
which page you want to link to using the href attribute.
FOR Example:
```
<a href="http://www.alaa.com">Alaa</a>

```

>This link contains
>
>>the page the
link takes you to
>>Opening link tag
>>Closing
link tag
> the text the
user clicks on
---

Good news for you
You 😍

 may want to add a list
Of content that links to
Corresponding sections are lower
Down. Or until you want to add
Link from part to bottom
Back to top of page to save
Users don't have to scroll backwards
to the top
that's easy
 Example :
 ```
 <h1 id="top">Film-Making Terms</h1>
<a href="#arc_shot">Arc Shot</a><br />
<a href="#interlude">Interlude</a><br />
<a href="#prologue">Prologue</a><br /><br />
<h2 id="arc_shot">Arc Shot</h2>
<p>A shot in which the subject is photographed by an
 encircling or moving camera</p>
<h2 id="interlude">Interlude</h2>
<p>A brief, intervening film scene or sequence, not
 specifically tied to the plot, that appears
 within a film</p>
<h2 id="prologue">Prologue</h2>
<p>A speech, preface, introduction, or brief scene
 preceding the the main action or plot of a film;
 contrast to epilogue</p>
<p><a href="#top">Top</a></p
````
Summary link

Links are created using the `<a>` element.
- The `<a>` element uses the href attribute to indicate
the page you are linking to.
- If you are linking to a page within your own site, it is
best to use relative links rather than qualified URLs.
-  You can create links to open email programs with an
email address in the "to" field.
-  You can use the id attribute to target elements within
a page that can be linked

## Layout

1. Controls the position of items
2. Create site layouts
3. design for different sized screens

 ### Clearing Floats
clear:
The clear property allows you
to say that no element (within
the same containing element)
should touch the left or righthand sides of a box. It can take
the following values:
 - left
The left-hand side of the box
should not touch any other
elements appearing in the same
containing element.
 - right
The right-hand side of the
box will not touch elements
appearing in the same containing
element.
both
Neither the left nor right-hand
sides of the box will touch
elements appearing in the same
containing element.
 - none
Elements can touch either side.
In this example, the fourth
paragraph has a class called
clear. The CSS rule for this
class uses the clear property
to indicate that nothing should
touch the left-hand side of it. The
fourth paragraph is therefore
moved further down the page
so no other element touches its
left-hand side.
Example:

`HTML`
```
<p class="clear">In 1865, the velocipede (meaning
 "fast foot") attached pedals to the front wheel,
 but its wooden structure made it extremely
 unco
 </P>
 ````
***CSS***
```
 body {
width: 550px;
font-family: Arial, Verdana, sans-serif;
color: #665544;}
p {
width: 200px;
float: left;
margin: 7px;
padding: 10px;
background-color: #efefef;}
.clear {
clear: left;}
```

# Summary:
LAYOUT
- `<div>` elements are often used as containing elements
to group together sections of a page.
-  Browsers display pages in normal flow unless you
specify relative, absolute, or fixed positioning.
-  The float property moves content to the left or right
of the page and can be used to create multi-column
layouts. (Floated items require a defined width.)
-  Pages can be fixed width or liquid (stretchy) layouts.
-  Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).
-  Grids help create professional and flexible designs.
- CSS Frameworks provide rules for common tasks.
-  You can include multiple CSS files in one page.

## JS

# FUNCTION:

WHAT IS A FUNCTION? 
Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of statements). 

A BASIC FUNCTION :
````
var msg = 'Sign up to receive our newsletter for 10% off!';
function updateMessage() {
var el = document.getElementByld('message'};
el .textContent = msg;
}
updateMessage(}; 
````

# ANONYMOUS FUNCTIONS
&  FUNCTION EXPRESSIONS 

Expressions produce a value. They can be used where values are expected.
If a function is placed where a browser expects to see an expression,
(e.g., as an argument to a function), then it gets treated as an expression. 

# FUNCTION DECLARATION 

A function declaration creates a function that you
can call later in your code. It is the type of function
you have seen so far in this book.
In order to call the function later in your code, you
must give it a name, so these are known as named
functions. Below, a function called area() is
declared, which can then be called using its name.

# FUNCTION EXPRESSION

If you put a function where the interpreter would
expect to see an expression, then it is treated as an
expression, and it is known as a function expression.
In function expressions, the name is usually omitted.
A function with no name is called an anonymous
function. Below, the function is stored in a variable
called area. It can be called like any function created
with a function declaration. 

----
Reasons for Pair Programming:

How does pair programming work?

  Pair programming usually involves two roles: the driver and the navigator.
The driver is the programmer who writes and is the only one who has his hand on the keyboard.
  , The driver software manages the text editor, switching files, version control and of course writing. Navigator uses their words to direct the driver but provides no direct input to the computer. Navigator thinks about the big picture, what comes next, and how the algorithm can be converted into code, while looking for typos or errors.

  How does pair programming work?

  
   Pair programming usually involves two roles: the driver and the navigator.
The driver is the programmer who writes and is the only one who gets to put his hand on the keyboard.
   -Player runs a text editor, file switching, version control, and of course writing. Navigator uses their words to guide the driver but does not provide direct input to the computer. Navigator thinks about the big picture, what comes next, and how the algorithm can be converted into code, while looking for misspellings or errors.


# Ordered Lists & Unordered Lists
---

 - How to use them:
 The unordered list is created
with the  `<ul>`  element.

 - Each item in the list is placed
between an opening `<li>` tag
and a closing `</li>` tag. (The li
stands for list item.)
***HTML***
```
{
    <ul>
<li>1kg King Edward potatoes</li>
<li>100ml milk</li>
<li>50g salted butter</li>
<li>Freshly grated nutmeg</li>
<li>Salt and pepper to taste</li>
</ul>
}
```
# What hashtag are we using to create?
 >**For you**, here is an example that shows the ordered and unordered list
 ```
 }
 <html>
<head>
 <title>Lists</title>
</head>
<body>
 <h1>Scrambled Eggs</h1>
 <p>Eggs are one of my favourite foods. Here is a
 recipe for deliciously rich scrambled eggs.</p>
 <h2>Ingredients</h2>
 <ul>
 <li>2 eggs</li>
 <li>1tbs butter</li>
 <li>2tbs cream</li>
 </ul>
 <h2>Method</h2>
 <ol>
 <li>Melt butter in a frying pan over a medium
 heat</li>
 <li>Gently mix the eggs and cream in a bowl</li>
 <li>Once butter has melted add cream and eggs</li>
 <li>Using a spatula fold the eggs from the edge of
 the pan to the center every 20 seconds (as if
 you are making an omelette)</li>
 <li>When the eggs are still moist remove from the
 heat (it will continue to cook on the plate
 until served)</li>
 </ol>
</body>
</html>
}
```
## Boxes:

(`Let's learn a little bit about the Boxes`)
 - First : width,height
 ### You can use the height and width properties. The most popular way to define a square's size is to use pixels, percentages, or ems. Traditionally
  ✅ 

  In the example on the right, you
can see that a containing `<div>`
element is used which is 222
pixels wide by 222 pixels high.
Inside of this is a paragraph
that is 75% of the width and
height of the containing element.
This means that the size of the
paragraph is 225 pixels wide by
225 pixels high.
````
}
div.box {
height: 222px;
width: 222px;
background-color: #bbbbaa;}
p {
height: 80%;
width: 75%;
background-color: #0088dd;}
````
}
### margin
The margin property controls
the gap between boxes. Its value
is commonly given in pixels,
although you may also use
percentages or ems.
If one box sits on top of another,
margins are collapsed , which
means the larger of the two
margins will be used and the
smaller will be disregarded.
Please note: If the width of a box
is specified then the margin is
added to the width of the box.
You can specify values for each
side of a box using:
---- 
margin-top
margin-right
margin-bottom
margin-left
----

# js
### VALU ES IN ARRAYS

Values in an array are accessed as if they are in
a numbered list. It is important to know that the
numbering of this list starts at zero (not one). 
 
  ## `Summary`
- Conditional statements allow your code to make
decisions about what to do next.

- Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands.

 - Logical operators allow you to - combine more than one
set of comparison operators.

 - if ... else statements allow you to run one set of code
if a condition is true, and another if it is false.

 - switch statements allow you to compare a value
against possible outcomes (and also provides a default
option if none match).

 - Data types can be coerced from one type to another.

- All values evaluate to either truthy or falsy.
 - There are three types of loop: for, while, and
do ... while.Each repeats a set of statements. 333
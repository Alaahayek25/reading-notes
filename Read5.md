# Addiing Amges

 There are reasons why you should include an image on your site or even an infographic
And I know that you do not know 🥺

So I will teach you what I learned🔥💛

> let's go

To add an image into the page
you need to use an `<img>`
-
`<src>`
element.
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. 

`alt`
This provides a text description
of the image which describes the
image if you cannot see it.

`<img src=`

![a](./img/download.jpg)

` alt="A blue bird"/>`

### Height & Width of images
 height:
This specifies the height of the
image in pixels

width:
This specifies the width of the
image in pixels.
Images often take longer to
load than the HTML code that
makes up the rest of the page.
It is, therefore, a good idea to
specify the size of the image
so that the browser can render
the rest of the text on the page
while leaving the right amount of
space for the image that is still
loading.

` example`
{```img src="images/quokka.jpg" alt="A family of
 quokka" width="500" height="350" />```}


> The size of images is increasingly
being specified using CSS rather
than HTML 


## Old Code: Aligning Images Horizontally
I have discussed it here because
you are likely to come across
it if you look at older code, and
because some visual editors still
insert this attribute when you
indicate how an image should be
aligned.
The align attribute can take
these horizontal values:

* left

This aligns the image to the left
(allowing text to flow around its
right-hand side).

`<p><img src=` 

![brid](./img/download.jpg)There are around 10,000 living species of birds that inhabit different ecosystems from the Arctic to the Antarctic. Many species undertake long distance annual migrations, and many more perform shorter irregular journeys.`</p>`




 ` width="100"
height="100" align="left" />`
]



* right

This aligns the image to the right
(allowing text to flow around its
left-hand side)
`<p><img src="images/bird.gif" alt="Bird" width="100"
height="100" align="right" />`

Summary:

IMAGES
- The <img> element is used to add images to a
web page.
- You must always specify a src attribute to indicate the
source of an image and an alt attribute to describe the
content of an image.
-  You should save images at the size you will be using
them on the web page and in the appropriate format.
-  Photographs are best saved as JPEGs; illustrations or
logos that use flat colors are better saved as GIFs.

---
# Color
Background Color:
CSS treats each HTML element
as if it appears in a box, and the
background-color property
sets the color of the background
for that box.


```
body {
background-color: rgb(200,200,200);}
h1 {
background-color: DarkCyan;}
h2 {
background-color: #ee3e80;}
p {
background-color: white;}
```

`Example`

# COLOR

```
<!DOCTYPE html>
<html>
<head>
 <title>Color</title>
 <style type="text/css">
 body {
 background-color: silver;
 color: white;
 padding: 20px;
 font-family: Arial, Verdana, sans-serif;}
 h1 {
 background-color: #ffffff;
 background-color: hsla(0,100%,100%,0.5);
 color: #64645A;
 padding: inherit;}
 p {
 padding: 5px;
 margin: 0px;}
 p.zero {
 background-color: rgb(238,62,128);}
 p.one {
 background-color: rgb(244,90,139);}
 p.two {
 background-color: rgb(243,106,152);}
 p.three {
 background-color: rgb(244,123,166);}
 p.four {
 background-color: rgb(245,140,178);}
 p.five {
 background-color: rgb(246,159,192);}
 p.six {
 background-color: rgb(245,176,204);}
 p.seven {
 background-color: rgb(0,187,136);}
 p.eight {
 background-color: rgb(140,202,242);}
 p.nine {
 background-color: rgb(114,193,240);}
 ````

 # Summary: 

COLOR

-  Color not only brings your site to life, but also helps
convey the mood and evokes reactions.
-  There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
- Color pickers can help you find the color you want.
- It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).
-  CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
-  CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.
 --- 
 # Text    

 The font weight not only adds
emphasis but can also affect
the amount of white space and
contrast on a page.          
 
WEIGHT:         
**BOLD**
Light.
##### Medium.
Black.

Italic fonts have a cursive aspect
to some of the lettering. Oblique
font styles take the normal style
and put it on an angle.


# STYIE:
Normal.
*Italic*.
Oblique.

```
<!DOCTYPE html>
<html>
<head>
 <title>Font Family</title>
 <style type="text/css">
 body {
 font-family: Georgia, Times, serif;}
 h1, h2 {
 font-family: Arial, Verdana, sans-serif;}
 .credits {
 font-family: "Courier New", Courier,
 monospace;}
 </style>
</head>
<body>
 <h1>Briards</h1>
 <p class="credits">by Ivy Duckett</p>
 <p class="intro">The <a class="breed"
 href="http://en.wikipedia.org/wiki/
 Briard">briard</a>, or berger de brie, is
 a large breed of dog traditionally used as
 a herder and guardian of sheep...</p>
</body>
</html>
```
- There are properties to control the choice of font, size,
weight, style, and spacing.
-  There is a limited choice of fonts that you can assume
most people will have installed.
-  If you want to use a wider range of typefaces there are
several options, but you need to have the right license
to use them.
-  You can control the space between lines of text,
individual letters, and words. Text can also be aligned
to the left, right, center, or justified. It can also be
indented.
-  You can use pseudo-classes to change the style of an
element when a user hovers over or clicks on text, or
when they have visited a link.

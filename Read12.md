allback content : the canvas element supported by the old version of browser not like the img tag, and this make work easier to the developer because it is important to make a fallback always. to make this fall back type a text inside the canvas element , if the browser support canvas then it will ignore the text and vise versa. also the canvas need a closing tag like `</canvas>.`

### Applying styles and colors
To apply colors to a shape the user can apply the following properties:

`fillStyle = color` Sets the style used when filling shapes. `strokeStyle = color` Sets the style for shapes’ outlines. `globalAlpha = transparencyValue` Applies the specified transparency value.

Line styling options include:

l`ineWidth = value` Sets the width of lines drawn the future. `lineCap = type` Sets the appearance of the ends of lines. `lineJoin = type` Sets the appearance of the “corners” where lines meet. `miterLimit = value` Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes. getLineDash() Returns the current line dash pattern array containing an even number of non-negative numbers. setLineDash(segments) Sets the current line dash pattern. `lineDashOffset = value` Specifies where to start a dash array on a line.

#### drawing rectangular : canvas support rectangular shapes and paths. so to draw a rect. see the steps bellow :

- use a fillRect function to draw filled rectangle.

- use strokeRect function to draw rectanglar outline.
- use clearRect to clears the specified rectangular area.
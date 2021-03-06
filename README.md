# Processing

# Contents
{:.no_toc}

* TOC
{:toc}


## Links

- [processing.org](https://processing.org) [[reference](https://processing.org/reference/)]

##### Sharing and Ideas

- [OpenProcessing](http://openprocessing.org/)
- [Sketchpad](http://sketchpad.cc/) [[p5.js Sketchpad Studio](http://p5js.sketchpad.cc/)]
[[blog](http://blog.sketchpad.cc/)]

##### Blogs, etc.

- [Processing Month](http://vormplus.be/blog/article/processing-month) - daily sketches which build up


***

# Reference


Processing is a library on top of Java.

## Versions

[Changes in Processing 3](https://github.com/processing/processing/wiki/Changes-in-3.0)

Including:

- `fullScreen()` function added, and should be first line of `setup()` (or `settings()`)
- `displayWidth` / `displayHeight` are deprecated
- `FX2D` renderer - which is on its way to becoming the default
- `settings()` - for when you are using Processing without the preprocessor (e.g. from Eclipse)


## Basics

The two main functions are `setup()` and `draw()`.

`size()`/`fullScreen()`

`background()`

If you are


## Draw Loop

`frameRate()`


`noLoop()`/`loop()`
`redraw()`

***

## Data Types


## Variables



`focused`
`frameCount`
`frameRate`

`height`
`width`

Note `width` and `height` may be assigned to so be careful, esp. if using these names as class fields! It's not entirely clear, for example, how `PApplet.width` corresponds to `PApplet.g.width`.


***

## Colors

`color()`

`colorMode()`


`stroke()`
`noStroke()`

`fill()`
`noFill()`

##### Extracting Color Information

from `color` variable...

- `red()`/`green()`/`blue()`/`alpha()`
- `brightness()`/`hue()`/`saturation()`


## Shapes

PShape

### 2D Primitives

1. `point()`
2. `line()`
3. `ellipse()` ... `ellipseMode()`
4. `arc()`
5. `rect()` ... `rectMode()`
6. `quad()`
7. `triangle()`

`strokeWeight()`
`strokeCap()`
`strokeJoin()`

---

?:
curve
curvePoint
curveVertex
bezier
bezierPoint


## Style

`pushStyle()`/`popStyle()`

...


## Transformations

`pushMatrix()`/`popMatrix()`

### 2D Transformations

1. `translate()`
2. `rotate()` ... `radians()`
3. `scale()`

### 3D Transformations

1. call translate with 3 arguments
2. call rotate with 3 arguments
3. `rotateX()`/`rotateY()`/`rotateZ()`



### 3D


***

Images, SVG, and Shapes and loading?

***


## Interaction

`mousePressed()`

***


It seems that starting in version 3 `PApplet` no longer inherits from Java `Applet`.



# Chart.js(Canvas)

A chart is a graphical representation for data visualization, in which "the data is represented by symbols, such as bars in a bar chart, lines in a line chart, or slices in a pie chart". A chart can represent tabular numeric data, functions or some kinds of quality structure and provides different info.

## How do you create a chart in JavaScript?

You can create responsive charts with JSCharting through a couple simple steps:

- Define a <div> tag in the HTML file with a unique id.
- Provide this id, data, and any other options when calling JSC. Chart() in the JavaScript file.

### Create the Context Using JavaScript

  The first thing we need in the JavaScript is the context of our chart, which is basically just a fancy way of saying the element that we're going to apply the chart to, which is our canvas object.

So we're going to create a variable called context, or ctx for short, and we'll set this equal to that canvas object. And we're going to point to that canvas object using jQuery. So I'm gonna use the dollar sign and parentheses, and inside the parentheses, we'll have a set of quotation marks, and inside the quotation marks, we'll use the CSS selector for that canvas object. And we're pointing to that object's ID, so we're going to type # and then the ID, which is line-chart, and then add a semi-colon at the end of that statement.

### Add the JavaScript Code to Plot the Chart

Now that we've done that, we just need one more line of code to create our chart. Now it's going to be a complex line of code, and it's actually going to end up looking like multiple lines, but it's just going to be one JavaScript statement.

## Basic usage of canvas

This looks a lot like the <img> element, the only difference is that it doesn’t have the src and alt attributes. The <canvas> element has only two attributes - width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size. (If your renderings seem distorted, try specifying your width and height attributes explicitly in the <canvas> attributes, and not with CSS.)

The id attribute isn’t specific to the <canvas> element but is one of the default HTML attributes which can be applied to (almost) every HTML element (like class for instance). It’s always a good idea to supply an id because this makes it much easier to identify it in our script.

The <canvas> element can be styled just like any normal image (margin, border, background, etc). These rules however don’t affect the actual drawing on the canvas. We’ll see how this is done later in this tutorial. When no styling rules are applied to the canvas it will initially be fully transparent.

Fallback content
Because the <canvas> element is still relatively new, we need a means of providing fallback content when a browser doesn’t support the element.

This is very straightforward: we just provide alternative content inside the canvas element. Browsers which don’t support <canvas> will ignore the container and render the fallback content inside it. Browsers which do support <canvas> will ignore the content inside the container, and just render the canvas normally.

> For example, we could provide a text description of the canvas content or provide a static image of the dynamically rendered content. This can look something like this:

## Required *</canvas>* tag

In the Apple Safari implementation, <canvas> is an element implemented in much the same way <img> is; it does not have an end tag. However, for <canvas> to have widespread use on the web, some facility for fallback content must be provided. Therefore, Mozilla’s implementation requires an end tag (</canvas>).

If fallback content is not needed, a simple <canvas id="foo" ...></canvas> will be fully compatible with both Safari and Mozilla – Safari will simply ignore the end tag.

If fallback content is desired, some CSS tricks must be employed to mask the fallback content from Safari (which should render just the canvas), and also to mask the CSS tricks themselves from IE (which should render the fallback content).

### The rendering context

<canvas> creates a fixed size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. We’ll focus on the 2D rendering context. Other contexts may provide different types of rendering; for example, there is a 3D context (“experimental-webgl”) based on OpenGL ES.

The <canvas> is initially blank, and to display something a script first needs to access the rendering context and draw on it. The canvas element has a DOM method called getContext, used to obtain the rendering context and its drawing functions. getContext() takes one parameter, the type of context.

### Drawing shapes with canvas

Browsers give us several ways to display graphics. The simplest way is to use styles to position and color regular DOM elements. This can get you quite far, as the game in the previous chapter showed. By adding partially transparent background images to the nodes, we can make them look exactly the way we want. It is even possible to rotate or skew nodes with the transform style.

But we’d be using the DOM for something that it wasn’t originally designed for. Some tasks, such as drawing a line between arbitrary points, are extremely awkward to do with regular HTML elements.

There are two alternatives. The first is DOM-based but utilizes Scalable Vector Graphics (SVG), rather than HTML. Think of SVG as a document-markup dialect that focuses on shapes rather than text. You can embed an SVG document directly in an HTML document or include it with an <img> tag.

The second alternative is called a canvas. A canvas is a single DOM element that encapsulates a picture. It provides a programming interface for drawing shapes onto the space taken up by the node. The main difference between a canvas and an SVG picture is that in SVG the original description of the shapes is preserved so that they can be moved or resized at any time. A canvas, on the other hand, converts the shapes to pixels (colored dots on a raster) as soon as they are drawn and does not remember what these pixels represent. The only way to move a shape on a canvas is to clear the canvas (or the part of the canvas around the shape) and redraw it with the shape in a new position.

![img](https://cdn-images-1.medium.com/max/490/1*TZQZ6ComlrvPZPHz0cjDbQ.png)

## Applying styles and color

This part of the canvas tutorial explains how to color and style canvas shapes. It provides examples for simple coloring and line styles but also for more complex styles likes gradients.

In the chapter about drawing shapes only the default line and fill styles were used. In this chapter we will explore all the canvas options we have at our disposal to make our drawings a little more attractive.

## color

Up until now we’ve only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

strokeStyle is used for setting the shape outline color and fillStyle is for the fill color. These properties can be set to a string representing a CSS color value, a gradient object, or a pattern object. By default, the stroke and fill color are set to black (CSS color value #000000).

If you set the strokeStyle and/or fillStyle property, the new value becomes the default for all properties being drawn from then on. For every object you want in a different color, you will need to reassign the fillStyle or strokeStyle property with the new color value before that object is rendered.

![img](https://sprdblog-res.cloudinary.com/image/upload/v1555486825/BP_CanvaColors_teaser_fpyggy.jpg)

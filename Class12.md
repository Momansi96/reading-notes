# Class12 

[Return to home page](https://momansi96.github.io/reading-notes/). 

## CREATE  ANIMATED CHARTS WITH CHART.JS. 

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create, A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy. 

#### Setting up: 

The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in. Then create a new html page and import the script. 

#### Drawing a line chart: 

To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page: `<canvas id="buyers" width="600" height="400"></canvas>`. 

Next, we need to write a script that will retrieve the context of the canvas, so add the script tag to the foot of your body element. 

Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart. 

#### Drawing a pie chart: 

First, we need the canvas element: `<canvas id="countries" width="600" height="400"></canvas>`. 

Next, we need to get the context and to instantiate the chart. 

Next we need to create the data. This data is a little different to the line chart because the pie chart is simpler, we just need to supply a value and a color for each section. 

#### Drawing a bar chart: 

Finally, let’s add  a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added. First, we add the canvas element: `<canvas id="income" width="600" height="400"></canvas>`. 

Next, we retrieve the element and create the graph, And finally, we add in the bar chart’s data. 

## Chart.js: 

#### Getting Started: 

It's easy to get started with Chart.js. All that's required is the script included in your page along with a single `<canvas>` node to render the chart.

First, we need to have a canvas in our page. It's recommended to give the chart its own container for responsiveness.

Now that we have a canvas we can use, we need to include Chart.js in our page: `<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>`. 

Now, we can create a chart. We add a script to our page, Finally, render the chart using our configuration. 

## Canvas Element: 

#### Basic usage of canvas: 

At first sight a `<canvas>` looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the `<canvas>` element has only two attributes, width and height. These are both optional and can also be set using DOM properties. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

The `<canvas>` element can be styled just like any normal image (margin, border, background…). These rules, however, don't affect the actual drawing on the canvas.

* Fallback content: The `<canvas>` element differs from an `<img>` tag in that, like for `<video>`, `<audio>`, or `<picture>` elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.

* Required `</canvas>`: As a consequence of the way fallback is provided, unlike the `<img>` element, the `<canvas>` element requires the closing tag (`</canvas>`). If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed. 

#### The rendering context: 

The `<canvas>` element creates a fixed-size drawing surface that exposes one or more rendering contexts, which are used to create and manipulate the content shown. 

The canvas is initially blank. To display something, a script first needs to access the rendering context and draw on it. The `<canvas>` element has a method called getContext(), used to obtain the rendering context and its drawing functions





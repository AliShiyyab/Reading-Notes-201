# Docs for the HTML `<canvas>` Element & Chart.js

# Chart.js

**First, we need to have a canvas in our page. It's recommended to give the chart its own container for responsiveness.**

 `<div>`

 `<canvas id="myChart"></canvas>`

 `</div>`

 **Now that we have a canvas we can use, we need to include Chart.js in our page.**

 `<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>`

 ## Usage

**Chart.js can be used with ES6 modules, plain JavaScript, and module loaders.**

 ## Creating a Chart

*To create a chart, we need to instantiate the `Chart` class. To do this, we need to pass in the node, jQuery instance, or 2d context of the canvas of where we want to draw the chart. Here's an example.*

## Drawing a line chart

* To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page: ``<canvas id="buyers" width="600" height="400"></canvas>``

* Next, we need to write a script that will retrieve the context of the canvas, so add this to the foot of your body element: `<script>var buyers = document.getElementById('buyers').getContext('2d');new Chart(buyers).Line(buyerData);</script>`

## Drawing a pie chart

Our line chart is complete, so let’s move on to our pie chart. First, we need the canvas element: `<canvas id="countries" width="600" height="400"></canvas>`

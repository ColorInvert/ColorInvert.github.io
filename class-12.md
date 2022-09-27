# Daily Reading 12



#### What does the `<canvas>` allow a developer to acheive?

Manual drawing of 2D imagry through the use of simple shape definitions, and their properties.

#### What is the importance of the closing `</canvas>` tag?

Anything that is after the opening canvas tag, that does not relate directly TO canvas, will be considered "fallback content" and will only be displayed if canvas fails to load entirely.

#### Explain what the getContext() method does.

getContext() will tell the canvas which variant to use. Different canvases have different properties and capabilities. 

#### What is Chart.js and how it can be brought into your project?

Chart.js is a javascript plugin that utilizes the `<canvas>` element in order to assist the developer in making reactive, and informative charts. Chart.js, being a plugin, requires some initial setup for the project it is used in. It must be first downloaded, unzipped into the directory you will be working in, and finally, referenced using a `<script>` tag in the HTML head.

#### List 3 different Chart types you can create using Chart.js.

Line charts, pie charts, and bar charts.

#### What are some advantages to displaying data via a chart over a table?

Some data simply lends itself to charts better than a table, especially if relative ratios are of importance, and if there's many many data points, where seeing the specific and exact value of a singular datum is less important.

#### How could Chart.js aid your previously created applications visually?

Odd Duck would very blatantly benifit from the addition of a chart for the final data. All of the product views and clicks are important to understand in *context of each other.* and having it in a table, or worse, a simple list, provides very little intuitive insight in how the ratios of clicks per view vary between the products shown.


#### [Back To Main Page.](https://colorinvert.github.io/reading-notes/)
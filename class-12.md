# Class 12

* chart.js is a javascript plugin that uses html5's `<canvas>` to draw all types of charts easily
* to use chart.js first you need to install it.
* the guide uses filed called `chart.min.js` **the guide is outdated** and the demo is producing errors in console .
* supposedly the rest is a multi simple-chart examples using chart.js but its out dated.
* found some success using the official chart.js examples in their guide.

***

## Canvas element

* `<canvas>` element  looks like `<img>` when rendered with different atrr.
* all CSS styles used on `<img>` can be used to style `<canvas>`.
* The `<canvas>` element creates a fixed-size drawing surface that exposes one or more rendering contexts
* `getContext()` is a `<canvas>` JS method that sets what is the drawing context `'2d'` value sets for `CanvasRenderingContext2D`.

```HTML5
<html>
  <head>
    <meta charset="utf-8"/>
    <title>Canvas tutorial</title>
    <script type="text/javascript">
      function draw() {
        var canvas = document.getElementById('tutorial');
        if (canvas.getContext) {
          var ctx = canvas.getContext('2d');
        }
      }
    </script>
    <style type="text/css">
      canvas { border: 1px solid black; }
    </style>
  </head>
  <body onload="draw();">
    <canvas id="tutorial" width="150" height="150"></canvas>
  </body>
</html>
```

> example from : <https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage>, quotation date 28/2/2021.

* the upper is a simple empty rectangle sized 150*150  created and styled with in `<canvas>` structure.

***

## Drawing with `<canvas>`

* canvas only support two primitive shapes rectangles and paths.

* there are three options to draw rectangles:
   1. `fillRect(x, y, width, height)` draws filled rectangle.
   2. `strokeRect(x, y, width, height)` draws rectangular outline.
   3. `clearRect(x, y, width, height)` clear rectangular area makes it full transparent.

* x and y specify the position on the canvas (relative to the origin) of the top-left corner of the rectangle.

* to draw using paths you need to:
   1. First, you create the path.
   2. Then you use [drawing commands](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D#paths) to draw into the path.
   3. Once the path has been created, you can stroke or fill the path to render it


# Chart.js API

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool.

A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page.

## Setting up

The first thing we need to do is download Chart.js.

```
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="utf-8" />
        <title>Chart.js demo</title>
        <script src='Chart.min.js'></script>
    </head>
    <body>
    </body>
</html>
```

### three type of chart we use the most. 

1. Drawing a line chart

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQhmsL7QKvZYN4E4QeLXaCRD1cVcewyu8y4Jw&usqp=CAU)

2. Drawing a pie chart 

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQNjrRJ9_dqMGy_TlKEZ3V5WMf_MfqM5bNdJA&usqp=CAU)

3. Drawing a bar chart

![](https://static.packt-cdn.com/products/9781785284892/graphics/B04673_06_05.jpg)



# Chart.js

## Creating a Chart 

All that's required is the script included in your page along with a single` <canvas> `node to render the chart.

```
<canvas id="myChart" width="400" height="400"></canvas>
<script>
var ctx = document.getElementById('myChart').getContext('2d');
var myChart = new Chart(ctx, {
    type: 'bar',
    data: {
        labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
        datasets: [{
            label: '# of Votes',
            data: [12, 19, 3, 5, 2, 3],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        scales: {
            y: {
                beginAtZero: true
            }
        }
    }
});
</script>
```

## License

Chart.js is available under the MIT license


# Basic usage of canvas 

## The canvas element 

 the `<canvas>`element has only two attributes, width and height. These are both optional and can also be set using DOM properties. 

 The id attribute isn't specific to the` <canvas> `element .

 ## Required </canvas> tag 

 As a consequence of the way fallback is provided, unlike the `<img>` element, the` <canvas> `element requires the closing tag`(</canvas>)`.


# Drawing shapes with canvas

1. The grid

![](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes/canvas_default_grid.png)

2. Drawing rectangles

![](https://mdn.mozillademos.org/files/245/Canvas_rect.png)

3.  Drawing paths
 
    - beginPath()
    - Path methods
    - closePath()
    - stroke()
    - fill()

4. Drawing a triangle

![](https://mdn.mozillademos.org/files/9847/triangle.png)

# Applying styles and colors 

Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

`fillStyle = color`
Sets the style used when filling shapes.

![](https://mdn.mozillademos.org/files/5417/Canvas_fillstyle.png)

`strokeStyle = color`
Sets the style for shapes' outlines.

![](https://mdn.mozillademos.org/files/253/Canvas_strokestyle.png)


# Drawing text

The canvas rendering context provides two methods to render text:

`fillText(text, x, y [, maxWidth])`
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRcU84mrt6zaog6LHoclS58ZzGM-KEoze5l4Q&usqp=CAU)

`strokeText(text, x, y [, maxWidth])`
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTvBs3ANlamcaw09tXNKRSRZUXWmiO7zqCHmw&usqp=CAU)


## Styling text

![](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_text/baselines.png)
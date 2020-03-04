# SimpleCanvaChart-JS
An improved version of 'SimpleChartJS' using canva.

## How to use this?

Include the 'simplecanvachart.js' file in you page, after, create a div to contains the chart. In other script tag (JavaScript) call the function SimpleCanvaChart with these arguments:

SimpleCanvaChart(title,div,data,colors,height,width,type);
- Title(string): text that will appear in top of chart.
- Div(object): div that will contains the chart.
- Data: bidimensional array that contains the values to plot in chart.
- Colors: linear array that contains the colors of points in chart (same type of colors of CSS).
- Height and Width: dimensions of the chart.
- Type: an linear array with two boolean positions where the first position will draw the rectangles and the second will draw the lines.

Example:
```
SimpleCanvaChart('Gráfico de teste',div,data,color,500,500,[true,true]);
```

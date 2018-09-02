
## About
Draw.js is a basic 2d canvas graph library, which is under development currently.





## Get started
Add following script into your HTML header 
```html
<script src="https://drawjs.github.io/CDN/draw/draw.js"></script>
```
Add a canvas in html, like:
```html
<canvas id="myCanvas"></canvas>
```
Then you can just use it
```js
const canvas = document.getElementById( 'myCanvas' )
const draw = window.Draw( canvas )
```



## Features
### Creating an Element
##### Shapes
* Line
* Polyline

<iframe src="https://drawjs.github.io/CDN/iframes/drawExamples/shape/line/index.html"></iframe>


* Rect

<iframe src="https://drawjs.github.io/CDN/iframes/drawExamples/shape/rect/index.html"></iframe>

* Circle
<iframe src="https://drawjs.github.io/CDN/iframes/drawExamples/shape/circle/index.html"></iframe>

* Polygon, Rounded Polygon
<iframe src="https://drawjs.github.io/CDN/iframes/drawExamples/shape/polygon/index.html"></iframe>



Configure curve rate:
<iframe src="https://drawjs.github.io/CDN/iframes/drawExamples/shape/polygon-curve-rate/index.html"></iframe>



##### Image


##### Text



### Dragging, Rotating and Sizing Element


### Transforming Element with Segments and Handles

### Selecting Element


### Zooming and Panning Viewport




### MiniMap

### Exporting and Importing Data


## Example
### [Data-Sandboxie](https://drawjs.github.io/CDN/data-sandboxie/example/index.html)
An interactive graph for multi-level data combination. Here is a [demo](https://drawjs.github.io/CDN/data-sandboxie/example/index.html).
[![example image](https://drawjs.github.io/CDN/data-sandboxie/example.png)](https://drawjs.github.io/CDN/data-sandboxie/example/index.html)



## Future
Draw.js is still under development now. It will support more elements and more awesome features in the future. Let's look forward to it. And if you had any questions or advices, you could submit it in issues.


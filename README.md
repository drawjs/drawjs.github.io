<style>     
  Hi, welcome to visit the official introduction of draw.js. However, this article may look strange because it's been used for generating official website by github jekyll themes. You can visit official website here: https://drawjs.github.io.
</style>     

<style>     
iframe {
  width: 100%;
  height: 300px;
  border: none;
}
</style>    

## About
Draw.js is a basic 2d canvas graph library, which is under development currently.





## Get started
### CDN
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

### NodeJS
It also supports NodeJS use
```bash
npm install ts-draw --save-dev
```
Next import it with
```js
require( 'ts-draw' )
```
or
```js
import 'ts-draw'
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
<iframe src="https://drawjs.github.io/CDN/iframes/drawExamples/image/index.html"></iframe>


##### Text
<iframe src="https://drawjs.github.io/CDN/iframes/drawExamples/text/index.html"></iframe>



### Dragging, Rotating and Sizing Element
<iframe src="https://drawjs.github.io/CDN/iframes/drawExamples/draggingRotatingSizing/index.html"></iframe>



### Transforming Element with Segments and Handles
<iframe src="https://drawjs.github.io/CDN/iframes/drawExamples/transforming/index.html"></iframe>



### Selecting Element
Drag a selection area to select elements
<iframe src="https://drawjs.github.io/CDN/iframes/drawExamples/selection/index.html"></iframe>



### Zooming and Panning Viewport
Zoom
: Scroll mouse to zoom in or zoom out

Pan
: Press `Space` or click mouse's center key to pan viewport



### MiniMap
<iframe src="https://drawjs.github.io/CDN/iframes/drawExamples/miniMap/index.html"></iframe>




## Example
### [Data-Sandboxie](https://github.com/drawjs/data-sandboxie)
An interactive graph for multi-level data combination, being used in company's commercial product. Here is a [demo](https://drawjs.github.io/CDN/data-sandboxie/example/index.html).
[![example image](https://drawjs.github.io/CDN/data-sandboxie/example.png)](https://drawjs.github.io/CDN/data-sandboxie/example/index.html)



## Future
Draw.js is still under development now. It will support more elements and more awesome features in the future. Let's look forward to it. And if you had any questions or advices, you could submit it in issues.

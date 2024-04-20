In BlueGrid standard edition, shape tools are tools to draw almost any type of 2D shapes that are usually used in construction blueprints, such as line, rectangle, polygon, spline, path, shapes with wholes in side...etc. All shapes drawn using shape tools have metric values and can subscribe to material tags. Metric values are derived from shapes as rendered visuals (what you see is what you get).
While drawing, to get the best accuracy, point snaps should be on.

### Line tool 
A line is formed from two different points. To draw a line, select line tool, and pick two different points.
![type:video](https://www.youtube.com/embed/jlWXRpokY8M?si=lifopBsON2MKEDrq)
<figcaption>Line tool</figcaption>

### Polyline tool
A polyline is formed from at least two points (vertices). The number of polyline vertices are infinite. To draw a polyline, select polyline tool, and pick vertices of the polyline. To finish drawing the polyline, right click, the last vertex (floating vertex) will be canceled.
![type:video](https://www.youtube.com/embed/sJQnOlWITtQ)
<figcaption>Polyline tool</figcaption>

### Polygon tool
A polygon is formed from at least three vertices. The number of polygon vertices are infinite. A polygon is quite similar to a polyline, except that it is always a close shape, meaning the start vertex and the end vertex are identical. To draw a polygon, select polygon tool, and pick vertices. To finish drawing the polygon, right click, the last floating vertex will be canceled.
![type:video](https://www.youtube.com/embed/j86wBFtKKik)
<figcaption>Polygon tool</figcaption>

### Rectangle tool
To draw a rectangle pick two opposite corners of the rectangle. 
![type:video](https://www.youtube.com/embed/gHu_S0vmN6A?si=5fkFvPhGMs_Zo7hv)
<figcaption>Rectangle tool</figcaption>

### Circle tool
BlueGrid provide two options draw a circle: The first option allows you to draw a circle by picking two points, one is the center and the other is any point on the perimeter of the circle. The second option allows you to draw a circle of picking three different 3 points on the perimeter of the circle.
![type:video](https://www.youtube.com/embed/0hyQ1GY32Ek?si=-Ax05IJfbSqHCMlm)
<figcaption>Circle tool 3 points</figcaption>


### Ellipse tool
To draw an ellipse, pick the center of the ellipse and any corner of the virtual rectangle bounds of the ellipse. 


### Arc tool
An arc (circle arc) is a segment of the subscribe circle. To draw an arc, pick three different points on the arc.
![type:video](https://www.youtube.com/embed/vEmBnFBvqx8?si=7iVN1ZNNp06Sr-v6)
<figcaption>Arc tool</figcaption>

### Quad curve tool
A quadratic curve is derived from three different points. To draw a quad curve, pick three different points.


### Cubic curve tool
A cubic curve is derived from four different points. To draw a quad curve, pick four different points.


### Path tool
A path is a complex shape, it renders a shape with multiple kind of segments such line, skip (empty distance), quadratic segment, cubic segment, arc segment, and with zero or multiple wholes inside. To switch to ad different segment kind while drawing a path, switch to according path mode. This can be done by switching directly from path mode choice box or switch by using shortcut keys. Below is path mode shortcut keys table:

| Key  | Mode                     | Draw                   | 
| :----| :------------------------|:-----------------------|
| 0    | Move to (skip/jump) mode | Pick one point         |
| 1    | Line segment mode        | Pick one more point    |
| 2    | Quad segment mode        | Pick two more point    |
| 3    | Cubic segment mode       | Pick three more point  |
| 4    | Arc segment mode         | Pick two more point    |
| 5    | Close mode               |                        |
| Space| Cancel last segmentt     |                        |
    
![type:video](https://www.youtube.com/embed/YbrP_CiXLzM)
<figcaption>Path tool - Simple shape</figcaption>

![type:video](https://www.youtube.com/embed/Jr9gPiua9Fg)
<figcaption>Path tool - Shape with different segment kinds</figcaption>
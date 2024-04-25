# Draw tools

<p>
In BlueGrid, <code>shape tools</code> are used to draw almost any type of 2D shapes that are usually used in construction blueprints, such as line, rectangle, polygon, spline, path, shapes with wholes in side...etc. 
</p>
<tip>
<p>
To have the best accuracy when drawing shapes, <code>point snap</code> should be on.
</p>
</tip>

## Line tool
<procedure >
    <step>
        Select the <code>Line tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Left mouse click to pick the start point of the line.
    </step>
    <step>
        Drag or move the mouse to the end point of the line and release or press the mouse button to finish the line.
    </step>
</procedure>

## Rectangle tool
<procedure >
    <step>
        Select the <code>Rectangle tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Left mouse click to pick the first corner of the rectangle.
    </step>
    <step>
        Drag or move the mouse to the opposite corner of the rectangle and release or press the mouse button to finish the rectangle.
    </step>
</procedure>

## Polyline tool
<procedure >
    <p>
    A polyline is a connected sequence of line segments created as a single shape. A polyline has two or many vertices. In BlueGrid, drawing a polyline is to pick all the vertices of the polyline, in ordered sequence.
    </p>
    <step>
    Select the <code>Polyline tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
    Click left mouse button on the <code>Draw board</code> to pick the first vertex of the polyline. By picking the first vertex, there will an extra active vertex which is always move with the mouse cursor.
    </step>
    <step>
    Repeat the second step to pick the next vertex of the polyline, and so on.
    </step>
    <step>
    To finish drawing the polyline, right mouse click <code>draw board</code> to remove the active extra vertex and finish the polyline.
    </step>
</procedure>

## Polygon tool
<procedure >
    <p>
        A polygon is a connected sequence of line segments created as a single shape. A polygon is an always close polyline. Drawing a polygon is similar to drawing a polyline, but the last vertex of the polygon is always connected to the first vertex.
    </p>
    <step>
        Select the <code>Polyline tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Click left mouse button on the <code>Draw board</code> to pick the first vertex of the polygon. 
    </step>
    <step>
        Repeat the second step to pick the second vertex of the polygon.By picking the first vertex, there will an extra active vertex which is always move with the mouse cursor.
    </step>
    <step>
        Repeat the second step to pick the next vertex of the polygon, and so on.
    </step>
    <step>
        To finish drawing the polygon, right mouse click <code>draw board</code> to remove the active extra vertex and finish the polygon.
    </step>
</procedure>

## Circle tool

<procedure  >
    <step>
        Select the <code>Circle tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Click  to pick the center of the circle.
    </step>
    <step>
        Drag or move the mouse to a point on the perimeter of the circle and release or press the mouse button.
    </step>
</procedure>

## Circle 3 points tool
<procedure  >
    <step>
        Select the <code>Circle tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Click  to pick the center of the circle.
    </step>
    <step>
        Drag or move the mouse to a point on the perimeter of the circle and release or press the mouse button.
    </step>
</procedure>

## Arc tool
<procedure >
    <p>
        An arc is a part of a circle. In BlueGrid, drawing an arc is to pick three points on the circle, the start point, the end point, and a point in between the start and the end point.
   </p>
    <step>
        Select the <code>Arc tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Click to pick the start point of the arc.
    </step>
    <step>
        Click  to pick the second point of the arc. The second point can be any point in between the arc curve but not the start nor the end point
    </step>
    <step>
        Click  to pick the end point of the arc.
    </step>
</procedure>

## Ellipse tool
<procedure >
    <step>
        Select the <code>Ellipse tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Click on the <code>Draw board</code> to pick the center of the ellipse.
    </step>
    <step>
        Drag or move the mouse to a corner of the rectangle that encloses the ellipse and release or press the mouse button.
    </step>
</procedure>

## Quad Curve tool

<procedure >
<p>
A quad curve is a curve that is defined by three points, the start point, the control point, and the end point. The curve is a smooth curve that passes through the start and the end point and is controlled by the control point.
</p>
    <step>
        Select the <code>Quad Curve tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Click to pick the start point of the quad curve.
    </step>
    <step>
        Click to pick the control point of the quad curve.
    </step>
    <step>
        Click to pick the end point of the quad curve.
    </step>
</procedure>

## Cubic Curve tool
<procedure >
<p>
A cubic curve is a curve that is defined by four points, the start point, the control point 1, the control point 2, and the end point. The curve is a smooth curve that passes through the start and the end point and is controlled by the control points.
</p>
    <step>
        Select the <code>Cubic Curve tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Click to pick the start point of the cubic curve.
    </step>
    <step>
        Click to pick the first control point of the cubic curve.
    </step>
    <step>
        Click to pick the second control point of the cubic curve.
    </step>
    <step>
        Click to pick the end point of the cubic curve.
    </step>
</procedure>

## Spline tool
<procedure >
<p>
A spline is a smooth curve that is defined by a sequence of points. The curve passes through the points and is controlled by the points. In BlueGrid, drawing a spline is to pick a sequence of points.
</p>
    <step>
        Select the <code>Spline tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Click to pick the first point of the spline.
    </step>
    <step>
        Repeat the second step to pick the next point of the spline, and so on.
    </step>
    <step>
        To finish drawing the spline, right mouse click <code>draw board</code> to remove the active extra vertex and finish the spline.
    </step>
</procedure>

## Path tool
<p>
A path is a sequence of connected lines, curves and moves (empty distances). In BlueGrid, drawing a path is to consequently and continuously draw path elements. In BlueGrid, there are 6 types of Path Elements: Line, Quad Curve, Cubic Curve, Arc, Move, and Close. 
Adjacent path elements are connected, the last control point of the previous path element is the first control point of the next path element. 
To draw different path elements, switch to the corresponding path mode. This can be done by switching directly from the path mode choice box or switch by using shortcut keys. Below is the path mode shortcut keys table:
</p>

| Shortcut Key   | Path mode            | Draw                           | Path element        | Visible |
|:---------------|:---------------------|:-------------------------------|---------------------|---------|
| <code>0</code> | <code>Move to</code> | Pick one point                 | Empty distance      | NO      |
| <code>1</code> | <code>Line to</code> | Pick next point                | Line                | Yes     |
| 2              | Quad segment mode    | Pick next two points           | Quad Curve          | Yes     |
| 3              | Cubic segment mode   | Pick next three points         | Cubic               | Yes     |
| 4              | Arc segment mode     | Pick next two points           | Circle Arc          | Yes     |
| 5              | Close mode           | Path closes to last move       | Line (to last Move) | Yes     |
| Space          | Cancel last segment  | Last active segment is removed |                     | Yes     | 


<note>
The first element of a path is always a Move element and is automatically created when the path is started.
</note>
<procedure >
    <step>
        Select the <code>Path tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Click to pick the first point of the path.
    </step>
    <procedure title="Draw a line segment" id="draw-line-segment">
        <step>
            Select <code>Line To</code> mode from <code>Path mode</code> selection box or press the <code>1</code> key to switch to the <code>Line segment mode</code>.
        </step>
        <step>
            Click to pick the next point of the path.
        </step>
    </procedure>
    <procedure title="Draw a quad curve segment" id="draw-quad-curve-segment">
        <step>
          Select <code>Quad To</code> mode from <code>Path mode</code> selection box or press the <code>2</code> key to switch to the <code>Quad segment mode</code>.
        </step>
        <step>
            Click to pick the next point of the path.
        </step>
        <step>
            Click to pick the next point of the path.
        </step>
    </procedure>
    <procedure title="Draw a cubic curve segment" id="draw-cubic-curve-segment">
        <step>
            Select <code>Cubic To</code> mode from <code>Path mode</code> selection box or press the <code>3</code> key to switch to the <code>Cubic segment mode</code>.
        </step>
        <step>
            Click to pick the next point of the path.
        </step>
        <step>
            Click to pick the next point of the path.
        </step>
        <step>
            Click to pick the next point of the path.
        </step>
    </procedure>
    <procedure title="Draw an arc segment" id="draw-arc-segment">
        <step>
            Select <code>Arc To</code> mode from <code>Path mode</code> selection box or press the <code>4</code> key to switch to the <code>Arc segment mode</code>.
        </step>
        <step>
            Click to pick the next point of the path.
        </step>
        <step>
            Click to pick the next point of the path.
        </step>
    </procedure>
    <procedure title="Move to the next point" id="move-to-next-point">
        <p>
            A <code>Move element</code> is not a visible element, it does not draw anything, it is used to move the start point of the next element to another point. Thus, it creates an empty distance between the last control point of a visible path element and the first control point of the next visible path element.
            Without a <code>Move element</code> the next path element will start from the last control point of the previous path element.
        </p>
        <step>
            Select <code>Move To</code> mode from <code>Path mode</code> selection box or press the <code>0</code> key to switch to the <code>Move to mode</code>.
        </step>
        <step>
            Click to pick the next point of the path.
        </step>
    </procedure>
    <procedure title="Close the path" id="close-path">
        <step>
            Select <code>Close</code> mode from <code>Path mode</code> selection box or press the <code>5</code> key to switch to the <code>Close mode</code> to close the path.
        </step>
    </procedure>
    <procedure title="Cancel the last segment" id="cancel-last-segment">
        <step>
            Press the <code>Space</code> key to cancel the last segment of the path.
        </step>
    </procedure>
    <step>
        To finish drawing the path, right mouse click <code>draw board</code> to remove the active extra vertex and finish the path.
    </step>
<tip>
With path tool, you can draw complex shapes with multiple segments such as line, skip (empty distance), quadratic segment, cubic segment, arc segment, and with zero or multiple wholes inside.
</tip>

</procedure>




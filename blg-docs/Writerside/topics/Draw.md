# Draw shapes
<p>
In BlueGrid standard, shape tools are tools used to draw almost any type of 2D shapes that are usually used in construction blueprints, such as line, rectangle, polygon, spline, path, shapes with wholes in side...etc. All shapes drawn using shape tools have metric values and can subscribe to material tags. Metric values are derived from shapes as rendered visuals. 
</p>
<tip>
<p>
While drawing, to get the best accuracy, point snaps should be on.
</p>
</tip>
<procedure title="Line tool" id="line-tool">
    <step>
        Select the <code>Line tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Click on the <code>Draw board</code> to pick the start point of the line.
    </step>
    <step>
        Drag or move the mouse to the end point of the line and release the mouse button.
    </step>
</procedure>
<procedure title="Rectangle tool" id="rectangle-tool">
    <step>
        Select the <code>Rectangle tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Left click on the <code>Draw board</code> to pick the first corner of the rectangle.
    </step>
    <step>
        Drag or move the mouse to the opposite corner of the rectangle and release or press the right mouse button.
    </step>
</procedure>
<procedure title="Polyline tool" id="polyline-tool">
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
<procedure title="Polygon tool" id="polygon-tool">
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
<procedure title="Circle tool" id="circle-tool">
    <step>
        Select the <code>Circle tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Click on the <code>Draw board</code> to pick the center of the circle.
    </step>
    <step>
        Drag or move the mouse to a point on the perimeter of the circle and release or press the mouse button.
    </step>
</procedure>

<procedure title="Arc tool" id="arc-tool">
    <step>
        Select the <code>Arc tool</code> from the <code>Draw tool pane</code>.
    </step>
    <step>
        Click on the <code>Draw board</code> to pick the start point of the arc.
    </step>
    <step>
        Click on the <code>Draw board</code> to pick the second point of the arc.
    </step>
    <step>
        Click on the <code>Draw board</code> to pick the end point of the arc.
    </step>
</procedure>

<procedure title="Ellipse tool" id="ellipse-tool">
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

# Select shapes
<p>
    In some use cases, users may want to transform, move, or delete shapes. To do so, users must select the shapes they want to manipulate. 
</p>
<procedure>
    <step>
        <p>
        To select the select tool in <code>select tools</code> group.
        </p>
    </step>
    <step>
        <p>
        Click on the shape you want to select.
        </p>
    </step>
</procedure>

# Active shapes
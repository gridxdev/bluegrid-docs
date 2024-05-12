# Terms and definition
<deflist>
<def title="Shape">
<deflist>
    <def title="Shape">
        A shape is a 2D object that is drawn using shape tools. Shapes can be lines, rectangles, polygons, splines, paths, annotations, blocks, images...any things are added and visually rendered in <code>draw board</code>.
        <p>
            A shape is a page-wide data that exists in a page only.
        </p>
    </def>
    <def title="Selected shape">
        <p>
            A shape is selected by user actions and is displayed in selected state. 
        </p>
        <p>
            User select a shape to perform actions such as move, rotate, scale, delete, copy, change style format, subscribe materials, unsubscribe materials and so on.
        </p>    
    </def>
    <def title="Active shape">
        <p>A shape is trigger by user actions and is displayed in active state. </p>
        <p>User activate a shape to perform actions such as edit text, move anchors, insert anchors (applied to Poly classed shapes), delete anchors (applied to Poly classed shapes). Changes made to an active shape are intrinsic.</p>
    </def>
    <def title="Anchor">
      A anchor or anchor point is a point on or not on a shape. Anchor points of a shape directly effect the geometry the shape. Changes made to anchor points will change intrinsic properties of the shape.
   </def>
    <def title="Active point">
      A anchor point which has position actively bond with <code>cursor</code> position.
   </def>
    <def title="Active segment">
      A shape such <code>path</code> may be constituted of multiple line segments, quadratic segments, cubic segments  or empty distances. The segment which is being drawn is an active segment.
    </def>
</deflist>
</def>
<def title="Catalog">
    <deflist>
    <def title="Catalog">
        <p>
            A catalog is a tree structure of Work Breakdown Structure (WBS) that contains a list work groups, work items being referred to as materials in BlueGrid. A catalog is a project-wide data that can be shared among multiple pages.
        </p> 
    </def>
    </deflist>
</def>
</deflist>

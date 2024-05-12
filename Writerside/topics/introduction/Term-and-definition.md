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
<def title="Catalog and Materials">
    <deflist>
        <def title="Catalog">
            <p>
                A catalog is a tree structure of Work Breakdown Structure (WBS) that contains a list work groups, work items being referred to as materials in BlueGrid. 
            </p> 
            <p>
                A catalog is a project-wide data, which means it can be referred to from any page in the project.
            </p>
        </def>
        <def title="Catalog Item">
            <p>
                A catalog item is an item/node in a catalog tree. A catalog item can be of type <code>Group</code>, <code>Count</code>, <code>Linear</code>, <code>Area</code>, or <code>Volume</code>. A group item can have child items while the others are leaf items and do not have child items.
            </p>
            <p>
                Each non-empty catalog has one root item which is a group item.
            </p>
            <p>
                A catalog item of type Group can have child items. A catalog item of type <code>Count</code>, <code>Linear</code>, <code>Area</code>, or <code>Volume</code> is a leaf item and does not have child items, they are also referred to as material or work items.
            </p>
        </def>
        <def title="Catalog Item Type">
            <p>
                A catalog item must be either of type <code>Group</code>, <code>Count</code>, <code>Linear</code>, <code>Area</code>, or <code>Volume</code>. The table below describe properties of catalog item types:
            </p>
        <table>
            <tr>
                <th>Type</th>
                <th>WBS Ref.</th>
                <th>Tree Access</th>
                <td>Material visual format</td>
                <th>Description</th>
            </tr>
            <tr>
                <td><code>Group</code></td>
                <td>Work group</td>
                <td>Group item</td>
                <td>No</td>
                <td>Can have child items</td>
            </tr>
            <tr>
                <td><code>Count</code></td>
                <td>Work item</td>
                <td>Leaf item</td>
                <td>Yes</td>
                <td>Has a count value in integer</td>
            </tr>
            <tr>
                <td><code>Linear</code></td>
                <td>Work item</td>
                <td>Leaf item</td>
                  <td>Yes</td>
                <td>Has a length value in float number</td>
            </tr>
            <tr>
                <td><code>Area</code></td>
                <td>Work item</td>
                <td>Leaf item</td>
                <td>Yes</td>
                <td>Has an area value in float number</td>
            </tr>
            <tr>
                <td><code>Volume</code></td>
                <td>Work item</td>
                <td>Leaf item</td>
                  <td>Yes</td>
                <td>Has a volume value in float number</td>
            </tr>   
        </table>
        </def>
        <def title="Material">
            <p>
                A material is a work item, set for a specific page. A material item has the same properties as a catalog work item except that it is page-wide data.
            </p>
        </def>
    </deflist>
</def>
</deflist>

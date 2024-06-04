# Overview


## Terms and Definitions

<deflist>
    <def title="Page" id="page-def">
        <p>
            A <b>page</b> serves as a virtual reference for a blueprint. A blueprint represents a segment of a construction design. It can have one or multiple versions or updates. A page may contain zero or multiple corresponding PDF versions of the blueprint.
        </p>
        <p>
            Each page acts as an entry point, referring to a blueprint and any <a href="Overview.md" anchor="additional-data-def" >additional data</a> related to that page.
        </p>
        <p>
            A page resides in one folder.
        </p>
        <a href="pages.md">Learn more about pages</a>
    </def>
    <def title="Additional data" id="additional-data-def" >
        <p>
            <b>Additional data</b> refers to the information generated in BlueGrid by users, such as <a href="Overview.md" anchor="shape-def">shapes</a>, <a href="Overview.md" anchor="material-def"> materials</a>, and other relevant content. This data is stored in relation to a specific <a href="Overview.md" anchor="page-def"> page</a>. Essentially, a <a href="Overview.md" anchor="page-def">page</a> serves as the access point to its associated additional data.
        </p>
    </def>
    <def title="Shape" id="shape-def">
        A shape is a 2D object that is drawn using <code>shape tools</code>. Shapes can be lines, rectangles, polygons, splines, paths, annotations, blocks, images...any things are added and visually rendered in <code>drawboard</code>.
        <p>
            A shape presents page-wide data that exists only within a specific page.
        </p>
        <a href="Shape-tools.md">Learn how to create shapes</a>
    </def>
    <def title="Selected shape">
        <p>
            A shape is selected through user actions and is displayed in the selected state. 
        </p>
        <p>
            Users select a shape to perform actions such as moving, rotating, scaling, deleting, copying, changing the style format, subscribing materials, unsubscribing from materials and more.
        </p>    
        <a href="Move-and-transform.md">Learn how to select shapes</a>
    </def>
    <def title="Active shape">
        <p>A shape is activated through user actions and is displayed in an active state.</p>
        <p>user activates a shape to perform actions such as editing text, moving anchors, inserting anchors (applicable to Poly-class shapes), and deleting anchors (applicable to Poly-class shapes). Changes made to an active shape are intrinsic.</p>
        <a href="Active-and-modify.md">Learn how to activate a shape</a>
    </def>
    <def title="Free shape">
        <p>A shape is considered a free shape if it is not associated with any material.</p>
    </def>
    <def title="Anchor">
      An anchor, or anchor point, is a point that may or may not be on a shape. The anchor points of a shape directly affect the geometry of the shape. Changes made to anchor points will alter the intrinsic properties of the shape.
   </def>
    <def title="Catalog">
        <p>
        A catalog is a tree structure of the Work Breakdown Structure (WBS) that contains a list of work groups and work items, referred to as materials in BlueGrid.
        </p>
        <p>
            A catalog represents project-wide data, meaning it can be accessed from any page within the project.
         </p>
    </def>
    <def title="Catalog Item">
        <p>
            A catalog item is an element within a catalog tree. It can be categorized as a <code>Group</code>, <code>Count</code>, <code>Linear</code>, <code>Area</code>, or <code>Volume</code> type. A Group item may contain child items, whereas the other types are leaf items and do not possess child items.
        </p>
        <p>
         Every non-empty catalog contains a single root item, which is of the Group type.
        </p>
        <p>
            A Group-type catalog item is capable of having child items. In contrast, catalog items of the <code>Count</code>, <code>Linear</code>, <code>Area</code>, or <code>Volume</code> types are leaf items without child items and are also known as materials or work items.
        </p>
    </def>
 <def title="Catalog Item Type">
        <p>
            A catalog item must be of the type <code>Group</code>, <code>Count</code>, <code>Linear</code>, <code>Area</code>, or <code>Volume</code>. The table below describes the properties of catalog item types:
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
    <def title="Material" id="material-def">
        <p>
           A material is a work item designated for a specific page. A material item possesses the same properties as a catalog work item, with the exception that it is page-wide data, meaning it exists only within a single page.
        </p>
    </def>
</deflist>






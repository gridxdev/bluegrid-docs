# Material

<p>
In BlueGrid, each page has one co-related material table. Each material item in the table must be one of four types: Count, Linear, Area, or Volume. A shape, with its metric properties of length, area, and volume, can subscribe to or unsubscribe from a material item.
</p>
<p>
By subscribing to a material item, the shape’s metric property that corresponds to the material will be accounted for in that material’s quantity value.
</p>

## Add materials
<procedure title="Add a material item" id="add-a-material-item">
<step>
Go to <code>Draw view</code>
</step>
<step>
Select <code>material tab</code> of on the left of the <code>Draw view</code>
</step>
<step>
From <code>material table menu </code> hover <code>Add material</code> and select sub menu item of specific material type.
</step>
<img src="add_material.png" alt="Add a material item" width="540"/>
<note>
<p>
  The new material item is added with default properties such as <code>code</code>, <code>description</code>, and format style. A material item can always be edited. Refer to <a href="#edit-material-item">Edit material item</a> procedure.
</p>
</note>
</procedure>

## Import materials form CSV files
<procedure title="Import materials from CSV files" id="import-materials-from-csv-files">
<p>
Material table of a page can be imported from a CSV file.
</p>
<step>
Go to <code>Draw view</code>
</step>
<step>
Select <code>material tab</code> of on the left of the <code>Draw view</code>
</step>
<step>
From <code>material table menu </code> select <code>Import from csv</code> menu item.
</step>
<step>
Upon selecting the <code>Import from csv</code>, an open file <code>dialog window</code> will display. Navigate to the CSV file you want to import and click <code>Open</code> from the <code>dialog window</code>.
</step>
<img src="import_material.png" alt="Import materials from CSV files" width="540"/>
</procedure>

## Export material table to CSV files

<procedure title="Export material table" id="export-material-table">
<step>
Go to <code>Draw view</code>
</step>
<step>
Select <code>material tab</code> of on the left of the <code>Draw view</code>
</step>
<step>
From <code>material table menu </code> select <code>Export to csv</code> menu item.
</step>
<step>
Upon selecting the <code>Export to csv</code>, a save file <code>dialog window</code> will display. Navigate to the location you want to save the CSV file and click <code>Save</code> from the <code>dialog window</code>.
</step>
<img src="export_pdf.png" alt="Export material to csv" width="540"/>
<note>
<p>
Exporting material table to csv files is different from exporting to excel files. While exporting to csv file is to export the material definitions for the page, 
exporting to excel files is to export the material quantity take-off data for the page. 
</p>
</note>
<tip>
<p>
  The exported CSV file can be opened and edited in a spreadsheet application such as Microsoft Excel or Google Sheets and imported to BlueGrid later.
</p>
</tip>
</procedure>

## Delete materials
<procedure title="Delete material items" id="delete-material-items">
<step>
Go to <code>Draw view</code>
</step>
<step>
Select <code>material tab</code> of on the left of the <code>Draw view</code>
</step>
<step>
Select the material items you want to delete
</step>
<step>
From <code>material table menu </code> select <code>Delete material</code> menu item.
</step>
<img src="delete_materials.png" alt="Delete material items" width="540"/>
</procedure>

## Edit materials
<procedure title="Edit material item" id="edit-material-item">
<step>
Go to <code>Draw view</code>
</step>
<step>
Select <code>material tab</code> of on the left of the <code>Draw view</code>
</step>
<step>
Select the material item you want to edit
</step>
<step>
By selecting the material item, it is loaded to the <code>material editor</code> on the bottom of the <code>Draw view</code>. Edit the material item properties in the <code>material editor</code>.  
</step>
<img src="edit_material.png" alt="Edit material item" width="540"/>
</procedure>

<tip>
<p>
As material table can be exported to and imported from CSV files, users can edit the material table in a spreadsheet application such as Microsoft Excel or Google Sheets and import the edited material table back to BlueGrid.
</p>
</tip>

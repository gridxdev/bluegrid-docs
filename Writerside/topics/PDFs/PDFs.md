# Pages
<tldr>
    <p>UI path: <ui-path><code>Document view</code> <shortcut>Alt+1</shortcut> | <code>Page view</code></ui-path></p>
</tldr>

## Add PDF pages
<procedure >
<step>
In the <code>Folder view</code>, select the folder you want to add PDFs to.
</step>
<step>
Click to open <code>Page menu</code><shortcut>Alt+P</shortcut> select <code>Add PDF</code><shortcut>D</shortcut> menu item.
</step>
<step>
Navigate to the PDF files and click <code>Open</code> from the <code>open file dialog</code>.
</step>
<img src="add_pdf.png" alt="Add PDFs to a folder" width="540"/>
<tip>
You can simply add PDF pages to a folder by dragging and dropping PDF files to the <code>Page view</code> of the folder.
</tip>
</procedure>

## Replace pages
<procedure>
<p>In BlueGrid a PDF page is conceptually a blueprint and may have many versions, the last version is the 'active' version. By replacing the PDF page, users replace the last version.</p>
<step>
In <code>Folder view</code>, select the folder that contains the pages you want to replace.
</step>
<step>
Select the page you want to replace in <code>Page view</code>.
</step>
<step>
Right click on the page item to open the page <code>context menu</code>.
</step>
<step>
Select <code>Replace</code> menu item.
</step>
<step>
Navigate to the PDF file you want to replace the page with and click <code>Open</code> from the <code>open file dialog</code>.
</step>
<img src="replace_page.png" alt="Replace page" width="540"/>
<note>
    BlueGrid will take the first page of the PDF file to replace the page.
</note>
</procedure>

## Duplicate a page
<procedure>
<step>
    From <code>Page view</code> select the page to duplicate.
</step>
<step>
    Right mouse click to open page <code>context menu</code>
</step>
<step>
    Select menu item <code>Duplicate</code>
</step>
<img src="duplicate_page.png" alt="Duplicate a page" width="540"/>
</procedure>

## Add page version
<procedure>
<step>
    From <code>Page view</code> select the page to add version.
</step>
<step>
    Right mouse click to open page <code>context menu</code>
</step>
<step>
    Select menu item <code>Add version</code>
</step>
<step>
   Navigate to the PDF file you want to add version and click <code>Open</code> from the <code>open file dialog</code>.
</step>
<note>
    The lastly added PDF page is the last version and will be the active PDF page.
</note>
</procedure>

## Rotate PDF pages
<procedure>
<step>
    From <code>Page view</code> in <code>Document view</code> select the page to rotate.
</step>
<step>
    Right mouse click to open page <code>context menu</code>
</step>
<step>
    Hove menu item <code>Rotate</code>
</step>
<step>
    Select the rotation direction <code>Clockwise</code> or <code>Counter-clockwise</code>
</step>
<img src="rotate_page.png" alt="Rotate page" width="540"/>
<note>
    The rotation is applied to the last version of the page.
</note>
</procedure>

## Export to PDFs
<procedure>
<p>
In BlueGrid, users can export <code>Draw board</code> content of a page including shapes, markups, quantity take-off data to PDF files.
</p>
<step>
Select the pages you want to export to PDF in the <code>Page view</code>.
</step>
<step>
From <code>Page menu</code> select <code>Export to PDF</code> item.
</step>
<step>
Navigate to the location you want to save the PDF files and click <code>Save</code> from the dialog window.
</step>
<img src="export_pdf.png" alt="Export to PDF" width="540"/>
<tip>
        You can always select multiple pages to export to one PDF file.
</tip>
</procedure>


## Delete pages
<procedure  >
<warning>
    <p>
        <b>Page</b> is the entry point of every <b>additional data</b> relating to the page. By deleting a page, users will also delete all data referencing to the page. This action is irreversible.
    </p>
</warning>
<step>
Select the folder that contains the pages you want to remove in the <code>Document view</code>.
</step>
<step>
Select the pages you want to remove in the <code>Page view</code>.
</step>
<step>
From <code>Page menu</code> select <code>Remove</code> item.
</step>
<img src="remove_page.png" alt="Remove page" width="540"/>

</procedure>

## Delete page versions
<procedure>
<step>
    From <code>Page view</code> select the page you want to delete version.    
</step>
<step>
    Right mouse click to open page <code>context menu</code>.
</step>
<step>
    Select menu item <code>Delete version</code>.
</step>

[//]: # (<img src="" alt="Delete page versions"/>)
<note>
    By deleting version, BlueGrid deletes the last version of the page. The version next to the deleted version will be the last version and the active version.
    A page will have no PDF blueprint version if users deletes all its PDF blueprint versions.
</note>
</procedure>

## Set page properties
<p>
In BlueGrid, page properties of a page such as name, scale.
</p>
<procedure>
<step>
    From <code>Page view</code> select the page to set properties.
</step>
<step>
    Right mouse click to open page <code>context menu</code>.
</step>
<step>
    Select menu item <code>Properties</code>.
</step>
<step>
    Set the page properties in the <code>Properties dialog</code> and click <code>OK</code> to save the properties.
</step>
<img src="set_page_properties.png" alt="Set page properties" width="540"/>
<note>
    The recommended method to set scale to a page to use <code>Scale tool</code> in <code>annotation tool set</code> in <code>Draw view</code>.
    <a href="Annotation-tools.md" anchor="scale-tool">Learn more about scale tool</a>
</note>
</procedure>

## Filter pages by name
<p>
    PDF pages in an opened folder can be filtered by name.
</p>
<procedure>
<step>
    From  <code>Folder view</code> select the folder to filter pages.
</step>
<step>
    Click on the <code>Filter</code> input box in the <code>Page view</code>.
</step>
<step>
    Type complete or a part of the page name in the <code>Filter</code> input box.
</step>
<img src="filter_pages.png" alt="Filter pages" width="540"/>
</procedure>

## Find PDF pages by text content
<p>
    In BlueGrid, users can search for PDF pages by text content hints.
</p>
<procedure>
<step>
    From <code>Folder view</code> select the folder to search for pages.
</step>
<step>
    Click on the <code>Filter | Search</code> input box in the <code>Page view</code>.
</step>
<step>
    Type the text hint may PDF pages contain in the <code>Filter | Search</code> input box.
</step>
<step>
    Hit button <code>Search</code> to trigger search.
</step>

[//]: # (<img src="search_page.png" alt="Search pages" width="540"/>)
<note>
    BlueGrid will list all pages that contain the text hint in the search result.
</note>
</procedure>








## Application

Application is the main window of BlueGrid, where users perform quantity take-off projects.

Operations in the application are at project level. This means that the changes made in the application are applied to the project. Data of project is stored in the project file.

### User Interface
> The application has an application [Tool Bar](#application-tool-bar) and 3 sub-views: [Documents View](#document-view), [Draw View](#draw-view), and [Catalogs View](#catalogs-view).

> ![Document View interface](assets/image/application/application.png)

> 1. [Application Tool Bar](#application-tool-bar)
> 2. [Sub-view](#sub-view)

> #### Application Tool Bar
```Navigation: Application | Application Tool Bar```

> The **Application Tool Bar** is on the top of the application view and is always visible by default. From the **Application Tool Bar**, you do common operation such as save, undo, redo, and navigate to different sub-views of the application, for the purposes of use. 

> #### Sub-view
```Navigation: Application | Sub-view```

> Sub-view of can be either Documents View, Draw View, or Catalogs View. Each sub-view has its own functionalities and functions. All sub-views share the same project data. The Documents View is the default sub-view of the application, when you open a project.

## Document View
```Navigation: Application | Documents View```

> **Documents View** the view of project construction blueprints of PDF folders and pages.

### User Interface
> The user interface is designed to facilitate PDF view (as thumbnails) and simple but powerful PDF blueprints management.

> ![Document View interface](assets/image/application/documentview.png)

> 1. [Application Tool Bar](#application-tool-bar)
> 2. [Folders](#folders) 
> 3. [Pages](#pages) 
> 4. [Folders menu](#folders-menu)
> 5. [Pages menu](#folders-menu)
> 6. [Page thumbnails](#page-thumbnials)
> 7. [Pages context menu](#pages-context-menu)


> #### Folders
```Navigation: Application | Documents View | Folders```

> **Folders** is a list view that displays all PDF folders of the project. Users can click a folder item in the list to open it. To remove a folder from the list, select the folder item in the list, open [Folders Menu](#folders-menu), and select delete menu item.

> #### Pages
```Navigation: Application | Documents View | Pages```

> **Pages** is a grid view that displays PDF pages in thumbnails of an opened folder. To open a page, user double-click the page thumbnail or select Open in the Page Context Menu. To remove a page , select the page thumbnail, open [Pages Menu](#pages-menu) or right-click the page  thumbnail to open context menu, and select **Delete Pages** menu item.

> #### Folders menu
```Navigation: Application | Documents View | Folders | Folders menu```

> **Folders menu** is a menu that provides functions to manage PDF folders such as add, delete, rename... To open the menu, right-click the folder list or click the menu button on the top-right corner of the folder list.

> #### Pages menu
```Navigation: Application | Documents View | Pages | Pages menu```

> **Pages menu** is a menu that provides functions to manage PDF pages of a folder such as open, delete, append, import, export, duplicate... To open the menu,  click the menu button on the top-right corner of the page list. Users can also select multiple pages to perform batch operations such as delete, export, duplicate...

> #### Page thumbnails
```Navigation: Application | Documents View | Pages | Page thumbnails```

> Under-laying data of a page thumbnail is the page data set which consists of the PDF page, shapes, materials, annotations, and any data the user added to the page.To open a page, user double-click the page thumbnail or select Open in the [**Page Context Menu `7` **](#pages-context-menu). By opening a page, the application navigates to the [Draw View](#draw-view), loads data page set into the Draw View.

> #### Pages context menu
```Navigation: Application | Documents View | Pages | Page context menu```

> **Page context menu** is a menu that provides functions to manage selected PDF pages such as open, delete, append, import, export, duplicate... To open the menu, right-click the page thumbnail. Users can also select multiple pages to perform batch operations such as delete, export, duplicate... **Page context menu** has similar functions as [Pages menu](#pages-menu) as another option to accent pages functions by using right-click.


## Draw View
```Navigation: Application | Draw View```

> **Draw View** is the centric interface of the application. It is where users perform quantity take-off, create and edit shapes, materials, tags, annotations, images...etc.

### User Interface

> ![Draw View interface](assets/image/application/drawview.png)
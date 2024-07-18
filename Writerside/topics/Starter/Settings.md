# Application settings

<card-summary>Customize styles, shortcut keys, precision and more</card-summary>

<tldr>
    <p>UI path: <ui-path><code>Starter</code> | <code>Settings</code></ui-path></p>
</tldr>

## Themes and Styles
<procedure  >
<p>
The application has 4 themes: Prime, Nord, Cupertino, and Dracula, each is with dark and light modes.
</p>
<step>
From the <code>Starter</code> window select <code>setting</code> tab.
</step>
<step>Select theme from theme selection <code>dropdown</code>.</step>
<step>To change accent color, click on one of the color indicators.</step>
<img src="select_theme.png" alt="Select theme and style" />
</procedure>

[//]: # (<procedure title="Select language" id="select-language">)

[//]: # (<step>)

[//]: # (    From the Starter window select setting tab)

[//]: # (</step>)

[//]: # (<step>)

[//]: # (    Select language from the language selection <code>dropdown</code>)

[//]: # (</step>)

[//]: # (<img src="language_selection.png" alt="Select language" width="540"  />)

[//]: # (</procedure>)

## Set precision

<procedure title="Set floating point" >
<step>
    From the <code>Starter</code> window select <code>setting</code> tab
</step>
<step>
    Select floating point from the floating point selection <code>dropdown</code>
</step>
<img src="precision_selection.png" alt="Setting floating point"  />
</procedure>

## Set shortcut keys 

<procedure title="Setting shortcut keys" >
<p>
In BlueGrid, most user actions can be performed using keyboard shortcuts. 
</p>
<p>
To view or set shortcut keys, click on the <code>Setting</code> tab and scroll down to set Shortcut keys section in the Starter window.
Shortcut keys are categorized into four groups and two levels: <code>Application</code> (level 0), which is for ui controls on the top <code>Toolbar</code>, as shown in the image below,
<code>Draw View</code> (level 1), <code>Document View</code> (level 1), and <code>Catalog View</code> (level 1).
</p>
<p>
Each group contains a list of shortcut keys that users can customize. Shortcut keys at a lower level have a higher execution priority, meaning a shortcut key at a higher level will not execute if a lower-level key shares the same shortcut, the lower level shortcut key executes.
</p>
<p>
Identical shortcut keys in different groups at the same level will have the same execution priority. For example, the shortcut key <code>Ctrl</code>+<code>O</code> in the Draw View group and <code>Ctrl</code>+<code>O</code> in the <code>Document View</code> group will have the same execution priority. Shortcut key <code>Ctrl</code>+<code>D</code> in <code>Application</code> group will have the highest execution priority, if <code>Draw View</code> has the same shortcut, the shortcut key <code>Ctrl</code>+<code>D</code> in <code>Application</code> group will execute and the shortcut key <code>Ctrl</code>+<code>D</code> in <code>Draw View</code> group will not execute.
</p>
<p>
Different groups can share shortcut keys. In the same group, shortcut keys shall be unique.
</p>


<img src="shortcut.png" alt="Setting shortcut keys" />

</procedure>

## Import and Export setting profiles


<p>
    The application settings can be saved and loaded as profiles. Users can save settings profiles for different purposes and reload them later as needed.
</p>

<procedure title="Export setting profiles">
<step>
    Click on the <code>Export</code> button to open <code>save file dialog</code> window.
</step>
<step>
    In the <code>save file dialog</code>, enter the profile file's name and click <code>Save</code> to save the profile on the computer.
</step>
<img src="import_profile.png" alt="Import a setting profile"/>
</procedure>

<procedure title="Export setting profiles">
<step>
    To load a setting profile, click on the <code>Import</code> button.
</step>
<step>
    Upon clicking the <code>Import</code> button, an <code>Open file dialog</code> will appear, navigate to the profile file and click <code>Open</code> to load the file.
</step>
<img src="export_setting_profile.png" alt="Export setting profile"/>
</procedure>
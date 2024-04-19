# Settings

<procedure title="Select Themes and Styles" id="select-themes-and-styles">
<p>
The application has 4 themes: Prime, Nord, Cupertino, and Dracula, each is with dark and light modes.
</p>
<step>From the Starter window select setting tab</step>
<step>Select theme from theme selection <code>dropdown</code></step>
<step>To change accent color, click on one of the color indicators</step>
<img src="select_theme.png" alt="Select theme and style" width="540"/>
</procedure>

<procedure title="Select language" id="select-language">
<step>
From the Starter window select setting tab
</step>
<step>
Select language from the language selection <code>dropdown</code>
</step>
<img src="language_selection.png" alt="Select language" width="540"/>
</procedure>

<procedure title="Set floating point" id="set-floating-point">
<step>
From the Starter window select setting tab
</step>
<step>
Select floating point from the floating point selection <code>dropdown</code>
</step>
<img src="precision_selection.png" alt="Setting floating point" width="540"/>
</procedure>

<procedure title="Setting shortcut keys" id="setting-shorcut-key">
In Bluegrid, most user actions can be performed using keyboard shortcuts. 
<p>
To view or set shortcut keys, click on the <code>Setting</code> tab and scroll down to set Shortcut keys section in the Starter window.

Shortcut keys are categorized into four groups and two levels: <code>Application</code> (level 0), which is for ui controls on the top <code>Toolbar</code>, as shown in the image below,

<img src="app_toolbar.png"  width="540" alt="Application toolbar"/>

<code>Draw View</code> (level 1), <code>Document View</code> (level 1), and <code>Catalog View</code> (level 1).

Each group contains a list of shortcut keys that users can customize. Shortcut keys at a lower level have a higher execution priority, meaning a shortcut key at a higher level will not execute if a lower-level key shares the same shortcut, the lower level shortcut key executes.
</p>
<p>
Identical shortcut keys in different groups at the same level will have the same execution priority. For example, the shortcut key <code>Ctrl</code>+<code>O</code> in the Draw View group and <code>Ctrl</code>+<code>O</code> in the <code>Document View</code> group will have the same execution priority. Shortcut key <code>Ctrl</code>+<code>D</code> in <code>Application</code> group will have the highest execution priority, if <code>Draw View</code> has the same shortcut, the shortcut key <code>Ctrl</code>+<code>D</code> in <code>Application</code> group will execute and the shortcut key <code>Ctrl</code>+<code>D</code> in <code>Draw View</code> group will not execute.
</p>
<p>
Different groups can share shortcut keys. In the same group, shortcut keys shall be unique.
</p>


<img src="shortcut.png" alt="Setting shortcut keys" width="540"/>
</procedure>
<procedure title="Save and load profiles" id="save-load-profiles">
<p>
The application setting can be saved and loaded as profiles. For example, users can save a settings profiles for different favors of use and save time on setting up the application.
</p>
<p>
To save or load a setting profile, click on the <code>Setting</code> tab and scroll down to the <code>Setting Profile</code> section in the Starter window.
</p>
<img src="profile.png" alt="Save and load profile" width="540"/>
<procedure title="Import setting profiles">
<step>
Click on the <code>Export</code> button to save the current setting profile.
</step>
<step>
Upon clicking the <code>Export</code> button, a saving files dialog will appear where users can enter the profile name and click <code>Save</code> to save the profile to a file on the computer.
</step>
</procedure>

<procedure title="Export setting profiles">

<step>
To load a setting profile, click on the <code>Import</code> button.
</step>
<step>
Upon clicking the <code>Import</code> button, an opening files dialog box will appear, navigate to the profile file and click <code>Open</code> from the dialog window to load the file.
</step>
</procedure>
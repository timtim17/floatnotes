floatnotes
==========

_floatnotes_ is a "just for fun" utility for hovering a note taking window over a website.

Usage
-----
1. Go to [index.html](http://timtim17.github.io/floatnotes/index.html)
2. Enter the URL to visit in the box.
3. Click on the icon in the top right corner on the next screen
4. Resize the window if needed
5. Take Notes
6. Save Notes File
7. Load Notes File

Known Flaws/Requirements
------------------------
- Does not support pages that do not allow their content to be shown in an iFrame (i.e. Google, Stack Overflow, etc...)
  - Known Solutions:
    - YouTube: For *{{videoid}}*, **http://youtube.com/embed/{{videoid}}**
- Only browser fully supported is Chrome

How it Works
------------
Uses iFrame to show website.
Uses jQuery UI to have draggable window.
Saves with Blob/File API.

Libraries Used
--------------
- Served by Google CDN
  - jQuery
  - jQuery UI
  
Todo
----
- Finish Readme
- Clean-Up Code
- Add location bar to floating page
- Add features
  - Checkboxes
  - Code Line #s
  - Toolbar
- Intergrate with Cloud Services
  - Google Drive
  - OneDrive/OneNote

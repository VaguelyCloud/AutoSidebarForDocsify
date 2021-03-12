# Auto Sidebar For Docsify
## Introduction
In my spare time, I wrote a plug-in for Docsify to automatically generate a table of contents.
## Features
The main functions of Auto Sidebar For Docsify are: The blog deployed by Docsify automatically generates a directory.
## Environmental requirements
-nodejs
## Instructions for use
Copy the auto Sidebar.js file of this project to the root directory of the git project.
**Reminder**: Please back up the original `_ sidebar.md` file before use. Running the program will overwrite the original file.
```bash
$ node autoSidebar.js
```
After completion, the document effect will be automatically output in the terminal and written into the `_sidebar.md` file
## Effect picture
![](img/2021-03-12-12-42-08.png)
## Note
The directory has been optimized, and there will be no duplicate paths in the tree diagram.
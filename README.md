**Sheldon's Project Template**
This is just a nice template I plan to use for my projects.

**Why?**
I wanted a standard layout for all my projects. 
My prerequisites were the following:
-Intellisense should properly.
-Dependencies for both editing and executing the code tied to project.
-Usable with any language I can think of.

Doing this allows sharing and getting up and editing to be significantly quicker not only that but ensures workspaces are kept clean. Not only that but I can also have version control for anything my editor or code modules. I was also running into issues with conflicting extensions for Visual studio Code and found PyCharm to be quite a hassle to use when working on languages other than python.

**What?**
-All dependencies for editing are kept in /dependencies/editor
-All dependencies for code to run are kept in /dependencies/code

**Planned Layout:**
Depending on project this may change but here is my general outline.
/code/main.filetype - Main entry point for initializing the project.
/code/data/modules - Python Modules.
/code/data/ - Any other Data for code.
/dependencies/editor/ - Anything needed for the editor.
/dependencies/code/ - Anything needed for the code - This should not include code modules/code made for the project.

**Setup:**
1.) Install Visual Studio Code: https://code.visualstudio.com/
2.) Create a environment variable in your path that points to the location code.exe resides. 

**Usage:**
1.) Click edit.bat to open the editor
(If using this specific project further steps)
2.a) After launching navigate to /code/main.py then click python in the bottom left.
2.b) At the top set the interpreter to python.exe in /dependencies/code/python/
Enhanced-R: R Plugin for Sublime Text 2/3
=======================================

Introduction
------------
This plugin contains some simple features that helping writing R languages:
* More comprehensive Indentation and Syntax
* Some useful key bindings
* Support multiple applications on Windows/Mac/Linux.
* For Windows, [AutoHotkey](http://www.autohotkey.com) which is an automation script is used
as a bridge between R and ST.

Supported Applications
---------------
* R Gui i386 and x64 for Windows and Mac
* Terminal and iTerm 2 for Mac
* R Term i386 and x64 for Windows
* Tumx and screen for Linux

Some useful key bindings
---------------
#### Sending Code
**Keybinding:** `C-Enter`

* Send the selection to R (See settings for choosing default application)
* If no syntax is selected, it sends the whole line where the cursor stays at.

#### Changing Working Directory
**Keybinding:** `C-\`

* Change working directory to where the current working script stays

####  Sourcing file
**Keybinding:** `C-b`

* Tell R to source the working script

Settings
---------
#### Application

* Type ``R: Choose Application`` in Command Palette to switch between applications.

#### Application path

* In default, Enahnced-R will search for applications automatically. To manaully edit applications' paths, go to
Preferences -> Package Settings -> Enhanced R -> Settings

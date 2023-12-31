# Changelog

## Version 0.1.24
* Bugfix: issues from 0.1.23
* Better/shorter love2d path error messages

## Version 0.1.23
* Updated Love2D documentation to v. 11.4
* Better error messages
* Search for love.exe in workspace if pixelbyte.love2d.path is not valid

## Version 0.1.22
* Added 'revealStatus' setting to turn off forcing the status window to be shown when a status message is written to the output log. It is set by default to False so status messages will be written, but the window will not be shown if it is currently hidden.
* Added bottom status bar indicators to show the current 'debug' state and 'run on save' state. In addition, these indicators can be clicked to toggle each respective setting on/off.

## Version 0.1.21
* Changed Love2D default help key to ctrl + F1
* Tried to make it more clear that all the shortcut keys can be changed in settings

## Version 0.1.20
* Updated to support Love 11.3

## Version 0.1.19
* Updated to support Love 11.2

## Version 0.1.18
* Updated to support Love 11.1

## Version 0.1.17
* Fix pid error message when attempting to kill a process

## Version 0.1.16
* Check if specified Love2d path exists and is a file and report an error if it does not
* Ensure previous process keys exist before attempting to kill() them.
* Improve process spawning/management in OSX
* Set default path to /Applications/love.app/Contents/MacOS/love for OSX
* Set default path to 'love' for linux (i.e. assume it's in the path)
* Known issue: Unable to get print output with OSX 

## Version 0.1.14
* Bugfix: Extension was ignoring the srcDir when running Love2D --console

## Version 0.1.13
* Added pixelbyte.love2d.srcDir setting to change the search directory for main.lua
* If main.lua is the currently-open tab Love2D will be executed regardless of whether it is found in the current search path.

## Version 0.1.12
* Updated to support Love 11.0.0

## Version 0.1.11
* Added default MacOS keybindings for some of the keyboard shortcuts
 
## Version 0.1.10
* Fixed an issue in Windows that caused the debugging option to not run if there were spaces in the love2d path

## Version 0.1.9
* Fixed an issue with that could sometimes cause launching Love2D to fail when in debug mode

## Version 0.1.8
* Started work on a completion provider for the Love2D API which displays function and parameter information and is much more flexible than the snippets that were previously used

## Version 0.1.7
* Love2D-specific keybindings are only active when the editor language is Lua

## Version 0.1.6
* Added ability to open Love2D documentation for function name under cursor

## Version 0.1.5
* Added command to toggle debug mode on/off

## Version 0.1.4
* Added ability to run Love2D when a file is saved
* Added some more configuration settings to support run on save functionality

## Version 0.1.3
* Don't display error popups in VSCode
* Always kill love2d spwaned processes the same way in Windows 

## Version 0.1.2
* Settings changes no longer require a reload of VSCode

## Version 0.1.1
* Initial Release

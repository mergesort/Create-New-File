This is an automator script that lets you right click on a file or folder, and it give you the option to create a new file.
The file that it creates will be untitled.txt, in the same directory as the right click occurred.

Known issues:
Does not work on the Desktop, but will work in the Desktop folder itself.  This is because the action requires the current Finder window.
This also does not work in Dropbox, for some reason... No clue, but may look into it later.

To install, drop the Create New File script into ~/Library/Services and restart your Finder.
If you don't know how to restart your Finder, open Terminal and type killall Finder.
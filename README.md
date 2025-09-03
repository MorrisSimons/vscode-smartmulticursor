# Smart Multi-cursor
Context aware multi-cursor.  
Inserting cursor in the appropriate position on next line, if no pattern was found falling back to regular column based multi-cursor.  
The pattern search is based on:  
" ' = : , ; . ( ) { } [ ] < > Tab

This extension overrides the default insertCursorBelow/Above keybindings:  
> Windows: <kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Down/Up</kbd>  
> Linux: <kbd>Shift</kbd>+<kbd>Alt</kbd>+<kbd>Down/Up</kbd>  
> Mac: <kbd>⌘</kbd>+<kbd>⌥</kbd>+<kbd>Down/Up</kbd>  

Tip: use <kbd>Ctrl</kbd>+<kbd>u</kbd> to undo last cursor (Mac: <kbd>⌘</kbd>+<kbd>u</kbd>).

![example1](example1.gif "Example 1")


## Issues and suggestions
Please file an [issue](https://github.com/MorrisSimons/vscode-smartmulticursor).

Contributions are welcomed.

---


**This is a reupload of the original extension for Open VSX.**  
The VS Code extension “Smart Multi-cursor” by **idanpa** is published on the Visual Studio Marketplace but not on Open VSX, so this reupload makes it available for Cursor users.

[Why Cursor uses Open VSX](https://forum.cursor.com/t/extension-marketplace-changes-transition-to-openvsx/109138)  
Original listing at vs code marketplace: https://marketplace.visualstudio.com/items?itemName=idanp.smartmulticursor
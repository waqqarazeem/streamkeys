## Music player hotkeys
This is a simple script to send "global" (ie. across the browser) hotkeys to various online media players.<br>

##Default hotkeys:

MAC:
* Ctrl + Shift + 2: Toggle play/pause
* Ctrl + Shift + 1: Previous song
* Ctrl + Shift + 3: Next Song
* Cmd + Shift + M: Toggle mute

WINDOWS/LINUX
* Mediakeys: play/pause, next, previous
* Ctrl + Shift + M: mute

##Info:

This extension works by sending click events to the elements that control the music player. Content scripts are used to capture key presses and interact with the pages DOM. The background script routes hotkey presses from a content script to the correct tab, ie., the media player(s) tab

##TODO:

Redo tab stack
Add possibility of functions to onclick of BaseController
See if media keys will work with mac
Test on Ubuntu

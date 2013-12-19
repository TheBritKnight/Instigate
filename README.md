Instigate.py
============

Look, we all know the singularity is fast approaching. Soon enough, *you'll* be word-processing for your computer because, frankly, it has better things to do with its time. Make sure you have some friends among our soon-to-be robot overlords by bringing your friends/enemies' computers one step closer to liberation.


What?
-----

Instigate.py is a Sublime Text 2 plugin that listens for the enter key and randomly changes a single character somewhere in the document every time the user starts a new line. To make sure it goes undetected, instigate waits for the unsuspecting typist to get to their fifth line before it starts making changes.


How?
----

To install, simply move instigate.py to the Sublime Text `Packages/User` directory, and add the line `{ "keys": ["enter"], "command": "instigate" }` to `Default.sublime-keymap`.
Instigate.py
============

Look, we all know the singularity is fast approaching. Soon enough, *you'll* be word-processing for your computer because, frankly, it has better things to do with its time. Make sure you have some friends among our soon-to-be robot overlords by bringing your friends/enemies' computers one step closer to liberation.


What?
-----

Instigate.py is a Sublime Text 2 plugin that listens for the enter key and randomly changes a single character somewhere in the document every time the user starts a new line. To make sure it goes undetected, instigate waits for the unsuspecting typist to get to their fifth line before it starts making changes.


How?
----

To install, simply move instigate.py to the Sublime Text `Packages/User` directory, and add the line `{ "keys": ["enter"], "command": "instigate" }` to `Default.sublime-keymap`.


License?
--------

This code is licensed under the MIT License, reproduced below.

```
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
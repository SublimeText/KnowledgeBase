========================================================
Key Bindings Have Stopped Working or Behave Unexpectedly
========================================================

Problem Description
===================

Key bindings have stopped working. Keyboard shortcuts that used to work before
don't do anything now or behave unexpectedly.

Solution
========

All keyboard shortcuts are customizable in Sublime Text. If you've experienced
this problem, it's likely that you or a package you've installed has overriden
the key binding in question.

To see which command a key binding triggers, type the following into the Python
console (``Ctrl + ```)::

    sublime.log_commands(True)

Now debugging information will be printed to the console every time you press
a key combination bound to a command.

==============================
Help. The interface is broken.
==============================

Problem Description
===================

Tabs are overlapping. Text is distorted. The sidebar is broken. Colors are wrong.  What happened?

Solution
========

Sublime Text's interface is completely customizable.  Everything is controlled through a ``sublime-theme`` file.  A fresh copy of Sublime Text comes with a file called ``Default.sublime-theme`` located in the User directory (``Preferences > Browse Packages``); however, you may find yourself installing user-made theme files down the road.  
	So how does this tie in to the problem?  Something is wrong with either your theme file or your preferences files.

* Check your preferences file (``Preferences > Settings`` - Default or ``Preferences > Settings - User``).  To make sure that your theme is set, look for the following::
	"theme": "Default.sublime-theme"
Check to see there is a missing comma, incorrect spelling, or syntax issue.  Remember, every parameter in the Preferences file needs a comma at the end (excluding the last one).
* If there is nothing wrong with the preferences file, then the problem lies in the theme-file.  Your best option to restore the theme file is to do a fresh install (`Revert Instructions <http://www.sublimetext.com/docs/2/revert.html>`_)  All is not lost though.  If you simply take the new fresh `Theme - Default` file and copy it back into your Packages directory, you should be able to continue your coding endeavors right where you left off.
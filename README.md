soe-style
=========
All of the stylesheets associated with engineering.olemiss.edu

Document
========

* A comment block should be present in style.scss that describes the other
stylesheets in enough detail that a user can locate the correct file to modify
a style.
* A comment block should be present in each file that describes all selectors
and non-trivial attributes contained within the file
* Comment blocks should be no longer than 80 characters in width and follow the
style of the first comment block in style.scss. This style is subject to change
so take a look before writing your block.
* Do not explain trivial things. Assume the user has studied basic SASS and
CSS syntax.
* Use /* */ style comments. Never use // style comments.
* Align things with spaces. Never use tabs. This goes for code too.

Build
=====

1. Make sure sass is properly installed.
1. cd $WEBROOT/css
1. sass --watch sass:compiled --style compressed &

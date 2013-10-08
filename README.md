gerrit-trac-hook
================

This is a simple [Gerrit][0] hook for updating [Trac][0] with information about what
changes are in Gerrit review.

It parses the commit messages from Gerrit and looks for a Trac ticket in the 
style of "#1000".

It then adds a informative message to the Trac ticket about the review URL
and other data. It can also change the status of the issue to indicate that
this issue is now under gerrit review.

Script is tested with Trac 0.1.2 and Gerrit 2.6.rc0

[0]:http://gerrit.googlecode.com
[1]:http://trac.edgewall.org

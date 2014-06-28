# Asana CLI

CLI and general utility library for working with Asana

# Working and Building

Don't panic. We have a Makefile. The makefile manages the *project*
not the build.

It can make a build, of course, but that is just a useful thing, not
general way of building.

If you want to work on this and have a workspace and everything set up
for you, my recommendation is to do this:

    $ make activate
    
This sets up the workspace, moves you into it in a subprocess, etc. To
stop working on the project just exit the sub-shell (C-d or
<code>exit</code>). 


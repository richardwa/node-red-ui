# node-red-ui
node-red ui only, taken from running a server and tweaked to work with only static files.  

Employed a few tricks to do this correctly
* run node-red server 
* use httrack to mirror the site offline
* some missing resources were filled in from node-red codebase
* check for errors and missing files
* tweaked javascript and filled in missing files by hand

## Purpose
Intended to use with my mml-synth so that i can define the synth via blocks and connections.  Though I might switch gears and design it from scratch as this projects pulls in alot of extra code.  Plus i'll need to read over alot of the code  to add custom nodes, and import/export feature.  Paul has done this with his teensy audio tool.

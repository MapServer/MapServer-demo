MapServer Demo
==============

This is cleaned up version of the application/data used at the 1st MapServer User Meeting in
the "Advanced Interfaces" workshop.

It is intended to take users from a basic MapServer web application to a full-featured
DHTML-based frontend. It demonstrates topics such as URL-based configuration, virtual images
for panning, frames and DHTML.

Later additions allow the the Mapfile and datastes to demo WxS services, and the OGC Features API.

Installation
------------

- unpack workshop.zip someplace in your web tree
- edit "index.html" to reflect your configuration (there are 2 sets of comments marking 
  the sections that need to be changed)
- edit "itasca.map" to reflect your configuration (search for the keyword TOCHECK to find values that may need changing)
- point your browser at index.html and it should work

Requirements
------------

- MapServer version 8.x, basic build

Questions and/or comments should be sent to Stephen Lime, <steve.lime@state.mn.us>, 
or to the mailing lists at http://www.mapserver.org/community/lists.html

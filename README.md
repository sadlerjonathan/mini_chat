mini_chat
=========

Acknowledgement: 
This is more or less a direct copy of the work already done here: http://smithamilli.com/tuts/chat/part-one
I just added some new css/js to modernize it.


Chat Widget: Node, Express, Mongo
=================================
1. Change "http://192.168.2.111:3000/" to where ever you want (i.e. "http://localhost:3000/").

2. I have an absolute path (or two) referencing some images. Might want to change those lines.

3. Firefox will fail to connect over ws://... but will fallback gracefully after a few seconds.

4. Other than that, this should be a nice intro to node, express & socket

TO-DO:
*Currently you can open mutliple windows with the same user name, but only the last connection under 
that name can receive "whispers". I am trying to get sessions working in Express, but don't know how to do it yet.

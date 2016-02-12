Joanne Cheng
D3’s map making capabilities!
Boulder/Denver D3.js and Data Visualization
http://www.meetup.com/Boulder-Denver-D3-and-Data-Visualization/events/228560876/
Thursday, February 11, 2016
Gnip Boulder
1050 Walnut St, Suite 115, Boulder, CO

Hi all!

If you're new to D3, I _highly_ recommend going through a basic tutorial or two before coming. Here are two I like:

Three Little Circles (shorter, but goes through the basics): https://bost.ocks.org/mike/circles/

Scott Murray's D3 tutorial: http://alignedleft.com/tutorials/d3



To view map, cd into d3_map and start a http-server: "http-server -p 8008 &"

The map will be visible at http://localhost:8008/

To stop this http-server, find the Server PID#: "lsof -i tcp:8008"

Then kill the server using the PID# "kill -9 INSERTPID#HERE"

Simple-Responsive-Testing
==================
When I stumbled upon mattkersley's Responsive Design Testing tool I was inspired to create something even simpler. I took his idea and turned it into a single view that animates the width and height to popular device sizes. I also adapted a snippet from David Walsh's Blog to detect the scrollbar width and adjust the iframe's width accordingly. 

Instructions
==================
+ Copy responsive-test.html into the same directory as the file you would like to test.
+ Navigate to the responsive-test.html file.
+ Test away...

If you would like to test other device sizes simply add a new link to the controls like so:

	<a href="#" class="btn" data-width="240" data-height="320">240 &times; 320 <small>(small-mobile)</small></a>
	
Plans
==================
+	Ajax, load in iframe content.
+	Option to toggle between single view or side-by-side view.

Maintainer
==================
Matt Adams ~ @MattIn4D ~ matt@fourthdimensionweb.com
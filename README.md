# client-parallax-notifications
Provides notifications for the fractional positon of an HTML element relative to the viewport.

# [Demo](https://vivmaha.github.io/client-rect-notifications)

# Install

    $ npm install --save-dev client-parallax-notifications

# Usage
  
    var htmlElement = ...;
	var clientParallaxNotifications = require('client-parallax-notifications');
	clientParallaxNotifications.add(
	    htmlElement ,
		function(amount) {
			// do something 
		}	    
	);

# Build

    $ git clone ...
    $ npm install
    $ grunt serve

    // Deployed to http://localhost:9001/

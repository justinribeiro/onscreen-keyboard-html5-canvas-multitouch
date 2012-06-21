Multitouch keyboard implemented with HTML5 canvas, touch events API and Magictouch.js
=========================================
The following keyboard is implemented in HTML5 canvas and listens for touch events (will not work with your mouse, no mouseevent tracking implemented). We're using it with <a href="http://multi-touch-screen.com/">PQ Labs</a> overlays. 

Xoom / iPad kinda work, but we didn't optimize performance for those devices.
		
To make Chrome or Firefox on the desktop listen to touch events, you have install the <a href="https://github.com/fajran/npTuioClient">npTuioClient NPAPI plugin</a> and 
have an overlay that supports <a href="http://www.tuio.org/">TUIO</a>. Don't have an overlay? Boris Smus wrote a sweet article on the topic you 
should read: <a href="http://smus.com/multi-touch-browser-patch">Multi-Touch for your Desktop Browser</a>. We're 
using his <a href="https://github.com/borismus/MagicTouch">Magictouch.js</a> multi-touch polyfill with great success with our overlays.


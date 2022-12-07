# WoG Go Browser Formerly iVipServ Browser
iWeb is A Web Browser Based on Python And PyQt5 This is Experimental Version
iVipServ WEB is the latest revolution in web browsing! Go back and forward! Print! Save files! Get help! (you’ll need it). Any similarity to other browsers is entirely coincidental.
#Code notes
Tabbing
Adding tab support complicates the internals of the browser a bit, since we now need to keep track of the currently active browser view, both to update UI elements (URL bar, HTTPs icon) to changing state in the currently active window, and to ensure the UI events are dispatched to the correct web view.

This is achieved by using intermediate slots which filter events, and by adding signal redirection (using lamba functions to keep it short).
# ScreenShots
![iweb](https://www.pythonguis.com/examples/python-tabbed-web-browser/browser-tabbed-home.png)
<a href='https://github.com/masterofphoenix/iWEB/releases/download/0.5/Setup.exe' class='download-button'>
	Download
	<span>Latest version from GitHub</span>
</a>
<h4> First Georgian Browser </h4>


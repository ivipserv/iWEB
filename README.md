# iWEB Formerly iVipServ Browser
iWeb is A Web Browser Based on Python And PyQt5 This is Experimental Version
iVipServ WEB is the latest revolution in web browsing! Go back and forward! Print! Save files! Get help! (you’ll need it). Any similarity to other browsers is entirely coincidental.
#Code notes
Tabbing
Adding tab support complicates the internals of the browser a bit, since we now need to keep track of the currently active browser view, both to update UI elements (URL bar, HTTPs icon) to changing state in the currently active window, and to ensure the UI events are dispatched to the correct web view.

This is achieved by using intermediate slots which filter events, and by adding signal redirection (using lamba functions to keep it short).
# ScreenShots
![iweb](https://www.pythonguis.com/examples/python-tabbed-web-browser/browser-tabbed-home.png)
![iweb](https://thumbs.dreamstime.com/b/download-button-isolated-web-element-application-websites-buy-eps-166197294.jpg)
[Get it on PC](https://id.ivipserv.xyz/dl/iweb)

Other Terms
[Terms Of Use](https://www.id.ivipserv.xyz/privacy)

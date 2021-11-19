# iWEB Formerly iVipServ Browser
iWeb is A Web Browser Based on Python And PyQt5 This is Experimental Version
iVipServ WEB is the latest revolution in web browsing! Go back and forward! Print! Save files! Get help! (you’ll need it). Any similarity to other browsers is entirely coincidental.
#Code notes
Tabbing
Adding tab support complicates the internals of the browser a bit, since we now need to keep track of the currently active browser view, both to update UI elements (URL bar, HTTPs icon) to changing state in the currently active window, and to ensure the UI events are dispatched to the correct web view.

This is achieved by using intermediate slots which filter events, and by adding signal redirection (using lamba functions to keep it short).
# ScreenShots
![iweb](https://www.pythonguis.com/examples/python-tabbed-web-browser/browser-tabbed-home.png)
<a href='https://id.ivipserv.xyz/dl/iweb' class='download-button'>
	Download
	<span>Latest version from GitHub</span>
</a>
<style> 
a.download-button {
	display: block;
	padding: 15px 20px 10px 20px;
	color: #FFFFFF;
	text-decoration: none;
	font-size: 28px;
	font-weight: bold;
	background: #33A700 url('http://i.imgur.com/wt7UJ.png') no-repeat 92% 50%;
	border: 2px solid #339410;
	-webkit-box-shadow: 3px 3px 5px #000000;
	-moz-box-shadow: 3px 3px 5px #000000;
	box-shadow: 3px 3px 5px #000000;
	-webkit-border-radius: 5px;
	-moz-border-radius: 5px;
	border-radius: 5px;
	-webkit-transition: 350ms;
	-moz-transition: 350ms;
	-o-transition: 350ms;
	transition: 350ms;
}

a.download-button:hover {
	background-color: #267C00;
	background-position: 90% 50%;
}

a.download-button span {
	font-size: 14px;
	display: block;
	margin-top: 2px;
}
</style>

Other Terms
[Terms Of Use](https://www.id.ivipserv.xyz/privacy)

# Roshambo shim

*Version 1*

This is a trivially simple Roshambo AI shim. It's a simple tool for our team to pit their JS and AI coding skills against each other.

## Rules

Don't cheat. Be interesting.

## History

This simple shim is based on a University of Alberta contest:

* Overview - http://webdocs.cs.ualberta.ca/~darse/rsbpc2.html
* Season 1 results - http://webdocs.cs.ualberta.ca/~darse/rsb-results1.html
* The Iocaine Powder winner - http://www.ofb.net/~egnor/iocaine.html

## Parts

	index.php						The main UI
	bots.php						The bots API (returns a list of bots)
	roshambonator.js			The competition engine
		/lib							Libraries
		/theme						Visuals
		/bots							An upload folder for the bot JS
			example-bot.js		The example bot
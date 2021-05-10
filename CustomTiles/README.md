# SharpTools Custom Tile
Reference set up for Sharptools Tiles and Hubitat link:  https://community.sharptools.io/t/hubitat-gauge-tile/6595

PROCEDURE to load this HTML Custom Tile:................

	Create a new Custom Tile in Developers tools of Sharptools
	
	Select HTML, not URL
	
	Copy and Past all the HTML code from here to the sharptool HTML editor
	
	If Resolve box pops up hit resolve to all the radio buttons on right side, hit resolve
	
	Give it a name at the top
	
	Open "additional configuration", set tile size. Select label if you want Tile title label in editor option. you must do this.
	
	Hit update and/or save below the HTML editor
	
	Add new custom tile to dashboard and set up per SharpTools link above in post #1
	
	In dashboard Tile Editor enter the attribute name; temperature, voltage, humidity, etc.. Or what ever the Hubiat DH has to offer.

NOTES:.................

	Zero values at the end of a number wont show up. So if you change the deciamls and nothing happens then the last values are likely zeros

	GAUGES: You can easly change the gauge max/min value and color band positions by looking in the HTML code and modifying it. Its labbeled in th HTML

	TANK LEVEL: You might need to chnage the width, height, and padding in the code to center the gauge in the tile. If you get no value or the wrong value chnage the attribute number in the tile editor.


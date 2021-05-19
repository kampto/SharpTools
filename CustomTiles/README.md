# SharpTools Custom Tile
Reference set up for Sharptools Tiles and Hubitat link:  https://community.sharptools.io/t/hubitat-gauge-tile/6595

PROCEDURE to load this HTML Custom Tile:................

	Create a new Custom Tile in Developers tools of Sharptools
	
	Select HTML, not URL
	
	Copy and Paste all the HTML code from here to the sharptool HTML editor
	
	If Resolve box pops up hit resolve to all the radio buttons on right side, hit resolve
	
	Give it a name at the top
	
	Open "additional configuration", set tile size. Select label if you want Tile title label in editor option. you must do this.
	
	Hit update and/or save below the HTML editor
	
	Add new custom tile to dashboard and set up per SharpTools link above in post #1
	
	In dashboard Tile Editor enter the API Url, DeviceID and Attribute name; temperature, voltage, humidity, etc.. Or what ever the Hubiat DH has to offer.
	
	Change other Tile editor settings as needed or use the defaults
	
NOTES:.................

	-For some reason sometimes the "check box" boolean tile settings in the tile editor dont take until you click and unclick or vs versa.
	-Zero values at the end of a number wont show up. So if you change the deciamls and nothing happens then the last values are likely zeros
	-Depending on you screen resolution and dashboard tile size, it may be nessasary to edit the dimenions of content in the HTML editor. Sometime in multiple places.
	

	GAUGES: You can easly change the gauge max/min value and color band positions by looking in the HTML code and modifying it. Its labbeled in th HTML

	TANK LEVEL: You might need to chnage the width, height, and padding in the HTML code to center the gauge in the tile. 
	
	PLOT: The data from the plot is stored in the browser, so if you refresh browser it will restart from zero. Cycle the check boxes in tile editor for them to take.
	
	HUBITAT DEVICE ATTRIBUTE: A way to grab data from a device (temperature, contact, switch, etc..) and make a tile to display it with font, units, and decimal options.


ATTRIBUTE NAMES:  Open the Hubitat Device to see what attributes are availible.

![image](https://user-images.githubusercontent.com/31904505/117594195-6cde1500-b0f2-11eb-9de6-e6bbf0a7bc32.png)

MANDATORY DASHBOARD TILE EDITOR OPTIONS: you must fill these 3 out at the very least

![image](https://user-images.githubusercontent.com/31904505/117595076-8ed89700-b0f4-11eb-850d-89cdada15593.png)

GAUGE EXAMPLES:
![image](https://user-images.githubusercontent.com/31904505/118742984-4f9dfa80-b806-11eb-9292-bbdaef3b0e01.png)

PLOT EXAMPLES:


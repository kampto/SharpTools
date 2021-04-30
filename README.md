# SharpTools
Reference set up for Sharptools and Hubitat link:  https://community.sharptools.io/t/hubitat-gauge-tile/6595

Procedure to load this HTML:
Create a new Custom Tile in Developers tools of Sharptools
Select HTML, not URL
Copy and Past all the HTML code from here to teh sharptool HTML editor
If Resolve box pops up hit resolve to all the radio buttons on right side
Give it a name at the top
Open additional configuration and set tile size. Select label if you want Tile label option
Hit update or save below the HTML editor
Add new custom tile to dashboard and set up per SharpTools link above.

Notes:
Zero values at the end of a number wont show up. So if you change the deciamls and nothing happens then the last values are likely zeros
You can easly change the gauge max/min value and color band positions by looking in the HTML coade and modifying it. Its labbeled in th HTML

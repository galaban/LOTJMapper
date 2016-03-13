# Galaban's LOTJMapper
This is an update to the LOTJ mapper built by Xavious, which came from Johson, which was ported from Aardwolf mud, which came from...Well, you get the idea.  Ultimately, it goes all the way back to Nick Gammon.

Seriously... this came from here:
https://github.com/Xavious/LotjClient

##Fixes
This is the list of changes that I made to the standard (err...Xavious's) plugin:
* Added room deletion.  So now you can delete a room if you want
* Auto-exit tracking for inverse directions.  (No more walking around like an idiot)
* Added a "mapper goto" function so that you can "goto 3106".
* Fixed several bugs caused by moving too quickly for the crappy MSDP implementation
* "mapper output X" to be able to see some debug information for the LOTJ Mapper

Other than that, it works just like Xavious's mapper.  Click to walk, right-click to define rooms, mapper hide/show, etc.

## To install
1. Download the raw file from github:
https://raw.github.com/galaban/LOTJMapper/master/LOTJ_Mapper.xml
2. Place the raw file into your "plugins" directory.  This is fund in your Mushclient folder under /worlds/plugins.
3. Install the plugain in MushClient.  From the "File" menu, choose "plugins", then "Add".  Select the file and choose "OK".

Note: This requires colors.lua and Johnson's MSDP plugin... just like Xavious's does

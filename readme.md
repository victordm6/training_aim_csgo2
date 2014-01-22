#training_aim_csgo2
##Current release: 0.3.3

For the past few months I've been training on kataS' famous training_aim_csgo map.
There were a lot of gameplay and graphical bugs that I wanted to address. 
I also ended up adding and improving a lot of features as well. 
This is a work in progress, so subscribe and please leave feedback.

----

#####How to install and use:

* Go to the [Steam Workshop](http://steamcommunity.com/sharedfiles/filedetails/?id=213240871"Steam Workshop") link and click Subscribe.
* Launch the game.
* Click Play.
* Click Offline with Bots in the drop-down menu.
* Click Workshop.
* Double click training_aim_csgo2. 

----

###Changelog
 
####0.1.0

#####Gameplay
* Fixed spawning in pit.
* Fixed bot being hostile.
* Fixed warm up not ending.
* Warm up timer reduced to 5 seconds.
* Fixed weapons board.
* Added silenced weapons to weapons board.

#####Graphics
* Overhauled textures to solid colors.
* Changed shooting wall texture to white.
* Changed roof to glass.
* Fixed clipping issues.
* Added sun matching cs_office (light_environment).
* Removed uneven indoor lighting.
* Changed skybox to cityscape.

####0.1.1

#####Gameplay
* Moved start/stop buttons in to the walls, as to not accidentally be triggered.
* Fixed ladder on second level.
* Fixed some clipping issues.

#####Graphics
* Changed shooting wall texture to orange grid.
* Disabled Bloom and HDR to help with brightness problem.
* Made lighting dimmer.

####0.1.2 

#####Gameplay 
* Added "ding" sound when triggering buttons.

####0.1.3

#####Gameplay 
* Warmup works properly with custom gamemode.
* Fixed minor clipping issue.

####0.2.0

#####Gameplay 
* Added new, cleaner weapons board featuring weapon icons and separate entries for silenced weapons.

#####Graphics
* Fixed texture z-fighting.
* Optimized various parts of the map.

####0.3.0

#####Gameplay
* Added multiplayer support for teams of 5 each.
* Lengthened ladders so it is easier not to fall off (thanks Surfing-Nymph).

#####Graphics
* Removed border around options menu.
* Retextured some areas.
* Optimized map in general.

####0.3.1

#####Gameplay
* Fixed bug where weapons board did not drop your previous weapon.
* Fixed config.
* Removed warmup completely. 

####0.3.2

#####Gameplay
* Fixed bug where the game would trigger a map change. 

####0.3.3
* Increased round time to 60 minutes. 
----

###To Download on Github (for dev usage):

Copy the csgo folder to
"C:\Program Files (x86)\Steam\SteamApps\common\Counter Strike Global Offensive"

Then, copy training_aim_csgo2_a1.vmf from the vmf folder in to
"C:\Program Files (x86)\Steam\SteamApps\common\Counter*Strike Global Offensive\sdk_content\maps"

----

###Planned features
* Being able to change shooting wall texture
* Being able to change brightness
* ~~New weapons board texture~~
* Possibly new rooms, etc
* Better lighting
* New shooting modes
* Control over bullet decals
* Being able to toggle infinite ammo modes
* More bugfixes

----

###Links

[Youtube](http://www.youtube.com/watch?v=qS8DWKxMPCk&list=PLie_jw7Bdb2FOZjoKQTGWLtwnICY8Glnr&index=4"Youtube")

[training_aim_csgo](http://csgo.gamebanana.com/maps/168139"Gamebanana")

<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="encrypted" value="-----BEGIN PKCS7-----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-----END PKCS7-----
">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>








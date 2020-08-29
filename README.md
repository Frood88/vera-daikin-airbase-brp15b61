# Daikin Airbase BRP15B61 #

This was going to be a new plugin for the Daikin BRP15B61 WiFi controller module for Vera UI7, but I realised that some small modifications to some files in an existing plugin was all that was required.

This is my first attempt at modifying a plugin for Vera and is very much a work in progress - suggestions/additions welcome!

The LUA files above are supplementary to asahani's plugin below (which is for the older Daikin SkyFi controller) - install that plugin, then upload the modified LUA files above to Vera to update it for Airbase compatibility, then configure the new device in Vera, based on asahani's instructions.

You may also find it interesting to compare the differences between the files above and the equivalent original files in asahani's plugin to see the critical I've found (so far) between the older and newer Daikin interfaces.

## Current Critical Capabilities ##

Working as intended:
 - Change mode between Off/Heat/Cool from Vera takes effect immediately on the wall controller
 - Change temperature for Heat/Cool modes from Vera takes effect immediately on the wall controller
 - Mode and Temperature changes made on the wall controller are visible in Vera at next update/poll
  
Work still in progress:
 - Change mode to Auto from Vera
 
## Acknowledgements ##

I would like to thank asahani for having an excellent central place for plugin development and other references and to all who asahani acknowledges.

https://github.com/asahani/vera-daikin-wifi-controller

## References ##
* Forum - Daikin Airbase BRP15B61 WiFi Controller - http://forum.micasaverde.com/index.php/topic,124006.0.html
* Forum - Daikin Airbase - https://forums.whirlpool.net.au/thread/2768285

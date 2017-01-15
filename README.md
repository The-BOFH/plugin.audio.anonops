
# plugin.audio.anonopsradio V2 Branch
Plugin for Kodi/XBMC to tune into Anonops Radio!

Version 1.5.0

## Notes
Version 1.5.0 is a Fork of SimpleKores's Sample addon (it appears to be an uncredited fork of another popular kodi addon)
https://simplekore.com/how-to-make-a-video-add-on-for-kodixbmc/

There is a Lot of Unused code in this addon from the original and will be removed in a future release.
The Addon was originally For Playback of Videos 
a lot of the unused code is pointed to a bunch of known video sites and even some now dead ones. you wont see any of that content appear in the addon.  

we could really use a python developer!

If you think you can help in removing the unused/unwanted code please fork the addon,

You will be rewarded.

My Branch serves the Catagories list,Station list,archive list, and all server sided lists from cdn.basedsec.pro

Background images are the ones from the radio.anonops.com index page and are loaded from there with the exception of 8.jpg

The Icons are loaded from This Github with the exception of icon.png in the addon

### Changes

Server Sided Station/Archive/Video list, Should Anonops ever decide to host part of or the whole addon they would be able to have full control of what station and who is in the archive,etc, they could even get real creative and give the DJ's the ability to edit their archive without giving them access to an anonops backend. 

--
Added in a Archive Section! This will be further expanded on once I figure out a Viable method for archiving them.

MixCloud and other Services are using cloudflare and or other WAF software that makes hotlinking to the direct file impossibile with kodi

I have a Proposed Solution for this,

I could host the archives of the shows on cdn.basedsec.pro

I have No Problem hosting Archives of RadioShows but some may consider this a conflict of interest.

An alternative is if the dj provide his own hosting then the files could be hotlinked there.

Another could be let anonops host it (unlikely)

If we can find a host that we can upload mp3/m4a and hotlink to it then that could work.

Im opting to host archives on my cdn because i want to provide a stable host and dont want an addon that points to a bunch of 404'd links



--


Added in a Section For Youtube Videos, This could be useful for something in the future.

#### Installation Instructions:

1) Download The File file plugin.audio.anonopsraido.zip to the Device with kodi you want to install on.  
2) Launch Kodi  
3) Settings -> Addons -> Install From Zip File -> select zip file  
4) install done!  

Then, go to your Music Addons section, open Anonops Radio, and select the stream you want to tune into.

Enjoy!

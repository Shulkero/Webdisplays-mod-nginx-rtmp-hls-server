# Webdisplays-mod-nginx-rtmp-hls-server
Basically took a precompiled nginx with rtmp and added a hls player. This was made for Minecraft's Webdisplays mod:

Seems to work fine for this version --> https://www.curseforge.com/minecraft/mc-mods/webdisplays
This is a pretty good nginx server for streaming any content on your computer to the webdisplays screen. With some program
broadcasting like OBS you can input a specific address: rtmp://ip:port/live, then you can load the website on a browser
(by default the stream key is just set to stream. You may need to set ports in the nginx.conf and the default url for the video player would be ip:port/viewer.html)
With

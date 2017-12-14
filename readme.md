# SmartOS Zone Configs

These are just for my personal use, but feel free to modify and try them for yourself. The json files just provision the zones as I like them- you'll still need to connect to each and install the services required.

Note: you can use `git clone` if you have `git` installed in the global zone on your SmartOS. Otherwise, just copy and paste.

## DIY
`$ imgadm update`  
`$ imgadm import 7b5981c4-1889-11e7-b4c5-3f3bdfc9b88b`  
`$ vim plex.json`
`[paste contents in new plex.json file]`   
`$ vmadm validate create -f plex.json`  
`$ vmadm create -f plex.json`  
`$ vmadm list | grep plex`  

## To Do
- add nzbget json file

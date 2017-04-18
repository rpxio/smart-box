# smartos zone configs

these are just for my personal use, but feel free to modify and try them for yourself.

### diy
`$ imgadm update`
`$ imgadm import 7b5981c4-1889-11e7-b4c5-3f3bdfc9b88b`
`$ git clone https://github.com/rpxio/smart-box.git`
`$ cd smart-box`
`$ vmadm validate create -f plex.json`
`$ vmadm create -f plex.json`
`$ vmadm list | grep plex`

you'll still need to login to each box and install the services as required.

### todo
- add nzbget json file

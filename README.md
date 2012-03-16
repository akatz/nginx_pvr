# Nginx Config for PVR #
So I had these 3 tools running locally
Couch Potato Movie manager
http://couchpota.to/
SickBeard PVR
http://sickbeard.com/
SabNZBD
http://sabnzbd.org/


## Dependencies ##

Sickbeard
CouchPotato
SabNZBD
Nginx

## Installing ##
After the servers are up and running

`brew install nginx`

When its done installing you can copy these files over the existing files in
your /etc/nginx/ directory in your homebrew root.

change any references to me in the file "akatz"
change any path references from /Users/akatz/Developer to your homebrew root

Add DNS entries in your router for the server names configured. In my file they are:
sab
couchpotato
sickbeard

you can chane these to anything, even a FQDN if you want.

Enjoy

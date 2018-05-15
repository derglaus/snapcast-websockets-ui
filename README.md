# snapcast-websockets-ui
UI for snapcast using websockets


Features:

Client: Rename, set Latency, set Volume, Mute, assign to Group

Group: Mute, select Source

Graphics should be ok on Firefox and Edge, mediocre on Chrome and bad on Internet Explorer. If anyone wants to put an effort there: help is appreciated...
### update: at least a bit improved graphics. Improved Volume Control (smaller steps easier possible with second scale)

![Screenshot](https://github.com/derglaus/snapcast-websockets-ui/blob/master/screenshot.PNG?raw=true)

How to:

Install and configure https://github.com/badaix/snapcast

Install https://github.com/novnc/websockify

start websockify automatically at startup: websockify 2027 :1705

Option 1:
Install a webserver that supplies the snapcast-websockets-ui interface.html to the client

or Option2:
Store the interface.html locally (and edit the server address to match you snapserver/websockify

Browse to index.html. No configuration is needed.

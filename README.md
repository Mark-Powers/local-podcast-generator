## local-podcast-generator for android
Host a podcast from the files on your phone

### Parent Repo
This project is a fork of [lWS](https://github.com/mvbasov/lWS).

### Config
* Document root. Path may be entered as text or optional elected using OI File Manager.
* Port. May be from 1024 to 65535. Default is 8080
* Podcast Name. Name of the podcast feed

### Document root
The path where files will be added to the RSS feed from.

### "Open in browser" and "Send URL"
After server starts you can press "Open in browser" button for check.
You can send working server URL to another device by Bluetooth, Android Beam, E-Mail and other way available on your device.

### On screen log
The application has no permanent logging. I treat this as redundant functionality. I doing my best to make notification actual all time. On screen log actual only then application visible. Log screen may be cleared after returning from background.

### Security warning
You can change document root to any readable point of file system, but you need to understand what are you doing.
<b>Be careful: you could (suddenly?) create the configuration so way, than anyone on the same WiFi network could access to the data on your device either you don't like it.</b>
All files from document root and below available for reading without any restrictions to anyone who connected to network and known URL of the server.

### License
local-podcast-generator is licensed under the [GPLv3 License](LICENSE)
Directory listing sort based on [this project](https://github.com/wmentzel/table-sort) licensed under GPL-3.0

### Artwork
* File listing icons from [Feather project](https://feathericons.com/) released under MIT license.
* Application icon designed for lWS.


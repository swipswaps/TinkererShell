# TinkererShell
A simple reverse shell written in python just for fun.
Actually it supports Windows and Linux OS and integrates some basic functionalities like keylogging, sending collected data via email and AES encrypted communications.


### Supported operative systems:
 - [x] Windows
 - [x] Linux
 - [ ] OSX

### Functions and characteristics:
 - [x] Reverse connection
 - [x] AES encrypted communications
 - [x] Multithreaded
 - [x] Support multiple bots connected at the same time
 - [x] Keylogger
 - [x] Possibility to send keylogged data periodically via email
 - [x] Possibility to enable or disable persistence (before payload delivery or later via remote control)
 - [x] Possibility to enable or disable keylogger (before payload delivery or later via remote control)
 - [x] Simple DNS spoofer (via hosts file)
 - [x] Capability to upload and download files to and from the bot
 
 > Work in progress... stay tuned!
 
#### TODO:

* Modify the bots to keep trying to reconnect to master even if the connection has been terminated by the master.
* Split source in modules.
* Thoroughly test persistence function on Linux.
* Thoroughly test persistence function on Windows.
* Configure/Enable/Disable mail activation from shell cmd.
* Add clipboard monitoring and clipboard content capturing.
* Add active window recognition.
* Add screenshooter.
* Add webcam and microphone recording (ideally streaming from bot and saving locally to master).
* Exit master cleanly after closing all connections.



**_This project is for educational purposes only. Don't use it for illegal activities. I don't support nor condone illegal or unethical actions and I can't be held responsible for possible misuse of this software._**

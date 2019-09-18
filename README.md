# x11vnc
A desktop application to start x11vnc 
Create x11vnc.desktop

This trick is intended to sole the problem when x11vnc  ( server ) that gets started during bootup shuts down for some reason and you cannot reboot the linux desktop since you are stuck in the middle of busy development. Launching x11vnc from a bash shell is not an option since the vnc server shuts down when you close the shell window.
This is a .desktop file to be placed in the "Desktop" folder of User's home directory. For example if you are a user "noname" ,
place this folder under /home/noname/Desktop .
This file assumes that you have x11vnc installed to share the console session of the linux over a vnc.
Once this file is placed , make sure it has executable permission (chmod +x  /home/noname/Desktop/x11vnc.desktop ). 
once done , you can click this from the Desktop to launch x11vnc .

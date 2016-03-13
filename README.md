app.desktop
===========

these are desktop files, used in linux systems to indicate a type of "app shortcut". if you have a program installed, this is what tells your app menu where it is, what to run, and what icon it should use.

these are some customized desktop files that i use to add specified commands to my app menu (in XFCE, but should work for any desktop environment i think)

simply modify as needed and put them in ~/.local/share/applications/nameofapp.desktop. if there is a program installed that already shows up in your app menu, these will take their place, so you can update the app without fear of overwriting the system's desktop file for it.

the most special example is **ssh.desktop** which you can set as a handler for ssh:// links. this one grabs the link and puts in in a temporary file, and then starts a tmux session using my specified scripts to launch the ssh connection in a local tmux window.

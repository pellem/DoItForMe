Automatic install for Epitech basic tools

You just have to donwload init.sh, chmod it if needed, launch it where you want and let it do the job for you.

You need to be sudo to install the different features.
If you're running the bocal's distrib from Epitech you must not be sudoer.
You will already have git and zsh installed so don't worry.

THIS WILL INSTALL SOME FEATURES YOU MAY NOT WANT.
That's not my problem. You should be bright enough to change the code removing/adding features you want.


Current files versions:

init.sh:
- [x] Create "bin" dir (if it doesn't exists in your ~ (/home/$USER))
- [x] Check if git and zsh are installed (or will install those shit)
- [x] Create a temp directory with exotic name
- [x] Clone this repo (Epitech_Tools.git) in the temp dir
- [x] Move .sh in /home/$USER/bin
- [x] Move zshrc.cfg to /home/$USER/.zsrc
- [x] Remove temp folder

![alt tag](https://raw.github.com/NoImNot/Epitech_Tools/master/images/showroom.png)

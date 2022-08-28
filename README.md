# stigmarchpkg
Just a list of my starting arch packages and some configuration

In the cloned directory:

sudo pacman -S - < pkglist.txt

---------------------------------------------------------------------
This instruction will overwire your existing ~/.bashrc configuration
In the cloned directory:

cp bashrc.txt ~/.bashrc

---------------------------------------------------------------------
Move the image in the cloned directory to Pictures in the home folder

In the cloned directory:

mv xoxo.jpg ~/Pictures

---------------------------------------------------------------------
To change the image displayed with neofetch change the image path in bashrc

neofetch --kitty ~/Pictures/xoxo.jpg

---------------------------------------------------------------------
The aliases that comes with this bashrc are 
pog -> for "sudo pacman -Syu"
pagman -> for "sudo pacman -S"
waifu -> for "neofetch --kitty ~/Pictures/xoxo.jpg"

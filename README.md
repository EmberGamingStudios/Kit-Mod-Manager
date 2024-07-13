# Kit-Mod-Manager
An Unofficial Minecraft Mod Manager for Linux.

This is a Minecraft mod manager for GNU/Linux written in Python and Qt. You can easily see the code for yourself by opening this file in a text editor. 

It SHOULD work with both Forge or Fabric mods on any version of Minecraft Java Edition.

Setup:
  1. Put the KitModManager file in your home directory (NOT the /home directory).
  2. Create a folder called modpacks in your home directory- you will put your mod pack folders in this folder!
  3. Each modpack will use a seperate folder in the modpacks directory that you can select to use. 
  4. To launch this you will run the command: python3 KitModManager (I recommend creating a Desktop launcher for this so you don't have to run the command every time you want to use it).
  5. To load a mod pack, you click on the checkbox next the name and then hit the "Load Mod Pack" button- you should see all the mods in the modpack appear in the "Loaded Mods" window.
  6. To unload a modpack from Minecraft hit the "Remove Mod Pack" button- you should see all the mods in the "Loaded Mods" window disappear.

You may probably have to install PyQt5 and the Qt framework: 
  PyQt5: pip install PyQt5
  
  Qt framework:
  Debian/Ubuntu: sudo apt install qt5-default
  Fedora: sudo dnf install qt5 qt5-devel
  Arch: sudo pacman -S qt5-base qt5-tools

I haven't tested this with Qt 6 yet, but it should still work (don't quote me though).

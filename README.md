# The BoisMC server mods (1.12.2)

I do not own any of this. No copyright infringement intended. All rights and respects are reserved by the mods' creators.

### Setup:
These instructions assume you have a working Minecraft installed to your computer.

If already have forge 14.23.5.2854 set up for 1.12.2, skip steps 1 & 2, though you should [make sure at least 4 GB of memory is allocated to the installation](https://youtu.be/SfVJq2Csln4?t=170).

If you already have Git installed and know how to use it, skip step 3.

  1. In minecraft, create a 1.12.2 installation, run it, then close it.
  2. Download [Forge](https://files.minecraftforge.net/maven/net/minecraftforge/forge/1.12.2-14.23.5.2854/forge-1.12.2-14.23.5.2854-installer.jar) and install it [with atleast 4GB of ram allocated](https://youtu.be/SfVJq2Csln4?t=170), run it, then close it.
  3. Download [Git](https://git-scm.com/downloads) and install it with mostly recommended settings.
    
  Git specifics

    1. You can choose a different editor if you'd like.
    2. In "Configuring the line ending conversions", on Windows choose the option beginning with "Checkout Windows-style". All other operating systems choose "checkout as is, commit Unix style endings.
    3. If on Windows, in the next window, choose "Use Windows' default console window"
    4. Credential helper is optional.
    5. Install. No need to launch git bash.

  4. Go to your .minecraft folder and copy the [folder address](https://imgur.com/a/wY1BkLA) by clicking on it and copying.
  5. If there is a mods folder in .minecraft, delete it.
  6. Open a command prompt and type "cd ", then paste and press enter.
  7. On this github page, click the green button at the top that says code, and copy the link it gives you.
  8. In the command prompt type "git clone ", then paste and press enter. Once this completes, there will be a folder called "tn_minecraft_mods" inside your .minecraft folder. Rename this folder to "mods".
  9. You may now exit the command prompt.

Once you've completed these steps, your Minecraft should be ready to join the server.

### Update:
These instructions assume you have completed the setup.

If your Minecraft suddenly isn't able to join the server or you've been informed that the mods have been updated, follow these steps.

  1. Go to your .minecraft/mods folder and copy the [folder address](https://imgur.com/a/wY1BkLA) by clicking on it and copying.
  2. Open a command prompt and type "cd ", then paste and press enter. 
  3. Type "git pull origin master" and press enter, then wait for it to complete.
  4. You may now exit the command prompt.
  
Once you've completed these steps, your Minecraft should be ready to join the server.

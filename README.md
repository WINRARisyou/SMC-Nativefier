# SMC-Nativefier
Tutorial on how to run Super Mario Construct as an app using Nativefier

This guide assumes you have admin rights on your PC, so if something doesn't work, that's probably why.

First, watch [this tutorial](https://www.youtube.com/watch?v=_Ob56Twu7DM) (any tutorial will probably work really) on how to install nodejs, and ensure that you install npm along with it (there should be a button in the installer for it).

After nodejs and npm are setup, open command prompt and install nativefier by running this command ```npm install nativefier --global``` (I've always installed it globally so I don't know what changes when it's not global) and check to see if it installed by running ```nativefier --version```

Now make the folder that you want the game files to be in and enter it in command prompt by right clicking and pressing "Open in Terminal" on Windows 11, and by typing "cd" into Command Prompt and then dragging the folder into the window and pressing enter on Windows 10.

Finally, once in the folder that you want to install the game to in command prompt, type this command ```nativefier "https://levelsharesquare.com/html5/supermarioconstruct/" --name "Super Mario Construct" --platform windows --arch x64 --disable-dev-tools --width 832 --height 480 --min-width 832 --min-height 480```

Congrats, you now have Super Mario Construct as an app on your PC.

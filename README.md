# CS2-Radio_player
This set of configs facilitate listening to every radio messages available in Counter-Strike 2.

Installation
Open the archive and extract its content into the following path folder :

  "\...\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\radio_player\"
Launch the game, boot up a practice server where you can turn on sv_cheats 1 and type in the console the following command: "exec radio_player\radio_player.cfg".

Your console should display a message saying : "RADIO_PLAYER loaded succesfully ! :)"; otherwise you must have a path issue and the file did not load correctly.

Close the console and press MOUSE1 to start cycling between the radio commands.

Usage
Type in the console "exec radio_player\radio_player.cfg" to load the config into the game.
radiomsg is the main command to use.

Everytime you use the radiomsg keybind, it will play the current radio command in stack, then store the next one in memory.
If you want to skip to a specific radio command, type radiomsg[number] into the console, the keybind radiomsg will keep it in memory.

If you want to reset to default mousebind, type resetmouse in console.
The only file you should ever modify (if you know what you're doing) : "...\cfg\radio_player\radio_player.cfg", otherwise you will probably break the script !
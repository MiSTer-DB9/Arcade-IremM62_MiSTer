A new option has been added in the OSD menu of this core called: "UserIO Joystick" that allows playing with joysticks Mega Drive/Genesis (DB9) or Neo-Geo/Supergun (DB15). This new feature is disabled by default, therefore you must enter the menu (F12) the first time to activate it and save config.

This core are updated at the same rate as the official core, therefore, it preserves the same functionalities as this, and also adds the possibility of directly connecting DB9 and DB15 joysticks.

For total control from the UserIO Joysticks (also the OSD menu) also is necessary to update the files: MiSTer and menu.rbf from the root of the SD card. The link to these files is here (dowunload the last release):

MiSTer_Main: 
https://github.com/Miguel-T80c/Main_MiSTer/tree/master/releases

Core Menu:
https://github.com/Miguel-T80c/Menu_MiSTer/tree/master/releases


Menu control from DB9 joystick: 
Start+C-> Show OSD menu  |  A-> Enter  |  B-> Esc


Download the updater script to always have all the cores updated, for this you must replace the current file update.sh in /scripts/Update. Thus, will download the official versions of all cores in the same way but also, if there is a DB9 version, in this case it will download the DB9 version. The first time this script is launched, the process it will be slower because it will do a general update.

Updater script:
https://github.com/theypsilon/Updater_script_MiSTer_DB9/blob/master/update.sh

Also you can get more informaticon about DB9 fork from this links: 
https://github.com/antoniovillena/MiSTer_DB9.git
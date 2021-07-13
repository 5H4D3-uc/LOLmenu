# LOLmenu

# THIS IS OUTDATED / NOT WORKING! IT IS NOT READY TO USE!

# THIS IS BASED OFF [VA-LOL-RANT](https://www.unknowncheats.me/forum/valorant/414174-va-lol-rant-internal-external-aimassist.html) MADE BY @pean153

# Intructions:
1. Download [interception](https://github.com/oblitum/Interception)
2. Go into Interception > library > x86
3. Copy interception.dll to any folder you want
4. Set a path system variable (if you don't know how google is your friend) to the folder you copied interception.dll to
5. Open your cmd
6. Navigate to Interception > command line installer
7. type - install-interception /install
8. Restart your pc
9. Build the dll yourself (If any errors please look through the forum. The most common error is \_CRT_SECURE_NO_WARNINGS and a LINK error. Just for convenience see below on how to fix them. Otherwise use your brain :])
10. Inject into a 32-bit proccess

**IMPORTANT - COMPILE IT AS x86 (PROJECT SETTINGS ON DOWNLOAD DON'T DEFAULT TO IT)**

# ERROR FIXES (SKIP THIS PART IF YOU DON'T GET ERRORS WHEN BUILDING)
        - for _CRT_SECURE_NO_WARNINGS go to the dll properties > C/C++ > preprocessor > in the Preprocessor Definitions add _CRT_SECURE_NO_WARNINGS
        - for a LINK error go to the dll properties > Linker > General > under Additional Library Directories add a path to Interception > Library > x86.

# GENERAL INFO
NOTHING is set to default. Set every setting yourself, then commit the changes. If you skip over a setting, it won't work correctly. It doesn't tell you if you missed a step. It will, however, tell you if you've entered something wrong.

If you want the cheat always on, set your toggle key to be a toggle, press your key, and leave it on.

From @pean153's post "Smoothing has reasonable values around 0.01-0.2 based on your CPU and setup. The mode has 3 values (1, 2, 3). 1 is for Shot correction only, 2 is for AimAssist only, 3 is for both."

**WORKS IN FULLSCREEN**

**RED ISN'T IMPLEMENTED**

**EVERYTHING IS CASE SENSITIVE. WHEN ENTERING YOUR SELECTION (e.g., CHEST, NECK, HEAD), TYPE IT IN ALL CAPS; OTHERWISE, IT WON'T GO THROUGH. THE PROGRAM SHOULD TELL YOU IF WHAT YOU'VE ENTERED IS INVALID.**

**WHEN CHANGING YOUR TOGGLE KEY IT'S NORMAL TO SEE "ENTER CHAR UP TO: " (THIS IS BECAUSE OF PRESSING F2 IN CONSOLE) IT'S SAFE TO IGNORE, PRESS ANY KEY TO GET RID OF IT AND ENTER YOUR CHOICE.**

# KNOWN BUGS
 - When setting certain settings, your input from the previous setting you've set will be in the prompt. To avoid any errors, remove the things present and type your selection.
 I've tried everything to fix this. The cin.clear() doesn't work for some reason. Maybe I'm missing something; feel free to let me know.

# UPDATE #1
- Added an aim FOV option
- Added the option to load a config; in the GitHub you'll see "config.ini" if you wish to use this, put it in the directory of whatever you're injecting to, right-click it, and press edit. Then from there, you enter your settings and launch the cheat 
+ When the config is present, you'll be asked if you want to use the config file when you launch the cheat. If you type NO (case sensitive), it will continue to the usual set-up. If you type YES, it will load the config, display your config and
automatically close.
+ If you wish to not use the config at all, do not add it to the directory of your injected program, and it will continue with the normal set up prompt 
+ All the instructions for config will be in the config.ini

Spent a couple hours writing this. Hope you guys enjoy. Have fun.

Updated image 1:
https://imgur.com/a/mplaLn7

Updated image 2:
https://imgur.com/a/98t2kIM

# ENJOY :D

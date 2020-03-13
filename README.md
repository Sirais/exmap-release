## exmap: Simple and lightweight maphack and zoomhack

### [UPDATING FOR 3.10, PLEASE WAIT...]

#### **[Click here to ask for help and support](https://www.ownedcore.com/forums/mmo/path-of-exile/poe-bots-programs/842622-exmap-2-0-simple-lightweight-maphack.html)**

#### Overview

This program reveals the entire map and increases the maximum camera zoom in Path of Exile. This is as simple as it gets - just a maphack and a zoomhack. It's designed to be lightweight and easy to use. Just double-click and you're done.

#### Features

- Full map revealed on area load.
- Maximum camera zoom increased to 200%.
- Option to disable ambient fog.
- Option to disable far plane culling.
- No modifications to game memory.
- No open handles to the game.
- No administrator privileges required.
- No fumbling with Cheat Engine tables required.
- **Works with Steam and standard clients only.**
- **64-bit client only.**

#### Disclaimer

Cheating is bad. Using this program is against the game's terms of use. This is currently not detected; however, the anti-cheat could be changed to detect this. I will not be adding more anti-detection over time. **There is always a risk.**

#### Quick Start

1. Start the game.
2. Double-click on *exmap.exe*. You do not need to run it as an administrator.
3. The maphack will be automatically activated.

**Do you run Path of Exile as a limited user? If so, you also need to do the following:**
- **You *must* run the maphack and the game as the same user.**
- **You *must* allow the game to access the folder that exmaplib.dll is in.**
- **Doing this does not make it easier to detect the maphack.**

#### Configuring

You can change the configuration of the maphack by editing *exmaplib.dll.ini* in your favorite text editor to enable or disable specific features. You do not need to restart the game - the maphack will pick up your configuration changes as soon as you save the file.

#### Common Issues

**I get error code EE: 0xA0000003 LE: 5 when I try to run the maphack.**
See the instructions above. This is usually because you are not running the maphack using the exact same user that the game is running with. You need to run them as the same user. You also need to make sure the game can access the folder where the maphack is saved.

#### Screenshots

![](https://github.com/m4p3r/exmap-release/raw/master/img/before.png)
*Maximum zoom range normally.*

![](https://github.com/m4p3r/exmap-release/raw/master/img/after.png)
*Maximum zoom range with exmap.*

#### Changelog

*Version 2.4 - March 11, 2020 ([Download](https://github.com/m4p3r/exmap-release/raw/master/bin/exmap_240.zip))*
- Increased maximum zoom range to 200%.
- Added option to disable far plane culling.
- Added option to disable ambient fog rendering.
- Added configuration file to disable or enable settings. You can change these settings while the game is running.
- Fixed an issue where the game would be frozen until clicking OK on load.

*Version 2.3 - March 8, 2020 ([Download](https://github.com/m4p3r/exmap-release/raw/master/bin/exmap_230.zip))*
- Fixed the zoomhack to now work with both keyboard and mouse zooms.
- Fixed several potential performance issues.
- Removed alternate loading method.

*Version 2.2 - March 6, 2020 ([Download](https://github.com/m4p3r/exmap-release/raw/master/bin/exmap_220.zip))*
- Added an alternate loading method to help with users who run the game as a limited user.

*Version 2.1 - March 3, 2020 ([Download](https://github.com/m4p3r/exmap-release/raw/master/bin/exmap_210.zip))*
- Increased maximum zoom range to 150%.

*Version 2.0 - February 6, 2020 ([Download](https://github.com/m4p3r/exmap-release/raw/master/bin/exmap_200.zip))*
- Updated maphack to work with 3.9.2e.
- Refactored to eliminated the need for elevated privileges.
- Removed packet logger.
- Removed hotkeys.

#### Special Thanks

The following are people who gave me helpful information at some point over the years.

- zaafar
- ankorman
- TehCheat

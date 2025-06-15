![SusAlert](/assets/banner.png)

# SusAlert
SusAlert is an alt1 toolkit app designed for the Sanctum of Rebirth bosses in RuneScape. It tracks a boss' attacks and provides visual and (optional) audio cues. It can also monitor the Crystal Mask spell. The app currently supports Vermyx, Kezalam and Nakatra.

![SusAlert-MainWindow](/assets/mainscreen-overview.png)
## How to use
SusAlert is easy to setup and use, simply install (instructions below) and open the plugin in alt1 toolkit, and you're good to go! SusAlert will automatically detect when the fight starts and ends. The default attack schedule is Vermyx, but you can switch to another Sanctum of Rebirth boss by editing the `bossType` variable in `scripts/script.js`.
Currently the schedules for Vermyx, Kezalam and Nakatra are simplified and may not perfectly match in-game timings. There are also some features that are not enabled by default. These features can be enabled/disabled in the settings, which can be accessed by pressing the cog icon in the top right.
## Requirements
To function SusAlert needs the following:
- Alt1 toolkit must be installed, you can install that [here](https://runeapps.org/alt1).
- The bosstimer must be visible on-screen, this can be changed in Gameplay Settings > Interfaces > Information Windows > Boss kill timer.
- Interface scaling needs to be at 100% (this is the default).
- Game messages need to be turned on (plugin is tested with fontsize 12).
- It is recommended to turn timestamps on in the chat box to improve chatreader accuracy. This can be changed by ticking the box in Gameplay Settings > Chat & Social > Chat Customisation > Local timestamps in chat box.
- The recommended interface transparency is 0%, as a transparent chatbox may cause overlay detection issues.

## Installation
To install SusAlert copy & paste this link into your browser:<br/>
[alt1://addapp/https://raphire.github.io/SusAlert/appconfig.json](alt1://addapp/https://raphire.github.io/SusAlert/appconfig.json)

Or go to this URL in the alt1 browser:<br/>
https://raphire.github.io/SusAlert/

## Credits
Special thanks to [ZeroGwafa](https://github.com/ZeroGwafa) for his chat detection function, and [Skillbert](https://github.com/skillbert) for creating alt1 & his help with making the bosstimer detection.

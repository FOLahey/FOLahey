# Steam Deck
<img src="https://m.media-amazon.com/images/I/517iqqt5RdL._SL1500_.jpg">

## Accounts
- Steam
- RetroAchievements

## Hardware Upgrades
- USB-C Magnetic Adapter (Will reduce the amount of times you plug and unplug into the main console, prolonging its life)
- SD Card (Emudeck requires ext4 (or btrfs) formatting. You can format in Game Mode of Steam Deck)
- Internal NVMe
<img src="https://m.media-amazon.com/images/I/61oEjKjwi0L._AC_SL1500_.jpg">

## Software
Enter into Desktop Mode by holding power for a few seconds to make a menu appear or selecting in Steam Menu.
<img src="https://steamuserimages-a.akamaihd.net/ugc/1809895086190957419/8FE51D3F813D3E34AB59673DA833C1C1E48C852A/">

### EmuDeck
<img src="https://overkill.wtf/content/images/size/w1000/2022/11/emu1.webp">
EmuDeck is an emulator management suite for the Steam Deck (and other handheld emulators). You download ROMs from the Internet, add them to directories created by EmuDeck, then run a script from your desktop. EmuDeck creates Steam tiles and shortcuts to launch the games directly alongside the rest of your Steam library. EmuDeck leverages existing Open Source projects to bring this emulation to the Steam Deck. RetroAchievements is configurable to track your achievements in a number of old games from within the emulators included in EmuDeck, like RetroArch.
  - [EmuDeck Install Guide](https://www.emudeck.com/#how_to_install)
  - [EmuDeck Download](https://www.emudeck.com/EmuDeck.desktop)
  - SD Card must be ext4 from Game Mode format FIRST
  - Copy EmuDeck to desktop (required)
#### Add new games to EmuDeck
  - Copy ROMs into ./Emulation/roms/ directories
  - Click EmuDeck desktop icon
  - Click Preview, Parse, Save to Steam
  - Relaunch into Game Mode
<img src="https://i.ytimg.com/vi/65_Ppqx1sjg/maxresdefault.jpg">
#### Sourcing ROMs
You can Google the name of the game you are desiring to play with the word ROM. It should be pretty available. There is a text editor for Linux that starts with V. There is a website with a similar name that distributes ROMs. The legality of ROMs is gray. They are largely considered abandonware. The legal arguement used to be that you needed a physical copy of the game. Nobody is going around checking, but it is not legal to redistribute these ROMs. Only some versions of some ROMs are compatible with RetroAchievements. See note below. 
#### Playstation and other missing BIOS
The Emudeck does not ship with the BIOS required to be able to play Playstation 2 and 3 games. 
For PS2(pcsx2): You will need to source those BIOS, and then copy them directly to the Emulation/bios/ directory. Do not create a nested directory. You can get these by going to the same ROM site as above, going to emulators, and then clicking on the red text about PS2 bios under Playstation 2. Extract that zip file, and copy the three files to the bios directory directly. SCPH-70012.bin, SCPH-77008.bin, SCPH-90006.bin 

## Achievements
If you are interested in tracking your achievements for the old games you are playing, you can sign up for an account at RetroAchievements and then insert those credentials into RetroArch (after setting up EmuDeck). To unlock the achievement, you must be actively connected to the Internet.
-[RetroAchievements](https://retroachievements.org/) 
-[My Profile](https://retroachievements.org/user/Lahey)

<img src=https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjCLV8vMZGRB_ctudvGIYD95Mh-EL9QI4K0Y386t8GCeBCoDs2KCcOouF4nIhHJ2j5okUfnTW9tluFRg3XXNi7oRElf-5CFKNAi7CKrmWk0adSSvaHe62F99S0WC12JxQBbxIbuimED1NtbLTvmLGQ7XJJzefLjc56Ka9He7m_ZyDQV-1ne3so/s1273/retroach.png>

#### Achievement Compatibility
To check and see which ROM is supported on RetroAchievements, go to the game you are interested to play on RetroAchievements and scroll down 75% through the page till you see Supported Game Files. In there, it will have a version number and a hash. You should try to source that same version number. To ensure that you have the correct file after you download, you can compare the hash against the one on the website. The hash on RetroAchievements is the long string of characters under the name of the game file. 

On Windows, you can generate an MD5 hash for the file you downloaded
- Windows + r
- Type `cmd` without quotes then hit enter to open a Command Prompt
- Navigate to the same directory you downloaded the files. If you downloaded to Downloads, then `cd Downloads`.
- `certutil -hashfile <file> MD5`
- EX: `certutil -hashfile "Pokemon Red v1.0.gb" MD5`

#### Hardcore Achievements vs Softcore Achievements
RetroAchievements distinguishes between "hardcore" and "softcore" achievements. The hardcore achievements are achievements that are achieved during hardcore mode. Hardcore mode can be activated in the settings of RetroArch. Hardcore mode disables save states and cheats and other emulator hacks that could make it easier to achieve the achievement than on regular hardware. Softcore achievements are achievements that are unlocked while hardcore mode is not engaged. These mean that the use of emulator tricks could have aided in unlocking the achievement. Some games rely on save states to fullfill saving functionality in the game. These games you will have to beat in one sitting if you want to play in hardcore mode. Most hardcore mode games just set you back to the title screen everytime you play, softcore mode leaves you in the game where you last left off.

### Decky Loader
Decky Loader is a plugin manager for the Steam Deck. It offers an easy way to install plugins so you can customize your Steam Deck and the layout of the Steam OS. Its very useful for managing the tabs, creating collections, changing artwork, VPNs, etc. 
- Enter into Desktop Mode
- [Direct Download Link](https://github.com/SteamDeckHomebrew/decky-installer/releases/latest/download/decky_installer.desktop)
- Copy to Desktop and click icon
- Switch back to Game Mode and access Decky Loader via the 3 dot menu on the Steam Deck.
<img src="https://camo.githubusercontent.com/5615ccdc8ca2311738b49374c6a9d9bd4e598e84592a64423f530f670a00f342/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f3936363031373131323234343132353735362f313031323436363036333839333631303530362f6d61696e2e6a7067">

### Other Applications
#### Discord
- Enter Desktop Mode
- Launch Discover
- Download Discord
- Login to Discord
- Launch Steam from Desktop Mode
- Add a non-Steam game to my library and add Discord
- Return to Gaming Mode
<img src="https://static1.xdaimages.com/wordpress/wp-content/uploads/2022/10/Steam-Deck-Steam-OS-Discord-1.jpg?q=50&fit=crop&w=943&dpr=1.5">

#### Spotify
- Enter Desktop Mode
- Launch Discover
- Download Discord
- Login to Discord
- Launch Steam from Desktop Mode
- Add a non-Steam game to my library and add Discord
- Return to Gaming Mode
  
#### Media Player
Todo

#### Other Launchers
Todo

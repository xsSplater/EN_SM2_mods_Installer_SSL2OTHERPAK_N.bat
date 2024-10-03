# Warhammer 40,000: Space Marine 2

# Mods Installer for the Disable Intros
## version: 0.6

![Example](https://staticdelivery.nexusmods.com/mods/6771/images/headers/43_1726655413.jpg)

Download mod from: [Nexus](https://www.nexusmods.com/warhammer40000spacemarine2/mods/43)

---

### +++ WHAT THE BAT FILE DOES:

1. The batch file checks the registry for the address to the Game and WinRar.
2. Also checks for their presence in the folders before performing the installation.
3. Displays error screens and problem solution descriptions.
4. If it does not find the Game or WinRar, it offers to enter/paste the location address. In case the address was mistakenly considered from the registry or the game is NON-Steam.
5. Checks if there is a folder "SSL" next to the batch file, otherwise it is not executed, because there is no point.
6. Checks if there is a DEFAULT_OTHER.PAK archive in the target folder before copying.
7. Makes a backup of DEFAULT_OTHER.PAK to the BACKUP folder upon request.
8. Copies the "SSL" folder inside the DEFAULT_OTHER.PAK archive.

---

### +++INSTALLATION:

## Steam Version:

1. Unzip the archive wherever you want.
2. Run the file "EN_Disable_Intros_Installer_N.bat".
3. Follow the instructions of the X55-P1473-R Servitor.

## NON-Steam:

For the non-Steam version, you will need to enter the game address manually in the Installer window, since the script can only find the Steam version itself. (I only have one version of the game ;)

## Manual installation:

1. Go to: "..\SteamLibrary\steamapps\common\Space Marine 2\client_pc\root\paks\client\default\"
2. Open with WinRar (NOT 7zip): "default_other.pak"
3. Copy folder "SSL" to it.
4. Choose "Store" method!

---

# License

Code is under an MIT [license](LICENSE)

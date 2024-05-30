## Readme - Script for Managing Rocket League Videos

**Note**: This .exe is an add-on for BakkesMod's "Bakelite," which hasn't been updated for years. Bakelite must still be installed to use this script. [Here is the link to Bakelite](https://bakkesplugins.com/plugins/view/256). (Bakelite code wasn't used for this script)

After installing Bakelite, open Rocket League and navigate to Bakelite's plugin settings. Enable "Enable Recordings" and leave the rest of the settings unchecked.

Don't forget to activate highlights in NVIDIA GeForce Experience with ALT + Z.

This script is designed to streamline the management of Rocket League videos. It facilitates renaming, moving, and deleting videos from specific folders.

### Instructions for Use

1. **Interaction**:
   - Follow the prompts displayed during the script's execution.
   - Choose whether to mark, replay, move, or delete videos.

2. **Completion**:
   - Review the statistics at the end of the script to see which actions were performed.

### Setting Up Automatic Execution

To ensure the script runs automatically on every system startup, follow these steps:

1. **Open the Run window**:
   - Press Windows + R keys to open the Run window.

2. **Navigate to the startup folder**:
   - Type `shell:startup` into the Run window and press Enter. This will open the startup folder.

3. **Add a shortcut**:
   - Move the script's shortcut created on the desktop (`AutomaticMp4Drager`) to the opened startup folder.

4. **Restart the computer**:
   - Restart your computer to ensure the script runs automatically on every startup.

### Supported Video Players

The script utilizes a predefined list of video players to terminate running processes. Ensure this list is updated if necessary. The following video players are integrated into the script:

- **Video.UI.exe**
- **Microsoft.Media.Player.exe**
- **VLC Media Player**: `vlc.exe`
- **Windows Media Player**: `wmplayer.exe`
- **Media Player Classic**: `mpc-hc.exe`
- **PotPlayer**: `PotPlayerMini64.exe`
- **Kodi**: `kodi.exe`
- **Plex Media Player**: `PlexMediaPlayer.exe`
- **SMPlayer**: `smplayer.exe`
- **MPV**: `mpv.exe`
- **GOM Player**: `GOM.exe`
- **DivX Player**: `DivXPlayer.exe`

Please ensure this list is used according to your requirements to ensure all relevant video player processes are terminated before actions like moving or deleting files are executed. The script relies on this list to identify and stop running video player processes.

### Created Folders

Running this script creates the following folders:

- **RLTrashCan**: This folder is created on the desktop and serves as the trash can for Rocket League videos.
- **RLMoveTo**: This folder is created in the user's video folder and serves as a temporary storage for Rocket League videos before they are marked or deleted.
- **RocketLeagueClips**: This folder is created in the user's video folder and serves as the destination folder for marked Rocket League videos.

### Notes

- **Exercise caution when deleting files**:
  - Be careful when deleting files, as this action is irreversible.

### Uninstalling the Program

- **Uninstall**:
  - \Program Files\RLVideoManager\Uninstall.exe or Open Control Panel, Programs, Uninstall a program, RLVideoManager

- **Requirements**:
  - [BakeLite](https://bakkesplugins.com/plugins/view/256)
  - [Geforce Experience](https://www.nvidia.com/de-de/geforce/geforce-experience/)

### Potential Virus Detection

- **Unsigned Application**:
  - The .exe file may be detected as a virus because it is an unsigned application. Rest assured, this is a false positive.

### License

This script is provided under an MIT License.

### Authors

This script was created by [FuZeee](https://github.com/FuZeee).

### Version History

- Version 1.0: Initial release of the script.

### Support

For issues or questions, please contact via [GitHub Link](https://github.com/FuZeee/RLVideoManager/issues).

Thank you for using this script!

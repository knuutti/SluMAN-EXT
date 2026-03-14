# SluMAN
Speedrun tool for Sly Cooper games, on console and emulator, based on [racman](https://github.com/MichaelRelaxen/racman)

### [DOWNLOAD HERE](https://github.com/knuutti/SluMAN-EXT/releases/latest/download/SluMAN.zip)

# Supported games:
- Sly 2: Band of Thieves (KOR) - NPHA80175
- Sly 3: Honor Among Thieves (PAL) - NPEA00343
## Setup
To use SluMAN, follow these steps:
## PS3 Setup
First, make sure you have `webMAN MOD` installed on a jailbroken PS3 using either a console with custom firmware or a HEN-enabled console. It's important that you have the full version of webMAN MOD, which can be done by holding L1 while running the installer.

Make sure your PC and PS3 are connected to the same network. Then, to connect `SluMAN` to your PS3, you need to IP address from your PS3. This can be done by going into Settings > System Settings > System Information on your console.

Input the IP address and insert it into the `SluMAN.exe` application on your PC. Then all you need to do is run a game, and click the `Attach` button.

**Make sure to close `SluMAN` before closing your game!**

## RPCS3 Setup
Just run `SluMAN.exe`, then while your game is open in RPCS3, click the `RPCS3` button.

*Before the first use on RPCS3 you need to enable IPC server in RPCS3. Click "Configuration" > "IPC" and check the box that says "Enable IPC Server". Make sure the IPC server port is 28012 (supporting other port numbers is coming in the future). Click "Save".*

## Building
1. Use Visual Studio 2022
2. Clone the GitHub repository
3. Click Build > Build Solution

## Credits & Acknowledgments
- [racman](https://github.com/MichaelRelaxen/racman) contributors
- [webMAN MOD](https://github.com/aldostools/webMAN-MOD) contributors
- [bordplate](https://github.com/bordplate), for the [Ratchetron](https://github.com/bordplate/Ratchetron) API

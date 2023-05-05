
<center><img src="./image/demo-xfce.png"></center>
<p align="center"><b>Easily Install Full Kali Linux Verious Type Of Desktop in Termux</b></p>

<div align="center">

[![GitHub stars](https://img.shields.io/github/stars/sabamdarif/modded-kali)](https://github.com/sabamdarif/modded-kali/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/sabamdarif/modded-kali)](https://github.com/sabamdarif/modded-kali/issues)
[![GitHub license](https://img.shields.io/github/license/sabamdarif/modded-kali)](https://github.com/sabamdarif/modded-kali/blob/main/LICENSE)

</div>

### Features:

- :speaker: Fixed Audio Output
- :globe_with_meridians: 2 Browsers (Chromium & Mozilla Firefox)
- :tv: VLC Media Player and MPV media player (VLC Fully work)
- :books: Easy for Beginners
- :computer: Add new Application Menu
- :hammer: Install XFCE, LXDE, LXQT, KDE, or GNOME Desktop
- :art: More customization (new styles added and new fonts etc...)

### Installation:

1. Firstly install [Termux](https://termux.com) apk from [HERE](https://f-droid.org/repo/com.termux_118.apk)
2. Secondly Clone the Repository & Run the setup File

   - `pkg update -y && pkg upgrade -y`
   - `pkg install git wget -y`
   - `git clone https://github.com/sabamdarif/modded-kali`
   - `cd modded-kali`
   - `bash setup.sh`
   - `kali`
   - `bash gui.sh`
   - Now select **KFCE**, **KDE**, **LXDE**, **LXQT** OR **GNOME** Desktop (any one)
3. **You have to note your VNC password !!**
4. **If you select xfce4 / default desktop environment then you need to run `./customize-my-desktop`**
5. KALI image is now successfully installed.

   - Type `vncstart` to run Vncserver
   - Type `vncstop` to stop Vncserver

6. Install VNC VIEWER Apk on your Device. [Google Play Store](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android&hl=en)
7. Or, Install NetHunter KeX from [Nethunter Store](https://store.nethunter.com/en/packages/com.offsec.nethunter.kex/)

8. Open VNC VIEWER & Click on + Button & Enter the Address `localhost:1` & Name anything you like
9. Set the Picture Quality to High for better Quality
10. Click on Connect & Input the Password
11. Enjoy :smile:

### NOTE:

- **Type `kali` to run KALI CLI.**
- **Type `vncstart` to run Vncserver**
- **Type `vncstop` to stop Vncserver**
- **Type `fixvnc` if the vnc server not started (for Android 12 users)**
- **Type `bash remove.sh` to remove KALI**

### ISSUES:
- **Issue:-** Android 12 users have a problem of vncserver automatically stop and and show " [Process completed (signal 9) - press Enter] " &  the next time vncserver not starting

- **Solution:-** *use command `fixvnc` and the server started again*

### If you like our work then dont forget to give a Star :)


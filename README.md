# NitroShell
A reverse shell for easy shell management
**THIS WORK IS UNDER CC-BY-NC LICENSE. SEE LICENSE FOR DETAILS**
# Installation - WINDOWS
1. Download the executable to a select file
2. Copy the file directory
4. Go to edit system enviroment variables and then enviroment variables, system variables, then PATH.
5. Click add new.
6. Paste the copied path
7. Click ok until all windows are closed
8. Now you are ready to use it!
# Official Installer
You can download the GUI version with the required dependencies with the NitroShell_Setup.exe
1. Download the installer.
2. Select all components (Unless you have broken or outdated components).
3. There will be a folder called Nitroshell. Move into that folder.
4. Double-click NitroShell.exe, which will launch the GUI.
5. NOTE, antivirus apps may flag the app as it has a --noconsole flag for streamlined GUI. If possible, add it to a whitelist in your antivirus software.
# Usage - ns.exe
```cmd
ns -ip [IP ADDRESS] -p [PORT] -c [CONNECT TO LISTENER] -l [LISTEN FOR INCOMING CONNECTIONS] -f [LISTEN FOREVER]
```
**NOTE: THIS SERVER WILL TRY CONNECTING FOREVER UNLESS KEYBOARD INTERRUPT OR TERMINAL WINDOW CLOSED**
# USAGE - NitroShell.exe
NitroShell.exe is the GUI version of NitroShell. You must install the file NitroShell GUI as downloading it alone won't work since it depends on ns.exe.
Installing is the same, but keep in mind that antiviruses may flag it as malicious and delete the file. If this happens, add it to the antivirus's whitelist.
1. Enter IP in IP box. DDNS's may work, but hasn't been tested.
2. Enter a valid port number.
3. Click on either "Listen" or "Connect". Clicking one will open a shell window. Close to return to main GUI.
# DISCLAIMER
**If this software is used for malicious purposes, I am not responsible for any damage done to your computer with this. This is intended for remote administration and pentesting, not for malicious purposes.**

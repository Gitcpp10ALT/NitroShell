# NitroShell
A reverse shell for easy shell management
**THIS WORK IS UNDER CC-BY-NC LICENSE. SEE LICENSE FOR DETAILS**
# Installation - WINDOWS
1. Download the executable to a select file
2. Copy the file directory
3. Go to edit system enviroment variables and then enviroment variables, system variables, then PATH.
4. Click add new.
5. Paste the copied path
6. Click ok until all windows are closed
7. Now you are ready to use it!
# Usage - ns.exe
ns -ip [IP ADDRESS] -p [PORT] -c [CONNECT TO LISTENER] -l [LISTEN FOR INCOMING CONNECTIONS]
**NOTE: UNLIKE ns-server (see below), THIS WILL ONLY TRY CONNECTING ONCE**
# Usage - ns-server.exe
ns-server -ip [IP ADDRESS] -p [PORT]
**NOTE: THIS SERVER WILL TRY CONNECTING FOREVER UNLESS KEYBOARD INTERRUPT OR TERMINAL WINDOW CLOSED**

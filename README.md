# Manage-Vanguard
A simple batch script to manage RIOT Vanguard startup settings.
Inspired by this Gist: https://gist.github.com/AndrewMast/742ac7e07c37096017e907b0fd8ec7bb

### Features:
* Can modify the default startup setting of Vanguard services (vgc and vgk). Both enabling and disabling them.
* Can disable Vanguard for the current session. (same feature avaiable with the "Exit Vanguard" opion in Vanguard Tray.

### How To:
* Just download mng-vngrd.bat file from this repository and run it.
* It does not take any cli arguments, all inputs are taken directly from user during execution.

##### Vanguard Tray Icon:
Please note that this script doesn't disable "vgtray.exe" autostart. If you don't want to see it popping up on your task bar disable it manually in Windows autostart settings. It should be listed as either "vgtray.exe" or "Vanguard Tray Notification.". You can freely disable it since Vanguard relise on services to work and this porcess is only for you to get notifications from Vanguard and to be able to close Vanguard completely for the current session. You donn't need it since my script does the same thing and also has opcion to completly enable/disable Vanguard services loading on startup.

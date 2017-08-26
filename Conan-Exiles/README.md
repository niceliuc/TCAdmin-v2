## Install Windows Server

```
This configuration file is a bit tricky to get working due to file permissions but i will explain the best i can.
```

1. Download the latest release of this repo
2. Upload the XML via "Games & Other Voice Servers" - "Import"
3. Go to > Settings > Game Tools > "Steam Game Downloader" and Download the Server Files
4. Create "Mod" folder in "ConanSandbox" Directory
5. Create "modlist.txt" text file in your new "Mod" folder
6. In root Folder run "StartServer.bat" and leave it for a few mins then click on the main windows and push CTRL+C to shut down. 
(This will generate the files needed)
7. Go to > ConanSandbox > Saved > Config > WindowsServer and change the permissions on the files listed in step (9)
8. Right Click & Properties then check the "Read-only" check box on these files. "ServerSettings.ini" , "Game.ini" , "Engine.ini"
9. You can now create your first service!


## Install Linux Server

```
Coming Soon!
```

## Features

1. 119 Custom Variables!
2. Steam API Support
3. Save CTRL+C Script on Server Shutdown


## Configuration Files

* ConanSandbox\Saved\Config\WindowsServer\Game.ini
* ConanSandbox\Saved\Config\WindowsServer\Engine.ini
* ConanSandbox\Saved\Config\WindowsServer\ServerSettings.ini

* Raw File Settings "Game.ini" [Game.ini] (https://github.com/MrBrit-TCAdmin-Game-Configs/TCAdmin-v2/blob/master/Conan-Exiles-Windows/WindowsServer/Game.ini)
* Raw File Settings "Engine.ini" [Engine.ini] (https://github.com/MrBrit-TCAdmin-Game-Configs/TCAdmin-v2/blob/master/Conan-Exiles-Windows/WindowsServer/Engine.ini)
* Raw File Settings "ServerSettings.ini" [ServerSettings.ini] (https://github.com/MrBrit-TCAdmin-Game-Configs/TCAdmin-v2/blob/master/Conan-Exiles-Windows/WindowsServer/ServerSettings.ini)


## Log Files

* Location: ConanSandbox\Saved\Logs\ConanSandbox.log


## Configuration Editor

* Supported with 150+ Options!


## Included Batch Files (for use with or without TCAdmin)

* Launch Parameters (Commandline) BAT file
* SteamCMD Download Script BAT file


## Changelog

This is for your current installed xml file to save you deleting and importing my changes


## Known Issues

1. Missing Configuration Editor Settings for file "ServerSettings.ini" (I will add this soon)


## Planned Features

1. Steam Workshop Mod Support

Everything else has been done for you.
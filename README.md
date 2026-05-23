BBCR Mod Manager
=================

BBCR Mod Manager is a simple desktop tool for managing mods in Baldi’s Basics Classic Remastered. It helps you install, remove, and organize mods easily without manually moving files or editing game folders.

----------------------------------------
FEATURES
----------------------------------------
- Automatically detects BBCR game folder
- Installs and manages BepInEx setup
- One-click ZIP mod installation
- Remove mods easily
- View installed mods list
- Launch the game directly from the app
- Keeps mod files organized in BepInEx/plugins
- Simple and clean interface

----------------------------------------
REQUIREMENTS
----------------------------------------
- Windows PC
- Baldi’s Basics Classic Remastered (Steam/Epic version)
- Internet connection (for first-time BepInEx setup)
- Python 3.10+ (if running source code version)

Python packages (if running source):
- customtkinter
- tkinter (built-in)

Install dependencies:
pip install customtkinter

----------------------------------------
HOW TO USE
----------------------------------------
1. Launch BBCR Mod Manager
2. Select your Baldi’s Basics game folder (or let it auto-detect)
3. If BepInEx is not installed, the app will set it up automatically
4. Click "Install ZIP Mod" to add mods
5. Click "Launch Game" to start playing

----------------------------------------
MOD STRUCTURE
----------------------------------------
Mods are installed into:
BepInEx/plugins/

Each mod should contain:
- .dll file (main mod file)
- optional config folders or assets

----------------------------------------
IMPORTANT NOTES
----------------------------------------
- Only use trusted mods from safe sources
- Some mods may not be compatible with each other
- Game updates may break certain mods
- Always back up your game folder before installing large mod packs

----------------------------------------
DISCLAIMER
----------------------------------------
This tool is not affiliated with or endorsed by the developers of Baldi’s Basics.
All game assets belong to their respective owners.

----------------------------------------
CREDITS
----------------------------------------
Created for easier mod management in BBCR
Uses BepInEx

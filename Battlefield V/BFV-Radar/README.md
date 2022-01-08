# Tormund-BFV-Radar
External Radar Mod for Battlefield V using Python and PyGame

# Installation
  - Install Python 3.6.8 64-bit
  - Make sure its added to your path
  - go into your clone directory in commandline
  - pip.exe install -r requirements.txt (to install PyGame)
  - Run BFV.exe
  - python.exe .\Radar.py 1920 1200

## Features:
  - Radar follows your local player perspective
  - Not internal to BFV so game cannot take screenshots
  - Tracks all enemy locations
  - Tracks all vehicle locations
  - Colors vehicles based on team id
  - Vehicle specific icons
  - Tracks spawn beacons
  - Tracks Stationary Weapons
  - Tracks Ammo and Health supply stations
  - Tracks Grenade Entities
  - Tracks Explosion Packs
  - Renders Level Borders and Team specific Borders
  
  ## Firestorm Features:
  - Draws map borders
  - Draws inner circle
  - Draws outer circle
  - Draws LootEntities (as they pop up in memory)
  - White period = Tier 1 Loot
  - Green asterisk = Tier 2 Loot
  - Blinking Red/Green asterisk or hash = Tier 3 Loot
  
  ## Updates / Patches / AntiCheat
  As of April 2019 this is known to work. Unknown if DICE anticheat has ways to detect (most likely). Offsets found using generic sigs, hopefully as game updates the sigs find correct offsets
  
  ## Demos:
  
  ![Alt text](/demo/operations.png?raw=true "Operations")
  ![Alt text](/demo/firestorm.png?raw=true "Firestorm during airdrop")
  ![Alt text](/demo/firestorm2.png?raw=true "Firestorm on the ground")
  
  Shoutouts: Speedi13, txt, shellBullet, huangfengye, RozenMaiden, USSR, JD62, Coltonon, Robm

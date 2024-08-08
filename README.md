This is a BepInEx plugin for TABG dedicated servers  
To use it download the .dll and .exe files from the latest release  
Put the .dll file in your BepInEx plugins folder  
Put the .exe file in your TABG server main folder  
Boot the server until you see a heartbeat  
Shut down the server  
Run the Setup.exe, make any changes you want and remember to save on each page  
  
**Configurable Options**  
- Ring Locations
- Ring Sizes
- !!IMPORTANT!! Ring Speeds still need to be set in the game_settings.txt. I'm working on it.
- If you go down while on a team (If disabled you'll just die instantly without the chance to be revived)
- If you can respawn after being locked out (Enabled: Default / Disabled: Respawn)
- If you will be killed out of the trucks (Forces players into a zone early)
- If items will drop when a player is killed (Helps reduce lag from ground loot and keeps loadouts balanced. I would reccomend leaving this disabled)
- Which items are given to a player when they get a kill (Ammo and Meds can be given when you get a kill to give sustainability)
- Loadouts that can be given on respawn (These are given on respawn and can be created and managed in the setup file)
- Lobby Timer (Default is 15 minutes, I wouldn't set it too high as the servers get unstable)
- Lobby Spawn Points (These let you configure where you want palyers to spawn in the lobby. All the vanilla locations are toggable as well as a custom location you can choose)
- Vote To Start (/votestart. The options let you change minimum number of players needed, percent of votes needed, and how long the starting countdown will be once it finishes)
- Match Timer (This is how long the match will last if not ended by other means. The winner should get a Win screen but that's a bit buggy. Default is 15 minutes but it's the same as the lobby timer, dont set it too high)
- Win Conditions:
-   Default: The match will only end after the timer runs out or not enough teams are in the match to continue. Winner is whoever has the most kills.
-   Kills To Win: The match will end after a player reaches the required number of kills OR the timer runs out. Winner is whoever reached the requirement or has the most kills after the timer.
-   Debug: This is here for other mod developers. The match will not end (other than the timer) regardless of how many players are in the match. Very useful for testing, not so much for playing
- Heal On Kill (If enabled, when a player gets a kill they will be healed X% of their max hp.)
- Spelldrops AKA Blessing Drops AKA Air Drops (Can be toggled on and off and the time between drops and the offset from the start of the game can be configured)

**In Development**
- Ring Speeds (In the plugin setup and out of the game_settings.txt)
- Custom loot from Air Drops
- Out Of Combat Healing (This was previously bugged and needs to be fixed)
- Basic admin commands (/start, /kick, /give etc.)

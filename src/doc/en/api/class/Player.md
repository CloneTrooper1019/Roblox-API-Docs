# Members

## CameraMode
An enum that describes how a Player's camera is allowed to behave. <a href='http://wiki.roblox.com/index.php/CameraMode' target='_blank'>More info</a>.

## DataReady
Read-only. If true, this Player's persistent data can be loaded, false otherwise. <a href='http://wiki.roblox.com/index.php/ROBLOX_Scripting_How_To:_Data_Persistence' target='_blank'>Info on Data Persistence</a>.

## Idled
Fired periodically after the user has been AFK for a while.  Currently this event is only fired for the *local* Player.  "time" is the time in seconds that the user has been idle.

## LoadCharacter
Loads in a new character for this player.  This will replace the player's current character, if they have one. This should be used in conjunction with Players.CharacterAutoLoads to control spawning of characters. This function only works from a server-side script (NOT a LocalScript).

## playerFromCharacter
Use GetPlayerFromCharacter() instead

## WaitForDataReady
Yields until the persistent data for this Player is ready to be loaded. <a href='http://wiki.roblox.com/index.php/ROBLOX_Scripting_How_To:_Data_Persistence' target='_blank'>Info on Data Persistence</a>.
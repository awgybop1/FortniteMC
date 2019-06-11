# Fortnite MC Remake
This a Fortnite-like Battle Royale gamemode built in Skript for Spigot/Bukkit Servers.

Required Plugins:
Skript
ActionBar (for timers in ActionBar)
Multiverse (for the worlds)
MotdChanger (for Changing the MOTD depending on game state)

Setup:

You need 3 worlds.

One for your lobby (used the normal "world" for this in the script)
One for your players to actually play on and use (used the name "Map" for this in the script)
One for your Map in its normal state (used the name "Map_Normal" for this in the script)


You will need to set 2 spawn points, one for your Lobby and another for your Map.
The one for your Lobby can be anywhere you like, as long as its not in the 'Map' world.
The one for your Map needs to be in the air to work properly, so players can freefall and glide to their destination.
Use the command "/setspawn lobby" and "/setspawn map" to set your spawn points.
Set the center of the map for the storm using "/worldborder center <x> <z>", or you can put it anywhere you want the storm to close in.
  
  
Once all setup, players can join and start playing.
By default only a minimum of 2 players are required to start the game.
Once the game starts, players will spawn at the Map spawn point and be able to glide to where they wish.
After they have killed each other and only 1 player remains, the player will win the game and shortly be taken kicked off the server while the Griefed Player's Map is deleted and is cloned with the Normal Map.

Some Features of the game are:
Spectator system on death, spectators can still watch the game without being seen as Alive.
Map resetting system.
Working World Border/Storm system, with working timers/warnings for the storm.

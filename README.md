# Titanfall 2 Retry Deny Mod
Titanfall 2 mod for denying kills in vanilla multiplayer matches.

type `rd_enabled 1` in console to enable the mod

type `rd_health_frac VALUE` in console to change the value of the health threshold (should be a value between 1.0 and 0.0, keep in mind 0.51 works best and denies kills to most weapons)

Hello, I have not wrote a readme in a long time. 

Basically this mod reconnects you to any match when you get below a set HP value. Your score will be reset on the scoreboard, however your score towards winning will remain. It will not reconnect you if you reach an HP value at or below 0.0, and it will not reconnect you if you are in a titan. (Although maybe I should've added a feature to auto reconnect you when you get titan executed since that denies titan kills, lol)
This means if you have 100 points when you get reconnected, those 100 points will remain in the match and towards your teams score. However, it will be removed from your name on the scoreboard.

BIG NOTE : YES, THIS TAKES AWAY KILL CREDIT FROM ENEMY PLAYERS. THE DEFAULT VALUE FOR `rd_health_frac` (the convar that determines what the hp threashold is) IS WHAT I CONSIDER TO BE THE MOST EFFICIENT VALUE FOR THIS MOD. YOU CAN CHANGE IT IF YOU WANT.

## Convars and their purposes

- `rd_enabled` whether the mod is enabled or not. This convar is set to 0 by default (off)

- `rd_health_frac` what HP threshold to use (if your HP goes below this value, you will be disconnected)

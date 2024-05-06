# Titanfall 2 Retry Deny Mod
Titanfall 2 mod for denying kills in vanilla multiplayer matches.

Hello, I have not wrote a readme in a long time. 

Basically this mod reconnects you to any match when you get below a set HP value. Your score will be reset on the scoreboard, however your score towards winning will remain. 
This means if you have 100 points when you get reconnected, those 100 points will remain in the match and towards your teams score. However, it will be removed from your name on the scoreboard.

Currently, the version I am posting on GitHub is the version from my laptop, which is outdated. I am not home as of uploading this, so I cannot upload the most recent version.

The most current version of this mod doesn't reconnect you if you die, which is very useful as it makes the mod reconnect you only when it would be helpful. Also one thing to note : This version is glitchy in titans. 

BIG NOTE : YES, THIS TAKES AWAY KILL CREDIT FROM ENEMY PLAYERS. THE DEFAULT VALUE FOR `rd_health_frac` (the convar that determines what the hp threashold is) IS WHAT I CONSIDER TO BE THE MOST EFFICIENT VALUE FOR THIS MOD. YOU CAN CHANGE IT IF YOU WANT THOUGH. 

## Convars and their purposes

- `rd_enabled` whether the mod is enabled or not. This convar is set to 0 by default (off)

- `rd_health_frac` what HP threshold to use (if your HP goes below this value, you will be disconnected)

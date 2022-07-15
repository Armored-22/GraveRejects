# GraveRejects
Up-to-date server &amp; mod file settings
<br>
<br>
*Just want to clarify the first 8 settings in "ServerGameSettings.json" as the server host assigns a number with their config editor.*
```
  "GameModeType": "1",
  "1" = "PvP"
  
  "CastleDamageMode": "2",
  "2" = "TimeRestricted"
  
  "SiegeWeaponHealth": "2",
  "2" = "Normal"
  
  "PlayerDamageMode": "0",
  "0" = Always 
  
  "CastleHeartDamageMode": "0",
   "0" = "CanBeDestroyedOnlyWhenDecaying"
   
  "PvPProtectionMode": "3",
  "3" = "Medium"
  
  "DeathContainerPermission": "0",
  "0" = "Anyone"
  
  "RelicSpawnType": "1",
  "1" = "Plentiful"
  ```
<br>

**Change Log;**


# Update 1.1.0


**Castle Blood Drain**<br>
The rate in which your castle drains its blood has been increased from 0.5 to 1.5<br>
*This was far too low with the current stack size limits.*<br>

**Mastery Decay**<br>
Decay rate when offline will be slightly lower.<br>
Changed from 0.001% per 1 minute to 0.001% per 2.5 minutes.<br>

Example;<br>
For every 1 hour offline, you will lose 0.024% in all masteries<br>
*Changed from 0.060%*<br>
For every 24 hours offline, you will lose 0.576% in all masteries<br>
*Changed from 1.44%*<br>

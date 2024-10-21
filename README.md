# RestartRedirect
RestartRedirect teleports players from one server to another using the new feature from 1.20.5 (https://minecraft.wiki/w/Commands/transfer).
Something like MoveMeNow but without needing Velocity/Bungeecord


# Required
- Minecraft client 1.20.5+
- Minecraft server 1.20.5+
  
## Supported server software 
- Spigot (untested but should work), Paper, Purpur, Paper fork
- Fabric, Forge, NeoForge (Planned)
- Bungeecord/Velocity (Planned)
- Ignite (Maybe in the future)
 
# Limitations
- RestartRedirect sends the players to the configured server when a server shutdown is detected
- When the server crashes without executing the shutdown and saving, it will cause players not to be sent
- RestartRedirect does not check if the destination server is online/offline as a proxy server and it depends on the player's game what happens when they change server
- Players with a lower version, e.g. 1.20.4, cannot connect to another server due to a missing feature
  
# Installation
1) Download the plugin from the official source (link in future)
2) Put it in the plugins/mods folder
3) Restart the server or load the plugin via another plugin e.g. plugman,
4) Set config and type /RestartRedirect reload
5) Test via /RestartRedirect test or via /stop (server shutdown)

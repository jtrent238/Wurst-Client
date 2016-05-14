> This is an auto-generated error report for the [Wurst Client](https://www.wurst-client.tk).

# Description
An error occurred while processing events.
Event type: UpdateEvent

# Stacktrace
```
java.lang.NullPointerException
	at tk.wurst_client.utils.BuildUtils.advancedInstantBuild(BuildUtils.java:700)
	at tk.wurst_client.mods.InstantBunkerMod.onUpdate(InstantBunkerMod.java:305)
	at tk.wurst_client.events.EventManager.fireUpdate(EventManager.java:123)
	at tk.wurst_client.events.EventManager.fireEvent(EventManager.java:35)
	at net.minecraft.client.entity.EntityPlayerSP.onUpdate(EntityPlayerSP.java:200)
	at net.minecraft.world.World.updateEntityWithOptionalForce(World.java:1945)
	at net.minecraft.world.World.updateEntity(World.java:1914)
	at net.minecraft.world.World.updateEntities(World.java:1764)
	at net.minecraft.client.Minecraft.runTick(Minecraft.java:1864)
	at net.minecraft.client.Minecraft.runGameLoop(Minecraft.java:1095)
	at net.minecraft.client.Minecraft.run(Minecraft.java:396)
	at net.minecraft.client.main.Main.main(Main.java:115)

```

# System details
- OS: Windows 7 (x86)
- Java version: 1.8.0_45 (Oracle Corporation)
- Wurst version: 3.1 (latest: 3.1)
- Timestamp: 2016.05.14-06:36:11

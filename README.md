# LAVA_CAULDRON is not Levelled

## `org.bukkit.Material`

```java
    /**
     * BlockData: {@link Levelled}
     */
    LAVA_CAULDRON(4514, Levelled.class),
```

## Version

```
[06:44:08] [Server thread/INFO]: This server is running CraftBukkit version 3208-Spigot-18c71bf-97f629b (MC: 1.17.1) (Implementing API version 1.17.1-R0.1-SNAPSHOT)
```

## Error Log

```
[06:39:48] [Server thread/ERROR]: Could not pass event PlayerInteractEvent to LavaCauldronIsNotLevelled v1.0.0
org.bukkit.event.EventException: null
        at org.bukkit.plugin.java.JavaPluginLoader$1.execute(JavaPluginLoader.java:310) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at org.bukkit.plugin.RegisteredListener.callEvent(RegisteredListener.java:70) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at org.bukkit.plugin.SimplePluginManager.fireEvent(SimplePluginManager.java:589) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at org.bukkit.plugin.SimplePluginManager.callEvent(SimplePluginManager.java:576) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at org.bukkit.craftbukkit.v1_17_R1.event.CraftEventFactory.callPlayerInteractEvent(CraftEventFactory.java:499) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.server.level.PlayerInteractManager.a(PlayerInteractManager.java:485) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.server.network.PlayerConnection.a(PlayerConnection.java:1527) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.network.protocol.game.PacketPlayInUseItem.a(PacketPlayInUseItem.java:33) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.network.protocol.game.PacketPlayInUseItem.a(PacketPlayInUseItem.java:1) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.network.protocol.PlayerConnectionUtils.lambda$0(PlayerConnectionUtils.java:30) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.server.TickTask.run(SourceFile:18) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.util.thread.IAsyncTaskHandler.executeTask(SourceFile:151) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.util.thread.IAsyncTaskHandlerReentrant.executeTask(SourceFile:23) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.util.thread.IAsyncTaskHandler.executeNext(SourceFile:125) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.server.MinecraftServer.bf(MinecraftServer.java:1133) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.server.MinecraftServer.executeNext(MinecraftServer.java:1126) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.util.thread.IAsyncTaskHandler.awaitTasks(SourceFile:134) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.server.MinecraftServer.sleepForTick(MinecraftServer.java:1110) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.server.MinecraftServer.x(MinecraftServer.java:1039) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at net.minecraft.server.MinecraftServer.lambda$0(MinecraftServer.java:303) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        at java.lang.Thread.run(Thread.java:831) [?:?]
Caused by: java.lang.ClassCastException: class org.bukkit.craftbukkit.v1_17_R1.block.data.CraftBlockData cannot be cast to class org.bukkit.block.data.Levelled (org.bukkit.craftbukkit.v1_17_R1.block.data.CraftBlockData and org.bukkit.block.data.Levelled are in unnamed module of loader 'app')
        at dev.s7a.Main.on(Main.java:27) ~[?:?]
        at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?]
        at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:78) ~[?:?]
        at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?]
        at java.lang.reflect.Method.invoke(Method.java:567) ~[?:?]
        at org.bukkit.plugin.java.JavaPluginLoader$1.execute(JavaPluginLoader.java:306) ~[spigot-1.17.1.jar:3208-Spigot-18c71bf-97f629b]
        ... 20 more
```

# UltimateScoreboards

Official repository of UltimateScoreboards plugin. Get it on spigot <https://www.spigotmc.org/>.

For the **official wiki** visit <https://github.com/frengor/UltimateScoreboards/wiki>.

UltimateScoreboards is a powerful and light plugin to manage scoreboards on your server.  
It comes with a ton of features which allows you to easily customize your scoreboards. The plugin was written with the aim to give the best user-experience.  

UltimateScoreboard is :
* **easy to use**: the plugin is pretty straightforward to use
* **flexible**: every other team-based plugin out there is supported (obviously, not scoreboard ones) 
* **powerful**: you can customize everything from the config
* **built-in antiflicker**: scoreboards will never flick
* **packet-based**: the plugin is packet-based, which means that 
* **the best one**: you can create scoreboards on 1.8-1.12 with ~70 characters per line with only 1-tick update delay (no other plugin that I'm aware of can do that)

The plugin is fully asynchronous, which means that it will not impact in any way on the server performance.

### Developer API

The code in this repository is not the source code of UltimateScoreboards, but the official API of the plugin.  
If you're a developer and you're intrested in it check out the [official Developer API Wiki](https://github.com/frengor/UltimateScoreboards/wiki/Developer-API).

**Javadocs:** <https://us-docs.frengor.com> ([alternative link](https://frengor.github.io/UltimateScoreboardsAPI/))  
**Maven:**
```xml
<repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
</repository>
```
```xml
<dependency>
    <groupId>com.github.frengor</groupId>
    <artifactId>UltimateScoreboards</artifactId>
    <version>1.0</version>
</dependency>
```
API-Jar download for manual dependency addition: <https://github.com/frengor/UltimateScoreboards/releases>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=250&section=header&text=Toby%20Hall&fontSize=80&fontAlignY=35&desc=Java%20Developer%20%7C%20Spigot%20Enthusiast&descAlignY=55&descAlign=50" alt="Header" />
</div>

<p align="center">
  <em>Passionate developer from the UK crafting backend systems and custom Minecraft plugins.</em>
</p>

<div align="center">
  <a href="https://github.com/tobyhalldev">
    <img src="https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=GitHub&logoColor=white" alt="GitHub Badge"/>
  </a>
  <a href="https://discord.com/">
    <img src="https://img.shields.io/badge/Discord-5865F2.svg?style=for-the-badge&logo=Discord&logoColor=white" alt="Discord Badge"/>
  </a>
</div>

<br>

### 💻 About Me
```java
package dev.tobyhall.core;

import org.bukkit.ChatColor;
import org.bukkit.event.EventHandler;
import org.bukkit.event.Listener;
import org.bukkit.event.player.AsyncPlayerChatEvent;
import org.bukkit.plugin.java.JavaPlugin;

public class TobyProfile extends JavaPlugin implements Listener {

    @Override
    public void onEnable() {
        getLogger().info("Initializing Developer: Toby Hall...");
        getLogger().info("► Languages: Java, Python");
        getLogger().info("► Specialty: Spigot/Paper Plugin Development ⚔️");
        getLogger().info("► Location: United Kingdom 🇬🇧");
        getLogger().info("► Fuel: Coffee ☕");
        
        getServer().getPluginManager().registerEvents(this, this);
        getLogger().info("Toby is now online and ready to code!");
    }
    
    @EventHandler
    public void onFeatureRequest(AsyncPlayerChatEvent event) {
        if (event.getMessage().toLowerCase().contains("can you add this feature")) {
            event.setCancelled(true);
            event.getPlayer().sendMessage(ChatColor.GOLD + "Added to the backlog! (It might never get done)");
        }
    }
}
```

<br>

### 🛠️ Tech Stack
<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=java,python,gradle,maven,mysql,git,github,idea,linux&theme=dark&perline=9" alt="Tech Stack"/>
  </a>
</div>

<br>

### 📊 GitHub Stats
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tobyhalldev&show_icons=true&theme=nord&hide_border=true&bg_color=0D1117" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=tobyhalldev&layout=compact&theme=nord&hide_border=true&bg_color=0D1117" height="150" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=tobyhalldev&theme=nord&hide_border=true&background=0D1117" />
</div>

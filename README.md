FluxWardrobe
A high-performance, GUI-based skin management plugin for modern Paper servers.

📖 Overview
FluxWardrobe is a modern solution for skin management. It provides players with a personal wardrobe, allowing them to save, manage, and switch between their favorite skins using an intuitive GUI. Built for stability and speed, it leverages Paper's API to ensure zero lag during skin application.

✨ Features
In-Game Wardrobe: Players can save multiple skins with custom names/notes in a GUI.

Smart URL Support: Automatically parses links from NameMC, NovaSkin, and direct texture URLs.

High Performance: Asynchronous API handling with zero TPS impact.

Persistent Storage: Skins are saved via PersistentDataContainer, surviving server restarts.

Modern Tech: Built on Java 21, optimized for Minecraft 1.21+.

Integrations: Native support for Vault and PlaceholderAPI.

🚀 Getting Started
Requirements: Paper/Purpur Server (1.21+), Java 21+.

Installation: Place the FluxWardrobe.jar into your plugins folder.

Usage: Start your server, open the GUI using /wardrobe, and paste your skin links directly into the chat!

🔗 Supported Links

NovaSkin: Short links, post links, and long URLs.

Direct: Direct PNG texture links and Minecraft texture hashes.

🛠 Commands & Permissions

* Command                         *Permission
  
- /wardrobe                       - fluxwardrobe.use                                
- /skin <link>                    - fluxwardrobe.set

# BatchCraft Launcher

A retro-style Minecraft launcher written entirely in **Batch script**, inspired by the classic Mojang launcher UI. Lightweight, portable, and packed with customization.

---

## Features

-  **Classic Styled UI** – Colored ANSI menus using Windows CMD
-  **Configurable Settings** – Username, RAM, fullscreen mode, mod support (`options.ini`)
-  **Microsoft Account Support** – OAuth login support (WIP)
-  **AppData Integration** – Stores jars and tools in `%APPDATA%\.batchcraft`
-  **Embedded aria2** – High-speed jar downloading


## Configuration (`options.ini`) (`PILOT, CAN CHANGE`)

```ini
[BatchCraft Settings]
default_version=1.21.1
username=Steve
ram=2G
fullscreen=true
Fabric=false

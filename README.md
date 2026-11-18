# Minecraft Server Builder

![Python](https://img.shields.io/badge/Python-3-3776AB?logo=python&logoColor=white)
![CLI](https://img.shields.io/badge/interface-CLI-black)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

**Create and launch your own Minecraft server in a few keystrokes — no prior knowledge needed.**

Minecraft Server Builder is an interactive command-line tool that downloads the server software you choose, sets the RAM and starts the server for you.

![Main menu](https://github.com/ludenelenterrador/MinecraftServerBuilder/assets/134003146/498c987a-faf4-4e0f-a92a-97d5847b2908)

## Features

- 🧱 **Multiple server types:** Paper, Spigot and Magma (Forge + plugins)
- 📦 **Wide version support:** from Minecraft **1.8.8 up to 1.20.1**
- ⬇️ **Automatic download** of the selected server `.jar`
- 🧠 **Custom RAM** allocation (1–64 GB)
- 🎨 Colored, menu-driven terminal interface

## Screenshots

| Choose software | Choose version |
| --- | --- |
| ![](https://github.com/ludenelenterrador/MinecraftServerBuilder/assets/134003146/1366b0b0-27c1-4a16-9d5d-03e74416f54d) | ![](https://github.com/ludenelenterrador/MinecraftServerBuilder/assets/134003146/a0e79086-3d21-4e37-98aa-8838e93513e9) |
| ![](https://github.com/ludenelenterrador/MinecraftServerBuilder/assets/134003146/fbc887e4-c982-4d48-81cf-e77f391f49e9) | ![](https://github.com/ludenelenterrador/MinecraftServerBuilder/assets/134003146/9ffb5477-2659-4a02-9cb7-888b7dce4398) |

## Requirements

- Python 3.8+
- [Java](https://adoptium.net/) installed and available in `PATH` (Java 17+ for Minecraft 1.18 and newer)

## Getting started

```bash
git clone https://github.com/ludenelenterrador/MinecraftServerBuilder.git
cd MinecraftServerBuilder
pip install colorama requests
python main.py
```

Follow the menu: pick the server software → the version → the amount of RAM, and the server starts.

## Tech stack

Python · Requests · Colorama · PaperMC API

## License

[MIT](https://opensource.org/licenses/MIT) © 2023 Luden

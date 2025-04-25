# HikaBrain
[![License: GPL 3.0](https://img.shields.io/badge/License-GPL%203.0-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

A recreation of the classic french Minecraft minigame HikaBrain! Made for Paper 1.20+ with Kotlin

- 🎥🔴 **[Watch the demo on YouTube!](https://youtu.be/Sg8f3zO9CNc)**

# Usage
WorldEdit is required to use this plugin

## In-Game commands
- `/arena list` to display the list of arenas
- `/arena join <ID>` to join an arena
- `/arena leave <ID>` to leave an arena

## Config
To create new arenas, simply add their position in the config.yml following this format:
```yml
arenas:
  0: # This is one arena
    type: 'HIKABRAIN-SOLO'
    paste-position:
      world: 'void'
      x: 100
      y: 60
      z: 100
      yaw: 0
      pitch: 0
  1: # this is another arena
    type: 'HIKABRAIN-SOLO'
    paste-position:
      world: 'void'
      x: 300
      y: 50
      z: 1000
      yaw: 0
      pitch: 0
  2: #...
```

# License
Distributed under the CC [GPL 3.0](LICENSE) license



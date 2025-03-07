# Sanctify

### Get rid of curses hidden inside the floors of the Temple

It's a reimagined minesweeper game designed for elementary OS.

Author: [Subhadeep Jasu](https://github.com/SubhadeepJasu) \<subhadeep107@proton.me\>

<img src="screenshots/screenshot.png" width="500">

<a href="https://elementary.io"><img alt="Static Badge" src="data/badges/made_for_elementary_os_badge.svg"></a>

## Installation
### For Users
On elementary OS? Click the button to get Sanctify on AppCenter:

[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/com.github.elliegames.sanctify-game)

### For Developers
You'll need the following dependencies to build:

- Godot 4.3.x
- Flatpak Builder
- io.elementary.Sdk 8

**Build from Godot Editor:**

```bash
cd sanctify-game
mkdir build
/path/to/godot --headless --verbose --export-release "Linux" "build/com.github.elliegames.sanctify-game"
sudo mv build/com.github.elliegames.sanctify-game /usr/bin/com.github.elliegames.sanctify-game
```

…and run the game with:
```bash
com.github.elliegames.sanctify
```

**Install as Flatpak**

```bash
cd sanctify-game
flatpak-builder build com.github.elliegames.sanctify-game.yml --user --install
```

…and run the game with:
```bash
flatpak run com.github.elliegames.sanctify-game
```

<br>
<sup><b>License</b>: GNU GPLv3</sup>
<br>
<sup>Certain sounds are CC0</sup>
<br>
<sup>Sanctify Game © Copyright 2024-2025 Subhadeep Jasu</sup>

# Gaming Tools & Extensions by N00DLE_1

This repository contains modding utilities and custom Vortex plugin support for PC games. Most tools here are designed to extend mod compatibility, improve deployment, or allow unsupported games to be managed in Nexus Mods' Vortex Mod Manager.

---

## 🎮 Featured: Vortex Extension – *LOTR: Return to Moria*

Adds unofficial Vortex support for *The Lord of the Rings: Return to Moria*.

### ✅ Features

- Detects Steam installation of *Return to Moria*
- Enables `.pak`-based mod deployment via symlink or copy
- Supports mod installation to `Content\Paks\~mods`
- Fully modular and self-contained plugin
- Includes game thumbnail for Vortex UI

---

## 📦 Installation

1. **Download** the latest `.zip` from the [Releases](https://github.com/N00DLE-1/Gaming/releases) tab  
2. Extract the contents to:  
   ```
   %APPDATA%\Vortex\plugins\
   ```
3. Launch or restart **Vortex**  
4. Go to the **Games** section and enable *LOTR: Return to Moria*

---

## 🗃️ File Structure

```plaintext
vortex-return-to-moria/
├── index.js
├── game.js
├── manifest.json
├── info.json
└── gameart.jpg
```

---

## 🧪 Compatibility Notes

- Designed for Steam version of the game (App ID: 1853550)
- Tested on Vortex **v1.13.7+**
- Requires mods to use Unreal Engine .pak format
- Symlink deployment recommended for larger mods

---

## 🛠️ Contributing

Feel free to:  
- Open issues for bugs, UI errors, or mod conflicts  
- Fork the repo and submit a pull request  
- Share this plugin with others who want to mod *Return to Moria*

---

## 📜 License  
This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.
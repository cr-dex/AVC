# AVC

**Package Manager for Termux**  
The better alternative to deb • Built to improve

---

### Developers
**VIRUS & CR_DEX**

---

### Function & Overview
Modern package manager built specifically for Termux.  
Faster, cleaner and more secure alternative to the traditional deb system.  
Includes an isolated interactive environment called **AVCUI**.

---

### Commands

| Command | Description |
|---------|-------------|
| `init <name>` | Create new project |
| `build <folder>` | Build project into `.avc` |
| `install <file.avc>` | Install local package |
| `uninstall <name>` | Remove installed package |
| `list` | Show installed packages |
| `zip2avc <file.zip>` | Convert zipapp to `.avc` |
| `hub` / `search` | Browse packages on the hub |
| `get <name>` | Download & install from hub |
| `version` | Show AVC version |
| `help` | Show help |

### AVCUI Shell

| Command | Description |
|---------|-------------|
| `cd` / `pwd` / `ls` / `ll` | Navigation & listing |
| `clear` / `cl` / `c` | Clear screen |
| `ch` | `chmod +x` all files in current dir |
| `exit` / `quit` | Leave AVCUI |

---

**Shared folder:** `~/AVCUI` (bridge between Termux and AVCUI)

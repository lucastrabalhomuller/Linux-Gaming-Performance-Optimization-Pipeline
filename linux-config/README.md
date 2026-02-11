# Linux Configuration Files

This directory documents configuration files that are manually created
and used on a Linux system.

# GameMode Configuration File

The file `gamemode.ini` stored in this directory represents the real
configuration file used by GameMode on the Linux system, located at:

```bash
~/.config/gamemode.ini
```

# Using GameMode and MangoHud with Steam

This project relies on GameMode to apply the system configuration defined
in `~/.config/gamemode.ini`.

# Enabling GameMode in Steam

To enable GameMode for a game in Steam:

1. Open Steam
2. Right-click the game and select **Properties**
3. In **Launch Options**, add:

```bash
gamemoderun %command%
```

Or, if you prefer, use MangoHud.

```bash
gamemoderun mangohud %command%
```

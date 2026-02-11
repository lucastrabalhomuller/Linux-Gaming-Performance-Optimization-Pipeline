# System Configuration

This document describes the system-level configuration used to integrate
GameMode with Linux power management.

## GameMode Configuration

The following configuration was applied to the GameMode configuration file
(`~/.config/gamemode.ini`) to dynamically control CPU power profiles.

### Custom Start and End Hooks

When a GameMode session starts, the system switches the CPU power profile
to performance mode to reduce frequency scaling latency:

```ini
start=/usr/bin/powerprofilesctl set performance

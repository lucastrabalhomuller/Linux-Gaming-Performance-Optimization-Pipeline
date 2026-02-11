# Scripts

This directory contains system-level scripts used to support the performance
optimization workflow described in this project.

The scripts provided here focus on automating system configuration changes
that are relevant for latency-sensitive graphical workloads.

## Available Scripts

### gamemode-power-profile.sh

This script switches the CPU power profile to `performance` mode using
`powerprofilesctl`. It is intended to be executed at the start of a gaming
session, either manually or via GameMode hooks.

**Purpose:**
- Reduce CPU frequency scaling latency
- Improve frame time stability during gaming

## Usage Notes

- Scripts in this directory may require appropriate system permissions.
- Users should review and adapt scripts according to their hardware
  and distribution-specific configurations.

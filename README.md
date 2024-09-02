# Gas Trap Performance Fix

## Overview
Fixes the script lag occurring in cells with numerous gas traps.

### How It Works
Switches the "OnHitWith" block of the gas trap scripts to use NVSE event handlers.

### Performance Benchmarks[^1]
- Vault22e - 30 FPS -> 144 FPS (100+ Traps)
- zWastelandSewer01 - 40 FPS -> 144 FPS (60+ Traps)
- RooseveltHS02 - 40 FPS -> 144 FPS (50+ Traps)
- FriendshipMetroUtility - 50 FPS -> 144 FPS (30+ Traps)

## Requirements
- Dead Money
- [xNVSE](https://www.nexusmods.com/newvegas/mods/67883)

## Installation
Install with a mod manager via the FOMOD installer.

[^1]: The performance impact of gas traps varies based on the ExplodesGasTrapsOnHit FormList.
# betaflight-configs

Personal Betaflight CLI dumps and setup notes for my drones.

## Files
- `air cli dump 65.txt` - full CLI dump for Air65, BF 4.5.0 (STM32G47X)
- `air sideways cli dump 65.txt` - full CLI dump for Air65 sideways, BF 4.5.0 (STM32G47X)
- `m75 dump.txt` - full CLI dump for M75, BF 4.5.0 (STM32G47X)
- `racer velox.txt` - CLI dump for Velox racer, BF 4.4.3 (STM32F405)
- `racer xing.txt` - CLI dump for Xing racer, BF 4.5.1 (STM32F405)
- `scythe.txt` - CLI dump for Scythe, BF 4.4.2 (STM32F405)
- `sideways 65 1-3 setup.txt` - setup notes for sideways 65 (1-3), BF 4.5.0
- `sideways 65 panda 1-3 setup.txt` - setup notes for sideways 65 panda (1-3), BF 4.5.0
- `vtx switch setup.txt` - AUX6 VTX switch ranges and VTX table lines for Air65 + Reaper

## Use
1. Open Betaflight Configurator and connect to the FC.
2. Go to the CLI tab.
3. Paste the contents of the relevant file.
4. Type `save` to reboot and apply changes.

## Notes
- These dumps are hardware-specific. Verify board target, receiver mapping, motor order, and VTX table before applying.
- If you only need a subset of settings, consider copying just those sections instead of a full dump.

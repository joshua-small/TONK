# Documentation

This folder holds design specs, internal documentation, diagrams, and planning notes for the TONK controller project.

## External Libraries

This project uses the following third-party KiCad libraries as Git submodules:

### [XenGi/teensy_library](https://github.com/XenGi/teensy_library)

- 📁 Used for: **Teensy Symbol Definitions** in KiCad
- 📝 License: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
- 👤 Original Author: [@XenGi](https://github.com/XenGi)
- 💡 Cloned into: `libs/teensy_library`

### [XenGi/teensy.pretty](https://github.com/XenGi/teensy.pretty)

- 📁 Used for: **Teensy Footprint Library** in KiCad
- 📝 License: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
- 👤 Original Author: [@XenGi](https://github.com/XenGi)
- 💡 Cloned into: `libs/teensy.pretty`

### Usage Notes

These libraries are included as Git submodules for convenience and to preserve updateability. To initialize them after cloning the repo:

```bash
git submodule update --init --recursive
```

### License

This project includes third-party content under the CC BY-SA 4.0 license:

- teensy_library by XenGi: <https://github.com/XenGi/teensy_library>
- teensy.pretty by XenGi: <https://github.com/XenGi/teensy.pretty>

Changes may have been made. Original license preserved.

## Reference Materials

- [TI App Note – Gaming Trigger With Hall-Effect Sensors (SLYA072)](https://www.ti.com/lit/SLYA072)

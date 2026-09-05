# SoftRF Online Configurator

Offline configuration tool for SoftRF devices.

The command format, parameter layout and default values are based on the SoftRF project.

For detailed information about SoftRF configuration options, please refer to the original documentation:

- [SoftRF Dongle Settings](https://github.com/lyusupov/SoftRF/wiki/Dongle-settings)

The SoftRF online settings tool generates the NMEA command that can be pasted into a serial or Bluetooth terminal to configure a SoftRF device.

You can save the `index.html` file and use it completely offline, or run it directly from GitHub Pages.

The integrated decoder can verify and restore previously generated PSRFC commands.

Paste an existing `$PSRFC...` command into the **Decode PSRFC Sequence** section to:

- verify the NMEA checksum
- restore all settings into the user interface
- compare the regenerated command with the original input

## Live Application

➡️ [Open SoftRF Online Configurator](https://gh4chris.github.io/SoftRF-online-configurator/)

## Features

- 100% offline operation
- Single self-contained HTML file
- Automatic NMEA checksum calculation
- PSRFC command decoder and validator
- Light and dark theme
- English, German and Russian user interface
- No external dependencies
- GPL-3.0 licensed

## Credits

The original SoftRF project and protocol definitions are maintained by the SoftRF community:

- [SoftRF Project](https://github.com/lyusupov/SoftRF)
- [SoftRF Wiki](https://github.com/lyusupov/SoftRF/wiki)

## License

This project is licensed under the GNU General Public License v3.0 or later (GPL-3.0-or-later).

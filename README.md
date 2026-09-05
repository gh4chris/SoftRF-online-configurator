# SoftRF Online Configurator

Offline configuration tool for SoftRF devices.

- [Inspired by the soaringweather page](http://soaringweather.no-ip.info/SoftRF/settings.html)

The command format, parameter layout and default values are based on the information found at Linar's SoftRF project.

For detailed information about SoftRF configuration options, please refer to the original documentation:

- [SoftRF Dongle Settings](https://github.com/lyusupov/SoftRF/wiki/Settings)

The SoftRF online settings tool generates the NMEA command that can be pasted into a serial or Bluetooth terminal to configure a SoftRF device.

- [Find out how to connect the device on Linar's page](https://github.com/lyusupov/SoftRF/wiki/Dongle-settings)
- [You might want to use a web serial terminal with autoconnect setting for more comfort and see all boot messages](https://googlechromelabs.github.io/serial-terminal/)

You can save the `index.html` file provided in this repo, save it and use it completely offline, or run it directly here as a 

## Live Application

➡️ [Open SoftRF Online Configurator](https://gh4chris.github.io/SoftRF-online-configurator/)

The integrated decoder can verify and restore previously generated PSRFC commands.

Paste an existing `$PSRFC...` command into the **Decode PSRFC Sequence** section to:

- verify the NMEA checksum
- restore all settings into the user interface
- compare the regenerated command with the original input
  
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
![GPLv3 Logo](https://www.gnu.org/graphics/gplv3-with-text-136x68.png)

This project is licensed under the GNU General Public License v3.0 or later (GPL-3.0-or-later).

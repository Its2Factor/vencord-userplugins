# Vencord Plugins

A collection of custom plugins for [Vencord](https://vencord.dev/), a Discord client mod that enhances your Discord experience.

## 📋 Table of Contents

- [About](#about)
- [Requirements](#requirements)
- [Installation](#installation)
- [Available Plugins](#available-plugins)
- [Contributing](#contributing)
- [License](#license)

## About

This repository contains custom Vencord plugins developed to extend Discord's functionality. Each plugin is self-contained in its own directory with its own documentation.

## Requirements

- [Vencord](https://vencord.dev/) Discord client mod
- Discord desktop app
- Node.js (for development only)

## Installation

### Installing Plugins

Each plugin can be installed individually. See the plugin's README for specific installation instructions.

#### General Installation Steps

1. **Locate your Vencord userplugins directory:**
   - **Windows**: `%appdata%\Vencord\plugins\userplugins\`
   - **Linux/Mac**: `~/.config/Vencord/plugins/userplugins/`

2. **Clone or download the plugin folder:**
   - Copy the desired plugin folder (e.g., `voiceChannelLogger`) to your userplugins directory

3. **Restart Discord or reload Vencord:**
   - Restart Discord completely, or
   - Use Vencord's reload functionality

#### Using Vencord Plugin Manager

Some plugins may be available through Vencord's built-in plugin manager:
1. Open Vencord Settings
2. Go to the Plugins tab
3. Search for the plugin name
4. Enable the plugin

## Available Plugins

### [Voice Channel Logger](./voiceChannelLogger/)

A lightweight plugin that tracks voice channel joins and leaves in real-time with timestamps and user details.

**Features:**
- Real-time logging of voice channel activity
- Advanced search and filtering
- Toast notifications
- Session duration tracking
- Modern UI with pagination
- Persistent storage

[View Plugin README →](./voiceChannelLogger/README.md)

---

## Contributing

Contributions are welcome! If you'd like to contribute:

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/amazing-plugin`)
3. Commit your changes (`git commit -m 'Add some amazing plugin'`)
4. Push to the branch (`git push origin feature/amazing-plugin`)
5. Open a Pull Request

## License

This project is licensed under the GPL-3.0-or-later License. Individual plugins may have their own license files - see each plugin's directory for details.

See the [LICENSE](./voiceChannelLogger/LICENSE) file for the full license text.

## Disclaimer

These plugins are community-developed and not officially affiliated with Discord or Vencord. Use at your own risk.

---

**Note**: Make sure you have Vencord installed and properly configured before using any of these plugins. For more information about Vencord, visit [vencord.dev](https://vencord.dev/).


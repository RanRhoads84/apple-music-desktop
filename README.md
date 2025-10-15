# Apple Music Desktop &nbsp;<img src="Logo.png" width="48">

An [Electron](https://www.electronjs.org/) app that provides a native Apple Music experience for Linux.

## Features

- Native desktop experience for Apple Music on Linux
- Tray icon with playback controls (Play/Pause, Next, Previous, Show/Minimize, Quit)
- Customizable menu with settings for theme, start tab, and more
- Mini Player mode
- About window showing app, Electron, Chromium, Node, and V8 versions
- Logging and configuration management
- Support for multiple package formats (zip, deb, AppImage, snap, nsis, dmg, etc.)

## Screenshot

![Screenshot](assets/screenshot.png)

## Installation

See the [Releases](https://github.com/RanRhoads84/apple-music-desktop/releases/tag/Release) page for pre-built Linux binaries.

Notes:
- AppImage: Make the file executable and run it. On most distros: `chmod +x apple-music_2.2.0_x86_64.AppImage` then `./apple-music_2.2.0_x86_64.AppImage`.
- DEB: Install with your package manager on Ubuntu 25.10 or compatible derivatives.
- Snap: Install via `snap install --dangerous apple-music_2.2.0_amd64.snap` or from the Snap Store if available.

## Building

Requires Node.js 16 or 18. It is recommended to use [nvm](https://github.com/nvm-sh/nvm) for managing Node versions.

```sh
git clone https://github.com/Alex313031/apple-music-desktop.git
cd apple-music-desktop
nvm install        # Only if using nvm
npm install        # Install dependencies
npm run start      # Run app in dev mode
```

### Packaging

To build distributable packages:

```sh
npm run build      # Build unpacked app
npm run dist       # Build distributable packages
```

See [`build.sh`](build.sh) for additional build and packaging scripts.

## Configuration

- App settings are stored using [`electron-store`](https://github.com/sindresorhus/electron-store).
- Configuration file: `config.json` in the user data directory.
- Logging is available and can be enabled/disabled via the menu.

## License

BSD 3-Clause License
Copyright © 2024-2025 Alex313031

See [LICENSE.md](LICENSE.md) for details.

## Credits

- Developer: [Alex313031](https://github.com/Alex313031)
- Thanks to: ciderapp, sindresorhus, castlabs, electronjs

See [humans.txt](src/humans.txt) for more.

## TODO

See [TODO.txt](TODO.txt)

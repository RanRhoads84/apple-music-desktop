# Release Notes

## v2.2.0 — 2025-10-15

Apple Music Desktop 2.2.0 brings a smoother Linux desktop experience and refreshed docs.

### Highlights
- Added README Downloads section with direct links to AppImage, DEB, and Snap
- General documentation cleanup and clarifications
- Built with Electron 30.5.1 (castLabs wvcus)

### Downloads
- AppImage (x86_64): [release/apple-music_2.2.0_x86_64.AppImage](release/apple-music_2.2.0_x86_64.AppImage)
- Ubuntu 25.10 DEB (amd64): [release/apple-music_2.2.0_Ubuntu-25.10_amd64.deb](release/apple-music_2.2.0_Ubuntu-25.10_amd64.deb)
- Snap (amd64): [release/apple-music_2.2.0_amd64.snap](release/apple-music_2.2.0_amd64.snap)

### Checksums (SHA256)
```
cff7ca331059c830558965412c3a265aa66ad269c78d34b1db514f64793148fe  apple-music_2.2.0_amd64.snap
3a829578392fb32ae86f8da304d9b150895d30787362f3d8b4fe187495e7d266  apple-music_2.2.0_Ubuntu-25.10_amd64.deb
395b5329eee24fd02697eb72113ae9f74d6a0ea313bd076197df86fe26211bd1  apple-music_2.2.0_x86_64.AppImage
```

### Install notes
- AppImage: `chmod +x apple-music_2.2.0_x86_64.AppImage` then `./apple-music_2.2.0_x86_64.AppImage`
- DEB (Ubuntu 25.10): `sudo apt install ./apple-music_2.2.0_Ubuntu-25.10_amd64.deb`
- Snap: `sudo snap install --dangerous apple-music_2.2.0_amd64.snap`

### Tech
- Electron: castLabs 30.5.1+wvcus
- Node: >= 18 (see `package.json` engines)

### Credits
- Thanks to contributors and the Electron community.

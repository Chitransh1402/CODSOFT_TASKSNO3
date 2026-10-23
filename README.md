# Waveform Music Player

A responsive browser-based music player built with plain HTML, CSS, and JavaScript. It supports local audio playback, playlists, search, favorites, shuffle, repeat, seek, volume, and mute.

## Run it

1. Extract `music-player.zip`.
2. Open `index.html` in a modern browser.
3. Click **＋ Add music** or **Import music** and select audio files on your device.
4. Double-click a track in the library to play it. Use the bottom player to seek, change volume, skip tracks, or toggle shuffle/repeat.

No build tools or server are required. For best results, use a current version of Chrome, Edge, Firefox, or Safari.

## Features

- Play/pause, next, previous, and automatic playback-time updates
- Seekable progress bar and duration display
- Volume slider and mute toggle
- Import local audio files using the browser file picker
- Search by track, artist, or album
- Favorites and playlist creation
- Shuffle, repeat-all, and repeat-one modes
- Responsive layout for desktop and mobile
- Keyboard shortcuts: `Space` toggles playback; `Ctrl/⌘ + K` focuses search

## Notes

- Audio files stay local to the browser session; this project does not upload them.
- The cover art shown before you import music is decorative placeholder artwork, not playable sample tracks.
- Browser object URLs are temporary. Re-import your files after refreshing the page.
- Playlist membership is initialized from the current library when you create a playlist. This demo does not persist the library or playlists between refreshes.

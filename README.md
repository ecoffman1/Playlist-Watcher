# YouTube Playlist Tracker

A lightweight, single-file web app for keeping your place in YouTube playlists. No login, no account — just paste a playlist URL and pick up where you left off.

## Features

- **Resume playback** — saves your position (video + timestamp) automatically every 2.5 seconds
- **Sidebar navigation** — see all videos in the playlist, jump to any, and mark videos as watched
- **Multiple playlists** — save and manage as many playlists as you want
- **No setup** — everything is stored in your browser's localStorage; no server required

## Usage

1. Open `index.html` in a browser
2. Paste a YouTube playlist URL or ID into the input field and hit **Load**
3. Watch — your progress saves automatically
4. Come back later and hit **Resume** to pick up where you left off

## Tech

Pure HTML/CSS/JS, no build step or dependencies. Uses the YouTube IFrame API and the noembed.com API for metadata.

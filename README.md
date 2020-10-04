# syncvibes
Universal format for asynchronously syncing playlists between multiple devices/players.

This project is a WIP. It's something I've wanted for a long time, but never got around to building. I currently don't have the capacity to dedicate myself to this, but figured there might be a bunch of people online who are interested. If so, I can contribute where possible. You can contact me via [my portfolio](https://danieljs.tech) if you're keen.

## Features

* A universal format for importing/exporting playlists between all media players and devices
* Data is saved in the filesystem to make syncing easy (so you can use an app like [Syncthing](https://syncthing.net) to easily sync music between devices) 
* Asynchronous syncing of music without the need of a centralised server (so if you update a playlist on one device, it can be reflected on another without conflicts, and vice versa)
* Fast and lightweight
* Easy-to-use API with libraries for popular programming languages
* Utilities for quickly running a sync, which can be run at the app's startup (or whenever is optimal)
* Ledger with a single source of truth for organising music files to prevent duplicates
* Utility for organising music into a user-friendly tree
* Utility for accurately removing identifying, removing, and updating duplicates 
* Sync playlists without the use of external syncing apps (which are often inaccurate and don't sync 100% of music; are frequently paid; and may mine your data)
* Keeps track of music that wasn't synced (such as importing music from Spotify to TIDAL that wasn't available), so you're able to keep track of what's missing in your library between players
* Detailed and neat playlist files (in `.json` or something), instead of messy files such as `.pls`
* Fragmented song metadata (such as title, artist, and album) to make granular and accurate searches easy
* Support for other nodes, such as albums (to replace `.m3u`) 

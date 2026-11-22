# Stremio Remote plugin repository

Watch movies and shows from Stremio inside Final Fantasy XIV: in a window, on a screen in the game world, or on a
minion with the Background Screen mod. Watch together with your Lightless Sync pairs.

## Install
1. In game, open `/xlsettings` -> **Experimental**.
2. Under **Custom Plugin Repositories**, paste this URL, click **+**, then **Save and Close**:

   `https://raw.githubusercontent.com/Clair-songs/StremioRemote-plugins/main/pluginmaster.json`

3. Open `/xlplugins`, search for **Stremio Remote** and click **Install**.
4. Type `/stremio` to open it.

Updates arrive through `/xlplugins` like any other plugin.

## What you need
- **The Stremio desktop app** on the same PC: the in-game player uses the video library that comes with it, and
  torrent streams are downloaded by Stremio's streaming server (Stremio can stay minimized).
- **Your Stremio addons**: in the plugin, Settings -> Stream addons, paste each addon's link (its manifest.json URL).
- Optional, for **watch parties** with friends: **Lightless Sync** (paired with each other) and **SimpleHeels**
  (it carries the watch-party info; you don't have to use heels). Everyone needs Stremio Remote.
- Optional, for the **minion screen**: the **Background Screen** mod for Penumbra
  (https://www.xivmodarchive.com/modid/112306), which turns the Plush Cushion into a screen.
- Optional, for **YouTube/Twitch** links: yt-dlp (the plugin can download it for you, or reuse one another plugin
  already downloaded).

## Quick start
- Search a title -> **Watch in game** -> pick a stream.
- `/stremio screen` to put the video on a screen in the world or on your minion.
- Friends nearby in your watch party: they get a chat message and click **Watch together**, or type `/stremio join`.

Stremio Remote is a fan-made plugin and isn't affiliated with Stremio or Square Enix. Like all third-party
Dalamud plugins, use it at your own risk.
# Echo

A small browser game where you navigate a dark maze by sound alone. Put on headphones.

The game is designed to be playable without sight. The screen is almost black on purpose, all gameplay information comes through stereo audio, and every menu and event is spoken aloud.

## Play

Open `index.html` in a desktop browser (no install, no build step). Click or press any key to start.

## Controls

| Key | Action |
| --- | --- |
| WASD / arrows | Move |
| Space | Ping: echoes reveal walls and hunters, but hunters hear it too |
| F | Strike a nearby hunter to stun it |
| 1 to 9 | Jump to a level (from any menu screen) |
| H | Hear your status: level, lives, pings, bells |
| V | Turn spoken announcements on or off (screen reader users: turn off, messages go to your reader) |

Left and right in your ears is left and right on the map. Higher pitch means further up.

## Levels

1. **The Hollow**: small maze, one heavy hunter.
2. **Two Sounds**: a heavy and a light hunter that sound different.
3. **Silent Exit**: the exit is silent until you find three bells.
4. **False Walls**: some echoes lie.
5. **Last Breath**: limited pings.

After level 5, endless "Deeper" levels get bigger and harder. Every level generates a new random maze.

## Accessibility

- Spoken announcements use the browser's built-in text to speech. They start after your first key press, because browsers block speech before any interaction.
- If you use a screen reader, press V during play to switch off the built-in voice. Messages are then sent to a live region your screen reader announces.
- Gameplay relies on stereo headphones. Left or right in your ears is left or right on the map, and higher pitch is further up.
- This has not yet been tested with blind players or with every screen reader. Feedback is welcome.

## Hosting

Enable GitHub Pages (Settings, Pages, deploy from the `main` branch root) to play it at a public link.

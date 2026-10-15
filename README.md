# GIFs

A GIF channel viewer hosted on GitHub Pages.

- The first GIF plays as soon as the page opens, with **channel 0 (automatic mode)** selected by default.
- In automatic mode, the viewer switches to a different random channel every **30–60 seconds**, choosing a new random interval each time.
- Press **0** to return to automatic mode. Press **1** or **2** to stay on that channel (number pad supported).
- On a phone, **tap once** to cycle through **0 → 1 → 2 → 0**. Channel 0 keeps the current GIF playing until its next automatic switch. The cycle includes any channels added to the channel list.
- On a phone, **double tap** to enter fullscreen where supported by the browser. Double tapping does not change the channel.
- On a computer, use **F11** for native browser fullscreen.
- The page never requests fullscreen on load, ordinary clicks, single taps, or keypresses.
- Each GIF stretches to fill the viewer without borders or additional UI.

GitHub Pages serves the root of the `main` branch. All assets use relative paths. Add channels to the `channels` array in `index.html` to extend the channel cycle and automatic selection.

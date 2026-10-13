# GIFs

A fullscreen GIF viewer hosted on GitHub Pages.

- The first GIF plays as soon as the page opens.
- The page requests fullscreen on arrival. If the browser blocks automatic entry, the first click or keypress retries it.
- Press **1** for the first GIF and **2** for the second (including the number pad).
- Press **Esc** to exit page fullscreen. F11 remains available for native browser fullscreen.
- Each GIF stretches to fill the entire display without borders.

The page shows only the active GIF. It requests fullscreen for the entire document and fills the display without additional UI. Browser security usually requires a click or keypress before entering fullscreen; websites cannot trigger F11 themselves.

GitHub Pages serves the root of the `main` branch. All assets use relative paths.

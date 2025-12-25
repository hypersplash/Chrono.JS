# Chrono.JS

Chrono.JS is a lightweight, browser-based clock built with pure HTML, CSS, and JavaScript.

## Features

- Real-time clock using the native `Date` API  
- Ten selectable color themes inspired by Monkeytype  
- 12-hour and 24-hour time format toggle  
- Smooth CSS-based animations and transitions  
- Responsive design for any screen size  
- No external dependencies

## Themes

- **default** — Neutral gray  
- **dracula** — Dark mode  
- **serika** — Yellow accent  
- **nord** — Cool and minimal  
- **retrocast** — Warm retro tones  
- **red samurai** — Red contrast  
- **monokai** — Classic developer palette  
- **8008** — Pink highlight  
- **laser** — Neon aesthetic  
- **olivia** — Soft cream palette

## Usage

Run Chrono.JS in one of the following ways:

1. **Locally** — Download or clone the repository and open `index.html` in a browser.  
2. **Online** — Use the GitHub Pages link available on the repository page.

### Controls

- Click the **⚙️** icon to open settings  
- Select a theme name to switch instantly  
- Use the format toggle to change between 12h and 24h  
- Click outside the settings panel to close it

## Installation

```bash
git clone https://github.com/hypersplash/Chrono.js.git
cd Chrono.js
open index.html
```

Or download the HTML file and open it directly in a browser.

## Technical Overview

- Time updated every second via `setInterval`  
- Date formatted using `Date.toLocaleDateString()`  
- Smooth theme transitions handled with CSS  
- Monospace font (`Courier New`) for alignment consistency  
- Fixed-position settings panel with slide-in animation

## Contributing

Contributions are welcome. Keep additions minimal and stylistically consistent.

## License

[MIT License](./LICENSE)

---

Inspired by late-night typing sessions and minimalist web design.
May or may not be partially broken and written by AI but who knows?

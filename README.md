# Chrono.JS

A clock in your browser, that's basically what it is

## Features

- **Real-time clock** using JavaScript's native Date API
- **10 handpicked themes** from Monkeytype's most iconic colorways
- **24h/12h format toggle** for your preference
- **Smooth animations** and transitions throughout
- **Zero dependencies** - pure HTML, CSS, and JavaScript
- **Responsive design** that scales beautifully on any screen

## Themes

- **default** - Classic gray elegance
- **dracula** - Dark vampire vibes
- **serika** - Bold yellow energy
- **nord** - Arctic minimalism
- **retrocast** - Nostalgic warmth
- **red samurai** - Crimson intensity
- **monokai** - Developer's favorite
- **8008** - Pink punch
- **laser** - Cyberpunk neon
- **olivia** - Creamy sophistication

## Usage

There are two ways to do this

1. Through the HTML file (you'll need to download the file from the repository)
2. Through the GitHub Pages link (you can probably find this on the repository page)

Some useful information
- Click the **⚙ gear icon** (top right) to open theme settings
- Click any **theme name** to switch instantly
- Use the **format toggle** button to switch between 12h and 24h time
- Click outside the settings panel to close it

## Installation

```bash
# Clone the repo
git clone https://github.com/hypersplash/Chrono.js.git

# Open in browser
open index.html
```

Or just download the HTML file and double-click it.

## Why Chrono.JS?

Sometimes you just need a clean, good-looking clock in your browser. No bloat, no tracking, no BS. Perfect for:

- Keeping a tab open for quick time checks
- Second monitor eye candy
- Learning basic web development
- Appreciating minimalist design

## Technical Details

- Updates every second via `setInterval`
- Uses `Date.toLocaleDateString()` for properly formatted dates
- CSS transitions for smooth theme switching
- Monospace font (`Courier New`) for that typing test aesthetic
- Fixed positioning for settings panel with slide-in animation
- Tabular nums for consistent digit width in the clock display

## Contributing

Found a bug? Want to add more themes? PRs are welcome. Keep it minimal, keep it clean.

## License

MIT - do whatever you want with it.

---

Built with ⚙️ and inspired by countless late-night typing sessions on Monkeytype.

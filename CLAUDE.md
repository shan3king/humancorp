# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Static "coming soon" landing page for humancorp. Pure HTML/CSS/JS with no build tools or dependencies.

## Development

Preview the site by opening `index.html` directly in a browser, or run a local server:

```bash
npx serve .
```

## Architecture

- `index.html` - Single-page landing with 3D glasses effect (cyan/magenta parallax layers using CSS `mix-blend-mode: multiply`)
- `fonts/` - Alte Haas Grotesk font files (woff/woff2) - must be added manually

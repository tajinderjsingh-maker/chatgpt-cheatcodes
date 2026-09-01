# ChatGPT Cheatcode Repository

A GitHub-ready static webpage for a curated library of composable prompt operators.

## Files
- `index.html` — self-contained webpage (HTML + CSS + JS)
- `commands.json` — editable source of the command repository

## Features
- 250 curated operator codes + clearly labelled official examples
- Category color coding
- Search
- Category filters
- One-click copy
- Multi-command builder
- Optional subject field
- Responsive/mobile layout
- No build step or external dependency

## Important terminology
Most `/codes` are **custom prompt shorthand**, not official hidden ChatGPT slash commands. Official examples are labelled in the UI.

## GitHub Pages
Upload the files to a repository, enable GitHub Pages for the branch/folder containing `index.html`, and the page can be served as a static site.

## Extending
Edit `commands.json` and regenerate `index.html` if you want to add commands to the current bundled version. The page intentionally keeps the first release dependency-free so it is easy to host and maintain.

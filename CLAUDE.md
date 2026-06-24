# Project: Norman Valenzuela Portfolio

## Safeguard Rails

### NEVER do these without explicit user approval:
- **No commits** — Do not run `git commit` without the user saying "commit" or "yes, commit"
- **No pushes** — Do not run `git push` without explicit approval
- **No permanent deletion** — Do not delete files, directories, or content permanently. If something needs removing, comment it out or move it to a backup section first
- **No force operations** — No `git reset --hard`, `git push --force`, `rm -rf`, or any destructive command
- **No branch deletion** — Do not delete any git branches
- **No overwriting uncommitted work** — Always check `git status` before any operation that could lose changes

### Safe defaults:
- Edits to index.html and asset files are allowed
- Creating new files is allowed
- Running local dev servers is allowed
- Reading files is always allowed
- Git status, diff, and log are always allowed

### Project Structure
- Static single-page site for GitHub Pages deployment
- Main file: `index.html`
- Keep it as a single HTML file with embedded CSS/JS for simplicity
- All assets (images) go in an `/assets` directory if needed

### Design Tokens (reference)
- Primary accent: amber/gold
- Secondary: navy blue
- Fonts: Clash Display (headings), Satoshi (body)
- Dark mode is default theme
